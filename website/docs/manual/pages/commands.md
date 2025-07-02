---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /pages/commands
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - page
toc_max_heading_level: 4

---

<div class="doxyPage">

# Special Commands




## Introduction {#cmd_intro}


All commands in the documentation start with a backslash (<b>\\</b>) or an at-sign (<b>@</b>). If you prefer you can replace all commands starting with a backslash below by their counterparts that start with an at-sign.

Some commands have one or more arguments. Each argument has a certain range:

<ul class="doxyList ">
<li>If &lt;sharp&gt; braces are used the argument is a single word.</li>
<li>If (round) braces are used the argument extends until the end of the line on which the command was found.</li>
<li>If {curly} braces are used the argument extends until the next paragraph. Paragraphs are delimited by a blank line or by a section indicator. Note that {curly} braces are also used for command options, here the braces are mandatory and just 'normal' characters. The starting curly brace has to directly follow the command, so without whitespace.</li>
</ul>

If in addition to the above argument specifiers \[square\] brackets are used the argument is optional, unless they are placed between quotes in that case they are a mandatory part of the command argument.

Here is an alphabetically sorted list of all commands with references to their documentation: <a id="showsecreflist"></a>


<ul class="doxyTocList">
<li><a class="doxyTocListItem" href="#cmda">\a</a></li>
<li><a class="doxyTocListItem" href="#cmdaddindex">\addindex</a></li>
<li><a class="doxyTocListItem" href="#cmdaddtogroup">\addtogroup</a></li>
<li><a class="doxyTocListItem" href="#cmdanchor">\anchor</a></li>
<li><a class="doxyTocListItem" href="#cmdarg">\arg</a></li>
<li><a class="doxyTocListItem" href="#cmdattention">\attention</a></li>
<li><a class="doxyTocListItem" href="#cmdauthor">\author</a></li>
<li><a class="doxyTocListItem" href="#cmdauthors">\authors</a></li>
<li><a class="doxyTocListItem" href="#cmdb">\b</a></li>
<li><a class="doxyTocListItem" href="#cmdbrief">\brief</a></li>
<li><a class="doxyTocListItem" href="#cmdbug">\bug</a></li>
<li><a class="doxyTocListItem" href="#cmdc">\c</a></li>
<li><a class="doxyTocListItem" href="#cmdcallergraph">\callergraph</a></li>
<li><a class="doxyTocListItem" href="#cmdcallgraph">\callgraph</a></li>
<li><a class="doxyTocListItem" href="#cmdcategory">\category</a></li>
<li><a class="doxyTocListItem" href="#cmdcite">\cite</a></li>
<li><a class="doxyTocListItem" href="#cmdclass">\class</a></li>
<li><a class="doxyTocListItem" href="#cmdcode">\code</a></li>
<li><a class="doxyTocListItem" href="#cmdcollaborationgraph">\collaborationgraph</a></li>
<li><a class="doxyTocListItem" href="#cmdconcept">\concept</a></li>
<li><a class="doxyTocListItem" href="#cmdcond">\cond</a></li>
<li><a class="doxyTocListItem" href="#cmdcopybrief">\copybrief</a></li>
<li><a class="doxyTocListItem" href="#cmdcopydetails">\copydetails</a></li>
<li><a class="doxyTocListItem" href="#cmdcopydoc">\copydoc</a></li>
<li><a class="doxyTocListItem" href="#cmdcopyright">\copyright</a></li>
<li><a class="doxyTocListItem" href="#cmddate">\date</a></li>
<li><a class="doxyTocListItem" href="#cmddef">\def</a></li>
<li><a class="doxyTocListItem" href="#cmddefgroup">\defgroup</a></li>
<li><a class="doxyTocListItem" href="#cmddeprecated">\deprecated</a></li>
<li><a class="doxyTocListItem" href="#cmddetails">\details</a></li>
<li><a class="doxyTocListItem" href="#cmddiafile">\diafile</a></li>
<li><a class="doxyTocListItem" href="#cmddir">\dir</a></li>
<li><a class="doxyTocListItem" href="#cmddirectorygraph">\directorygraph</a></li>
<li><a class="doxyTocListItem" href="#cmddocbookinclude">\docbookinclude</a></li>
<li><a class="doxyTocListItem" href="#cmddocbookonly">\docbookonly</a></li>
<li><a class="doxyTocListItem" href="#cmddontinclude">\dontinclude</a></li>
<li><a class="doxyTocListItem" href="#cmddot">\dot</a></li>
<li><a class="doxyTocListItem" href="#cmddotfile">\dotfile</a></li>
<li><a class="doxyTocListItem" href="#cmddoxyconfig">\doxyconfig</a></li>
<li><a class="doxyTocListItem" href="#cmde">\e</a></li>
<li><a class="doxyTocListItem" href="#cmdelse">\else</a></li>
<li><a class="doxyTocListItem" href="#cmdelseif">\elseif</a></li>
<li><a class="doxyTocListItem" href="#cmdem">\em</a></li>
<li><a class="doxyTocListItem" href="#cmdemoji">\emoji</a></li>
<li><a class="doxyTocListItem" href="#cmdendcode">\endcode</a></li>
<li><a class="doxyTocListItem" href="#cmdendcond">\endcond</a></li>
<li><a class="doxyTocListItem" href="#cmdenddocbookonly">\enddocbookonly</a></li>
<li><a class="doxyTocListItem" href="#cmdenddot">\enddot</a></li>
<li><a class="doxyTocListItem" href="#cmdendhtmlonly">\endhtmlonly</a></li>
<li><a class="doxyTocListItem" href="#cmdendif">\endif</a></li>
<li><a class="doxyTocListItem" href="#cmdendinternal">\endinternal</a></li>
<li><a class="doxyTocListItem" href="#cmdendlatexonly">\endlatexonly</a></li>
<li><a class="doxyTocListItem" href="#cmdendlink">\endlink</a></li>
<li><a class="doxyTocListItem" href="#cmdendmanonly">\endmanonly</a></li>
<li><a class="doxyTocListItem" href="#cmdendmsc">\endmsc</a></li>
<li><a class="doxyTocListItem" href="#cmdendparblock">\endparblock</a></li>
<li><a class="doxyTocListItem" href="#cmdendrtfonly">\endrtfonly</a></li>
<li><a class="doxyTocListItem" href="#cmdendsecreflist">\endsecreflist</a></li>
<li><a class="doxyTocListItem" href="#cmdendverbatim">\endverbatim</a></li>
<li><a class="doxyTocListItem" href="#cmdenduml">\enduml</a></li>
<li><a class="doxyTocListItem" href="#cmdendxmlonly">\endxmlonly</a></li>
<li><a class="doxyTocListItem" href="#cmdenum">\enum</a></li>
<li><a class="doxyTocListItem" href="#cmdexample">\example</a></li>
<li><a class="doxyTocListItem" href="#cmdexception">\exception</a></li>
<li><a class="doxyTocListItem" href="#cmdextends">\extends</a></li>
<li><a class="doxyTocListItem" href="#cmdfrndopen">\f(</a></li>
<li><a class="doxyTocListItem" href="#cmdfrndclose">\f)</a></li>
<li><a class="doxyTocListItem" href="#cmdfdollar">\f$</a></li>
<li><a class="doxyTocListItem" href="#cmdfbropen">\f[</a></li>
<li><a class="doxyTocListItem" href="#cmdfbrclose">\f]</a></li>
<li><a class="doxyTocListItem" href="#cmdfcurlyopen">\f{</a></li>
<li><a class="doxyTocListItem" href="#cmdfcurlyclose">\f}</a></li>
<li><a class="doxyTocListItem" href="#cmdfile">\file</a></li>
<li><a class="doxyTocListItem" href="#cmdfileinfo">\fileinfo</a></li>
<li><a class="doxyTocListItem" href="#cmdfn">\fn</a></li>
<li><a class="doxyTocListItem" href="#cmdgroupgraph">\groupgraph</a></li>
<li><a class="doxyTocListItem" href="#cmdheaderfile">\headerfile</a></li>
<li><a class="doxyTocListItem" href="#cmdhidecallergraph">\hidecallergraph</a></li>
<li><a class="doxyTocListItem" href="#cmdhidecallgraph">\hidecallgraph</a></li>
<li><a class="doxyTocListItem" href="#cmdhidecollaborationgraph">\hidecollaborationgraph</a></li>
<li><a class="doxyTocListItem" href="#cmdhidedirectorygraph">\hidedirectorygraph</a></li>
<li><a class="doxyTocListItem" href="#cmdhideenumvalues">\hideenumvalues</a></li>
<li><a class="doxyTocListItem" href="#cmdhidegroupgraph">\hidegroupgraph</a></li>
<li><a class="doxyTocListItem" href="#cmdhideincludedbygraph">\hideincludedbygraph</a></li>
<li><a class="doxyTocListItem" href="#cmdhideincludegraph">\hideincludegraph</a></li>
<li><a class="doxyTocListItem" href="#cmdhideinheritancegraph">\hideinheritancegraph</a></li>
<li><a class="doxyTocListItem" href="#cmdhideinlinesource">\hideinlinesource</a></li>
<li><a class="doxyTocListItem" href="#cmdhiderefby">\hiderefby</a></li>
<li><a class="doxyTocListItem" href="#cmdhiderefs">\hiderefs</a></li>
<li><a class="doxyTocListItem" href="#cmdhideinitializer">\hideinitializer</a></li>
<li><a class="doxyTocListItem" href="#cmdhtmlinclude">\htmlinclude</a></li>
<li><a class="doxyTocListItem" href="#cmdhtmlonly">\htmlonly</a></li>
<li><a class="doxyTocListItem" href="#cmdidlexcept">\idlexcept</a></li>
<li><a class="doxyTocListItem" href="#cmdif">\if</a></li>
<li><a class="doxyTocListItem" href="#cmdifnot">\ifnot</a></li>
<li><a class="doxyTocListItem" href="#cmdimage">\image</a></li>
<li><a class="doxyTocListItem" href="#cmdimplements">\implements</a></li>
<li><a class="doxyTocListItem" href="#cmdimportant">\important</a></li>
<li><a class="doxyTocListItem" href="#cmdinclude">\include</a></li>
<li><a class="doxyTocListItem" href="#cmdincludedoc">\includedoc</a></li>
<li><a class="doxyTocListItem" href="#cmdincludedbygraph">\includedbygraph</a></li>
<li><a class="doxyTocListItem" href="#cmdincludegraph">\includegraph</a></li>
<li><a class="doxyTocListItem" href="#cmdincludelineno">\includelineno</a></li>
<li><a class="doxyTocListItem" href="#cmdingroup">\ingroup</a></li>
<li><a class="doxyTocListItem" href="#cmdinheritancegraph">\inheritancegraph</a></li>
<li><a class="doxyTocListItem" href="#cmdinternal">\internal</a></li>
<li><a class="doxyTocListItem" href="#cmdinvariant">\invariant</a></li>
<li><a class="doxyTocListItem" href="#cmdinterface">\interface</a></li>
<li><a class="doxyTocListItem" href="#cmdlatexinclude">\latexinclude</a></li>
<li><a class="doxyTocListItem" href="#cmdlatexonly">\latexonly</a></li>
<li><a class="doxyTocListItem" href="#cmdli">\li</a></li>
<li><a class="doxyTocListItem" href="#cmdline">\line</a></li>
<li><a class="doxyTocListItem" href="#cmdlineinfo">\lineinfo</a></li>
<li><a class="doxyTocListItem" href="#cmdlink">\link</a></li>
<li><a class="doxyTocListItem" href="#cmdmainpage">\mainpage</a></li>
<li><a class="doxyTocListItem" href="#cmdmaninclude">\maninclude</a></li>
<li><a class="doxyTocListItem" href="#cmdmanonly">\manonly</a></li>
<li><a class="doxyTocListItem" href="#cmdmemberof">\memberof</a></li>
<li><a class="doxyTocListItem" href="#cmdmodule">\module</a></li>
<li><a class="doxyTocListItem" href="#cmdmsc">\msc</a></li>
<li><a class="doxyTocListItem" href="#cmdmscfile">\mscfile</a></li>
<li><a class="doxyTocListItem" href="#cmdn">\n</a></li>
<li><a class="doxyTocListItem" href="#cmdname">\name</a></li>
<li><a class="doxyTocListItem" href="#cmdnamespace">\namespace</a></li>
<li><a class="doxyTocListItem" href="#cmdnoop">\noop</a></li>
<li><a class="doxyTocListItem" href="#cmdnosubgrouping">\nosubgrouping</a></li>
<li><a class="doxyTocListItem" href="#cmdnote">\note</a></li>
<li><a class="doxyTocListItem" href="#cmdoverload">\overload</a></li>
<li><a class="doxyTocListItem" href="#cmdp">\p</a></li>
<li><a class="doxyTocListItem" href="#cmdpackage">\package</a></li>
<li><a class="doxyTocListItem" href="#cmdpage">\page</a></li>
<li><a class="doxyTocListItem" href="#cmdpar">\par</a></li>
<li><a class="doxyTocListItem" href="#cmdparagraph">\paragraph</a></li>
<li><a class="doxyTocListItem" href="#cmdparam">\param</a></li>
<li><a class="doxyTocListItem" href="#cmdparblock">\parblock</a></li>
<li><a class="doxyTocListItem" href="#cmdpost">\post</a></li>
<li><a class="doxyTocListItem" href="#cmdpre">\pre</a></li>
<li><a class="doxyTocListItem" href="#cmdprivate">\private</a></li>
<li><a class="doxyTocListItem" href="#cmdprivatesection">\privatesection</a></li>
<li><a class="doxyTocListItem" href="#cmdproperty">\property</a></li>
<li><a class="doxyTocListItem" href="#cmdprotected">\protected</a></li>
<li><a class="doxyTocListItem" href="#cmdprotectedsection">\protectedsection</a></li>
<li><a class="doxyTocListItem" href="#cmdprotocol">\protocol</a></li>
<li><a class="doxyTocListItem" href="#cmdpublic">\public</a></li>
<li><a class="doxyTocListItem" href="#cmdpublicsection">\publicsection</a></li>
<li><a class="doxyTocListItem" href="#cmdpure">\pure</a></li>
<li><a class="doxyTocListItem" href="#cmdqualifier">\qualifier</a></li>
<li><a class="doxyTocListItem" href="#cmdraisewarning">\raisewarning</a></li>
<li><a class="doxyTocListItem" href="#cmdref">\ref</a></li>
<li><a class="doxyTocListItem" href="#cmdrefitem">\refitem</a></li>
<li><a class="doxyTocListItem" href="#cmdrelated">\related</a></li>
<li><a class="doxyTocListItem" href="#cmdrelates">\relates</a></li>
<li><a class="doxyTocListItem" href="#cmdrelatedalso">\relatedalso</a></li>
<li><a class="doxyTocListItem" href="#cmdrelatesalso">\relatesalso</a></li>
<li><a class="doxyTocListItem" href="#cmdremark">\remark</a></li>
<li><a class="doxyTocListItem" href="#cmdremarks">\remarks</a></li>
<li><a class="doxyTocListItem" href="#cmdresult">\result</a></li>
<li><a class="doxyTocListItem" href="#cmdreturn">\return</a></li>
<li><a class="doxyTocListItem" href="#cmdreturns">\returns</a></li>
<li><a class="doxyTocListItem" href="#cmdretval">\retval</a></li>
<li><a class="doxyTocListItem" href="#cmdrtfinclude">\rtfinclude</a></li>
<li><a class="doxyTocListItem" href="#cmdrtfonly">\rtfonly</a></li>
<li><a class="doxyTocListItem" href="#cmdsa">\sa</a></li>
<li><a class="doxyTocListItem" href="#cmdsecreflist">\secreflist</a></li>
<li><a class="doxyTocListItem" href="#cmdsection">\section</a></li>
<li><a class="doxyTocListItem" href="#cmdsee">\see</a></li>
<li><a class="doxyTocListItem" href="#cmdshort">\short</a></li>
<li><a class="doxyTocListItem" href="#cmdshowdate">\showdate</a></li>
<li><a class="doxyTocListItem" href="#cmdshowenumvalues">\showenumvalues</a></li>
<li><a class="doxyTocListItem" href="#cmdshowinitializer">\showinitializer</a></li>
<li><a class="doxyTocListItem" href="#cmdshowinlinesource">\showinlinesource</a></li>
<li><a class="doxyTocListItem" href="#cmdshowrefby">\showrefby</a></li>
<li><a class="doxyTocListItem" href="#cmdshowrefs">\showrefs</a></li>
<li><a class="doxyTocListItem" href="#cmdsince">\since</a></li>
<li><a class="doxyTocListItem" href="#cmdskip">\skip</a></li>
<li><a class="doxyTocListItem" href="#cmdskipline">\skipline</a></li>
<li><a class="doxyTocListItem" href="#cmdsnippet">\snippet</a></li>
<li><a class="doxyTocListItem" href="#cmdsnippetdoc">\snippetdoc</a></li>
<li><a class="doxyTocListItem" href="#cmdsnippetlineno">\snippetlineno</a></li>
<li><a class="doxyTocListItem" href="#cmdstatic">\static</a></li>
<li><a class="doxyTocListItem" href="#cmdstartuml">\startuml</a></li>
<li><a class="doxyTocListItem" href="#cmdstruct">\struct</a></li>
<li><a class="doxyTocListItem" href="#cmdsubpage">\subpage</a></li>
<li><a class="doxyTocListItem" href="#cmdsubparagraph">\subparagraph</a></li>
<li><a class="doxyTocListItem" href="#cmdsubsection">\subsection</a></li>
<li><a class="doxyTocListItem" href="#cmdsubsubparagraph">\subsubparagraph</a></li>
<li><a class="doxyTocListItem" href="#cmdsubsubsection">\subsubsection</a></li>
<li><a class="doxyTocListItem" href="#cmdtableofcontents">\tableofcontents</a></li>
<li><a class="doxyTocListItem" href="#cmdtest">\test</a></li>
<li><a class="doxyTocListItem" href="#cmdthrow">\throw</a></li>
<li><a class="doxyTocListItem" href="#cmdthrows">\throws</a></li>
<li><a class="doxyTocListItem" href="#cmdtodo">\todo</a></li>
<li><a class="doxyTocListItem" href="#cmdtparam">\tparam</a></li>
<li><a class="doxyTocListItem" href="#cmdtypedef">\typedef</a></li>
<li><a class="doxyTocListItem" href="#cmdplantumlfile">\plantumlfile</a></li>
<li><a class="doxyTocListItem" href="#cmdunion">\union</a></li>
<li><a class="doxyTocListItem" href="#cmduntil">\until</a></li>
<li><a class="doxyTocListItem" href="#cmdvar">\var</a></li>
<li><a class="doxyTocListItem" href="#cmdverbatim">\verbatim</a></li>
<li><a class="doxyTocListItem" href="#cmdverbinclude">\verbinclude</a></li>
<li><a class="doxyTocListItem" href="#cmdversion">\version</a></li>
<li><a class="doxyTocListItem" href="#cmdvhdlflow">\vhdlflow</a></li>
<li><a class="doxyTocListItem" href="#cmdwarning">\warning</a></li>
<li><a class="doxyTocListItem" href="#cmdweakgroup">\weakgroup</a></li>
<li><a class="doxyTocListItem" href="#cmdxmlinclude">\xmlinclude</a></li>
<li><a class="doxyTocListItem" href="#cmdxmlonly">\xmlonly</a></li>
<li><a class="doxyTocListItem" href="#cmdxrefitem">\xrefitem</a></li>
<li><a class="doxyTocListItem" href="#cmddollar">\$</a></li>
<li><a class="doxyTocListItem" href="#cmdat">\@</a></li>
<li><a class="doxyTocListItem" href="#cmdbackslash">\\</a></li>
<li><a class="doxyTocListItem" href="#cmdamp">\&amp;</a></li>
<li><a class="doxyTocListItem" href="#cmdtilde">\~</a></li>
<li><a class="doxyTocListItem" href="#cmdlt">\&lt;</a></li>
<li><a class="doxyTocListItem" href="#cmdeq">\=</a></li>
<li><a class="doxyTocListItem" href="#cmdgt">\&gt;</a></li>
<li><a class="doxyTocListItem" href="#cmdhash">\#</a></li>
<li><a class="doxyTocListItem" href="#cmdperc">\%</a></li>
<li><a class="doxyTocListItem" href="#cmdquot">\"</a></li>
<li><a class="doxyTocListItem" href="#cmdchardot">\.</a></li>
<li><a class="doxyTocListItem" href="#cmdquest">\?</a></li>
<li><a class="doxyTocListItem" href="#cmdexclam">\!</a></li>
<li><a class="doxyTocListItem" href="#cmddcolon">\::</a></li>
<li><a class="doxyTocListItem" href="#cmdpipe">\|</a></li>
<li><a class="doxyTocListItem" href="#cmdndash">\--</a></li>
<li><a class="doxyTocListItem" href="#cmdmdash">\---</a></li>
</ul>

The following subsections provide a list of all commands that are recognized by Doxygen. Unrecognized commands are treated as normal text.
 <center>

##  ---  Structural indicators  ---  
 </center>

## \\addtogroup &lt;name&gt; \[(title)\] {#cmdaddtogroup}


Defines a group just like <a href="#cmddefgroup">\\defgroup</a>, but in contrast to that command using the same &lt;name&gt; more than once will not result in a warning, but rather one group with a merged documentation and the first title found in any of the commands.

The title is optional, so this command can also be used to add a number of entities to an existing group using <code>@{</code> and <code>@}</code> like this:


<pre><code>  /*! \addtogroup mygrp
   *  Additional documentation for group 'mygrp'
   *  @{
   */

  /*!
   *  A function
   */
  void func1()
  {
  }

  /*! Another function */
  void func2()
  {
  }

  /*! @} */
</code></pre>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
page <a href="/web-doxygen/docs/pages/grouping">Grouping</a>, sections <a href="#cmddefgroup">\defgroup</a>, <a href="#cmdingroup">\ingroup</a>, and <a href="#cmdweakgroup">\weakgroup</a>.
</dd>
</dl>


<hr/>


## \\callgraph {#cmdcallgraph}


When this command is put in a comment block of a function or method and <a href="/web-doxygen/docs/pages/config/#cfg_have_dot">HAVE\_DOT</a> is set to <code>YES</code>, then Doxygen will generate a call graph for that function (provided the implementation of the function or method calls other documented functions). The call graph will be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_call_graph">CALL\_GRAPH</a>.

:::info
The completeness (and correctness) of the call graph depends on the Doxygen code parser which is not perfect.
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdcallergraph">\callergraph</a>, section <a href="#cmdhidecallgraph">\hidecallgraph</a>, section <a href="#cmdhidecallergraph">\hidecallergraph</a> and option <a href="/web-doxygen/docs/pages/config/#cfg_call_graph">CALL_GRAPH</a>
</dd>
</dl>


<hr/>


## \\hidecallgraph {#cmdhidecallgraph}


When this command is put in a comment block of a function or method and then Doxygen will not generate a call graph for that function. The call graph will not be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_call_graph">CALL\_GRAPH</a>.

:::info
The completeness (and correctness) of the call graph depends on the Doxygen code parser which is not perfect.
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdcallergraph">\callergraph</a>, section <a href="#cmdcallgraph">\callgraph</a>, section <a href="#cmdhidecallergraph">\hidecallergraph</a> and option <a href="/web-doxygen/docs/pages/config/#cfg_call_graph">CALL_GRAPH</a>
</dd>
</dl>


<hr/>


## \\callergraph {#cmdcallergraph}


When this command is put in a comment block of a function or method and <a href="/web-doxygen/docs/pages/config/#cfg_have_dot">HAVE\_DOT</a> is set to <code>YES</code>, then Doxygen will generate a caller graph for that function (provided the implementation of the function or method is called by other documented functions). The caller graph will be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_caller_graph">CALLER\_GRAPH</a>.

:::info
The completeness (and correctness) of the caller graph depends on the Doxygen code parser which is not perfect.
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdcallgraph">\callgraph</a>, section <a href="#cmdhidecallgraph">\hidecallgraph</a>, section <a href="#cmdhidecallergraph">\hidecallergraph</a> and option <a href="/web-doxygen/docs/pages/config/#cfg_caller_graph">CALLER_GRAPH</a>
</dd>
</dl>


<hr/>


## \\hidecallergraph {#cmdhidecallergraph}


When this command is put in a comment block of a function or method and then Doxygen will not generate a caller graph for that function. The caller graph will not be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_caller_graph">CALLER\_GRAPH</a>.

:::info
The completeness (and correctness) of the caller graph depends on the Doxygen code parser which is not perfect.
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdcallergraph">\callergraph</a>, section <a href="#cmdcallgraph">\callgraph</a>, section <a href="#cmdhidecallgraph">\hidecallgraph</a> and option <a href="/web-doxygen/docs/pages/config/#cfg_caller_graph">CALLER_GRAPH</a>
</dd>
</dl>


<hr/>


## \\showrefby {#cmdshowrefby}


When this command is put in a comment block of a function, method or variable, then Doxygen will generate an overview for that function, method, variable of the, documented, functions and methods that call / use it. The overview will be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_referenced_by_relation">REFERENCED\_BY\_RELATION</a>.

:::info
The completeness (and correctness) of the overview depends on the Doxygen code parser which is not perfect.
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdshowrefs">\showrefs</a>, section <a href="#cmdhiderefby">\hiderefby</a>, section <a href="#cmdhiderefs">\hiderefs</a> and option <a href="/web-doxygen/docs/pages/config/#cfg_referenced_by_relation">REFERENCED_BY_RELATION</a>
</dd>
</dl>


<hr/>


## \\hiderefby {#cmdhiderefby}


When this command is put in a comment block of a function, method or variable then Doxygen will not generate an overview for that function, method or variable of the functions and methods that call / use it. The overview will not be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_referenced_by_relation">REFERENCED\_BY\_RELATION</a>.

:::info
The completeness (and correctness) of the overview depends on the Doxygen code parser which is not perfect.
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdshowrefs">\showrefs</a>, section <a href="#cmdshowrefby">\showrefby</a>, section <a href="#cmdhiderefs">\hiderefs</a> and option <a href="/web-doxygen/docs/pages/config/#cfg_referenced_by_relation">REFERENCED_BY_RELATION</a>
</dd>
</dl>


<hr/>


## \\showrefs {#cmdshowrefs}


When this command is put in a comment block of a function or method, then Doxygen will generate an overview for that function or method of the functions and methods that call it. The overview will be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_references_relation">REFERENCES\_RELATION</a>.

:::info
The completeness (and correctness) of the overview depends on the Doxygen code parser which is not perfect.
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdshowrefby">\showrefby</a>, section <a href="#cmdhiderefby">\hiderefby</a>, section <a href="#cmdhiderefs">\hiderefs</a> and option <a href="/web-doxygen/docs/pages/config/#cfg_references_relation">REFERENCES_RELATION</a>
</dd>
</dl>


<hr/>


## \\hiderefs {#cmdhiderefs}


When this command is put in a comment block of a function or method and then Doxygen will not generate an overview for that function or method of the functions and methods that call it. The overview will not be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_references_relation">REFERENCES\_RELATION</a>.

:::info
The completeness (and correctness) of the overview depends on the Doxygen code parser which is not perfect.
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdshowrefs">\showrefs</a>, section <a href="#cmdshowrefby">\showrefby</a>, section <a href="#cmdhiderefby">\hiderefby</a> and option <a href="/web-doxygen/docs/pages/config/#cfg_references_relation">REFERENCES_RELATION</a>
</dd>
</dl>


<hr/>


## \\showinlinesource {#cmdshowinlinesource}


When this command is put in a comment block of a function, multi-line macro, enum or a list initialized variable then Doxygen will generate the inline source for that member. The inline source will be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_inline_sources">INLINE\_SOURCES</a>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdhideinlinesource">\hideinlinesource</a>, option <a href="/web-doxygen/docs/pages/config/#cfg_inline_sources">INLINE_SOURCES</a>
</dd>
</dl>


<hr/>


## \\hideinlinesource {#cmdhideinlinesource}


When this command is put in a comment block of a function, multi-line macro, enum or a list initialized variable then Doxygen will not generate the inline source for that member. The inline source will not be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_inline_sources">INLINE\_SOURCES</a>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdshowinlinesource">\showinlinesource</a>, option <a href="/web-doxygen/docs/pages/config/#cfg_inline_sources">INLINE_SOURCES</a>
</dd>
</dl>


<hr/>


## \\includegraph {#cmdincludegraph}


When this command is put in a comment block of a file then Doxygen will generate an include graph for that file. The include graph will be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_include_graph">INCLUDE\_GRAPH</a>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdhideincludegraph">\hideincludegraph</a>, section <a href="#cmdincludedbygraph">\includedbygraph</a>, section <a href="#cmdhideincludedbygraph">\hideincludedbygraph</a> and option <a href="/web-doxygen/docs/pages/config/#cfg_include_graph">INCLUDE_GRAPH</a>
</dd>
</dl>


<hr/>


## \\hideincludegraph {#cmdhideincludegraph}


When this command is put in a comment block of a file then Doxygen will not generate an include graph for that file. The include graph will not be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_include_graph">INCLUDE\_GRAPH</a>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdincludegraph">\includegraph</a>, section <a href="#cmdincludedbygraph">\includedbygraph</a>, section <a href="#cmdhideincludedbygraph">\hideincludedbygraph</a> and option <a href="/web-doxygen/docs/pages/config/#cfg_include_graph">INCLUDE_GRAPH</a>
</dd>
</dl>


<hr/>


## \\includedbygraph {#cmdincludedbygraph}


When this command is put in a comment block of an include file then Doxygen will generate an included by graph for that include file. The included by graph will be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_included_by_graph">INCLUDED\_BY\_GRAPH</a>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdhideincludedbygraph">\hideincludedbygraph</a>, section <a href="#cmdincludegraph">\ncludegraph</a>, section <a href="#cmdhideincludegraph">\hideincludegraph</a> and option <a href="/web-doxygen/docs/pages/config/#cfg_included_by_graph">INCLUDED_BY_GRAPH</a>
</dd>
</dl>


<hr/>


## \\hideincludedbygraph {#cmdhideincludedbygraph}


When this command is put in a comment block of an include file then Doxygen will not generate an included by graph for that include file. The included by graph will not be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_included_by_graph">INCLUDED\_BY\_GRAPH</a>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdincludedbygraph">\includedbygraph</a>, section <a href="#cmdincludegraph">\ncludegraph</a>, section <a href="#cmdhideincludegraph">\hideincludegraph</a> and option <a href="/web-doxygen/docs/pages/config/#cfg_included_by_graph">INCLUDED_BY_GRAPH</a>
</dd>
</dl>


<hr/>


## \\directorygraph {#cmddirectorygraph}


When this command is put in a comment block of a directory (see section <a href="#cmddir">\\dir</a>) then Doxygen will generate a directory graph for that directory. The directory graph will be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_directory_graph">DIRECTORY\_GRAPH</a>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdhidedirectorygraph">\hidedirectorygraph</a>, option <a href="/web-doxygen/docs/pages/config/#cfg_directory_graph">DIRECTORY_GRAPH</a>
</dd>
</dl>


<hr/>


## \\hidedirectorygraph {#cmdhidedirectorygraph}


When this command is put in a comment block of a directory (see section <a href="#cmddir">\\dir</a>) then Doxygen will not generate a directory graph for that directory. The directory graph will not be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_directory_graph">DIRECTORY\_GRAPH</a>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmddirectorygraph">\directorygraph</a>, option <a href="/web-doxygen/docs/pages/config/#cfg_directory_graph">DIRECTORY_GRAPH</a>
</dd>
</dl>


<hr/>


## \\collaborationgraph {#cmdcollaborationgraph}


When this command is put in a comment block of a class then Doxygen will generate a collaboration graph for that class. The collaboration graph will be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_collaboration_graph">COLLABORATION\_GRAPH</a>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdhidecollaborationgraph">\hidecollaborationgraph</a>, option <a href="/web-doxygen/docs/pages/config/#cfg_collaboration_graph">COLLABORATION_GRAPH</a>
</dd>
</dl>


<hr/>


## \\hidecollaborationgraph {#cmdhidecollaborationgraph}


When this command is put in a comment block of a class then Doxygen will not generate a collaboration graph for that class. The collaboration graph will not be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_collaboration_graph">COLLABORATION\_GRAPH</a>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdcollaborationgraph">\collaborationgraph</a>, option <a href="/web-doxygen/docs/pages/config/#cfg_collaboration_graph">COLLABORATION_GRAPH</a>
</dd>
</dl>


<hr/>


## \\inheritancegraph\['{option}'\] {#cmdinheritancegraph}


When this command is put in a comment block of a class then Doxygen will generate an inheritance graph for that class conforming the <code>option</code>. The inheritance graph will be generated, conforming the <code>option</code>, regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_class_graph">CLASS\_GRAPH</a>. The possible values of <code>option</code> are the same values as can be used with <a href="/web-doxygen/docs/pages/config/#cfg_class_graph">CLASS\_GRAPH</a>. In case no <code>option</code> is specified the value <code>YES</code> is assumed.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdhideinheritancegraph">\hideinheritancegraph</a>, option <a href="/web-doxygen/docs/pages/config/#cfg_class_graph">CLASS_GRAPH</a>
</dd>
</dl>


<hr/>


## \\hideinheritancegraph {#cmdhideinheritancegraph}


When this command is put in a comment block of a class then Doxygen will not generate an inheritance graph for that class. The inheritance graph will not be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_class_graph">CLASS\_GRAPH</a>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdinheritancegraph">\inheritancegraph</a>, option <a href="/web-doxygen/docs/pages/config/#cfg_class_graph">CLASS_GRAPH</a>
</dd>
</dl>


<hr/>


## \\groupgraph {#cmdgroupgraph}


When this command is put in a comment block of a <a href="#cmddefgroup">\\defgroup</a> command then Doxygen will generate a group dependency graph for that group. The group graph will be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_group_graphs">GROUP\_GRAPHS</a>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdhidegroupgraph">\hidegroupgraph</a>, option <a href="/web-doxygen/docs/pages/config/#cfg_group_graphs">GROUP_GRAPHS</a>
</dd>
</dl>


<hr/>


## \\hidegroupgraph {#cmdhidegroupgraph}


When this command is put in a comment block of a <a href="#cmddefgroup">\\defgroup</a> command then Doxygen will not generate a group dependency graph for that group. The group graph will not be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_group_graphs">GROUP\_GRAPHS</a>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdgroupgraph">\groupgraph</a>, option <a href="/web-doxygen/docs/pages/config/#cfg_group_graphs">GROUP_GRAPHS</a>
</dd>
</dl>


<hr/>


## \\showenumvalues {#cmdshowenumvalues}


When this command is put in a comment block of an enum then doxygen will show the specified enum values for that enum, regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_show_enum_values">SHOW\_ENUM\_VALUES</a>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdhideenumvalues">\hideenumvalues</a>, option <a href="/web-doxygen/docs/pages/config/#cfg_show_enum_values">SHOW_ENUM_VALUES</a>
</dd>
</dl>


<hr/>


## \\hideenumvalues {#cmdhideenumvalues}


When this command is put in a comment block of an enum then doxygen will not show the specified enum values for that enum, regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_show_enum_values">SHOW\_ENUM\_VALUES</a>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdshowenumvalues">\showenumvalues</a>, option <a href="/web-doxygen/docs/pages/config/#cfg_show_enum_values">SHOW_ENUM_VALUES</a>
</dd>
</dl>


<hr/>


## \\qualifier &lt;label&gt; | "(text)" {#cmdqualifier}


With this command it is possible to add custom qualifier labels to members and classes. These labels will be shown in the output in the same way as the automatically generated labels such as "static", "inline", and "final".

For instance to indicate that a function is only meant for testing purposes one could add <code>\\qualifier test</code>

<hr/>


## \\category &lt;name&gt; \[&lt;header-file&gt;\] \[&lt;header-name&gt;\] {#cmdcategory}


For Objective-C only: Indicates that a comment block contains documentation for a class category with name &lt;name&gt;. The arguments are equal to the <a href="#cmdclass">\\class</a> command.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdclass">\class</a>.
</dd>
</dl>


<hr/>


## \\class &lt;name&gt; \[&lt;header-file&gt;\] \[&lt;header-name&gt;\] {#cmdclass}


Indicates that a comment block contains documentation for a class with name &lt;name&gt;. Optionally a header file and a header name can be specified. If the header-file is specified, a link to a verbatim copy of the header will be included in the HTML documentation. The &lt;header-name&gt; argument can be used to overwrite the name of the link that is used in the class documentation to something other than &lt;header-file&gt;. This can be useful if the include name is not located on the default include path (like &lt;X11/X.h&gt;). With the &lt;header-name&gt; argument you can also specify how the include statement should look like, by adding either quotes or sharp brackets around the name. Sharp brackets are used if just the name is given. Note that the last two arguments can also be specified using the <a href="#cmdheaderfile">\\headerfile</a> command.

<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/* A dummy class */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">Test</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! \class Test class.h "inc/class.h"</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \brief This is a test class.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * Some details about the Test class.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>

</div>

 
  Click <a href="pathname:///examples/class/html/class_test.html">here</a>
  for the corresponding HTML documentation that is generated by Doxygen.
</dd>
</dl>


<hr/>


## \\concept &lt;name&gt; {#cmdconcept}


Indicates that a comment block contains documentation for a C++20 concept with name &lt;name&gt;. See also the <a href="#cmdheaderfile">\\headerfile</a> command to specify the header a user should be included to use the concept.

<hr/>


## \\def &lt;name&gt; {#cmddef}


Indicates that a comment block contains documentation for a <code>#define</code> macro.

<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! \file define.h</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    \brief testing defines</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    This is to test the documentation of defines.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*!</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  \def MAX(x,y)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  Computes the maximum of \a x and \a y.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">   \brief Computes the absolute value of its argument \a x.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">   \param x input value.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">   \returns absolute value of \a x.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define ABS(x) (((x)&gt;0)?(x):-(x))</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define MAX(x,y) ((x)&gt;(y)?(x):(y))</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define MIN(x,y) ((x)&gt;(y)?(y):(x)) </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">        /*!&lt; Computes the minimum of \a x and \a y. */</span></span></div>

</div>

 
  Click <a href="pathname:///examples/define/html/define_8h.html">here</a>
  for the corresponding HTML documentation that is generated by Doxygen.
</dd>
</dl>


<hr/>


## \\defgroup &lt;name&gt; (group title) {#cmddefgroup}


Indicates that a comment block contains documentation for a <a href="/web-doxygen/docs/pages/grouping/#topics">topics</a> of classes, modules, concepts, files or namespaces. This can be used to categorize symbols, and document those categories. You can also use groups as members of other groups, thus building a hierarchy of groups.

The &lt;name&gt; argument should be a single-word identifier.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
page <a href="/web-doxygen/docs/pages/grouping">Grouping</a>, sections <a href="#cmdingroup">\ingroup</a>, <a href="#cmdaddtogroup">\addtogroup</a>, and <a href="#cmdweakgroup">\weakgroup</a>.
</dd>
</dl>


<hr/>


## \\dir \[&lt;path fragment&gt;\] {#cmddir}


Indicates that a comment block contains documentation for a directory. The "path fragment" argument should include the directory name and enough of the path to be unique with respect to the other directories in the project. The <a href="/web-doxygen/docs/pages/config/#cfg_strip_from_path">STRIP\_FROM\_PATH</a> option determines what is stripped from the full path before it appears in the output.

<hr/>


## \\enum &lt;name&gt; {#cmdenum}


Indicates that a comment block contains documentation for an enumeration, with name &lt;name&gt;. If the enum is a member of a class and the documentation block is located outside the class definition, the scope of the class should be specified as well. If a comment block is located directly in front of an enum declaration, the <code>\\enum</code> comment may be omitted.

<dl class="doxySectionUser">
<dt>Note:</dt>
<dd>
The type of an anonymous enum cannot be documented, but the values of an anonymous enum can.
</dd>
</dl>


<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">Enum_Test</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">public</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">enum</span><span class="doxyHighlight"> TEnum { Val1, Val2 };</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    /*! Another enum, with inline docs */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">enum</span><span class="doxyHighlight"> AnotherEnum </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      V1, </span><span class="doxyHighlightComment">/*!&lt; value 1 */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      V2  </span><span class="doxyHighlightComment">/*!&lt; value 2 */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    };</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! \class Enum_Test</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * The class description.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! \enum Enum_Test::TEnum</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * A description of the enum type.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! \var Enum_Test::TEnum Enum_Test::Val1</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * The description of the first enum value.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>

</div>

 
  Click <a href="pathname:///examples/enum/html/class_enum___test.html">here</a>
  for the corresponding HTML documentation that is generated by Doxygen.
</dd>
</dl>


<hr/>


## \\example\['{lineno}'\] &lt;file-name&gt; {#cmdexample}


Indicates that a comment block contains documentation for a source code example. The name of the source file is &lt;file-name&gt;. The contents of this file will be included in the documentation, just after the documentation contained in the comment block. You can add option <code>{lineno}</code> to enable line numbers for the example if desired. All examples are placed in a list. The source code is scanned for documented members and classes. If any are found, the names are cross-referenced with the documentation. Source files or directories can be specified using the <a href="/web-doxygen/docs/pages/config/#cfg_example_path">EXAMPLE\_PATH</a> tag of Doxygen's configuration file.

If &lt;file-name&gt; itself is not unique for the set of example files specified by the <a href="/web-doxygen/docs/pages/config/#cfg_example_path">EXAMPLE\_PATH</a> tag, you can include part of the absolute path to disambiguate it.

If more than one source file is needed for the example, the <a href="#cmdinclude">\\include</a> command can be used.

<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** A Example_Test class.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  More details about this class.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">Example_Test</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">public</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    /** An example member function.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">     *  More details about this function.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">     */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> example();</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> Example_Test::example() {}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** \example example_test.cpp</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * This is an example of how to use the Example_Test class.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * More details about this example.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>

</div>


Where the example file <code>example_test.cpp</code> looks as follows:

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> main()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  Example_Test t;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  t.example();</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

 
  Click <a href="pathname:///examples/example/html/examples.html">here</a>
  for the corresponding HTML documentation that is generated by Doxygen.
</dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdinclude">\include</a>.
</dd>
</dl>


<hr/>


## \\endinternal {#cmdendinternal}


This command ends a documentation fragment that was started with a <a href="#cmdinternal">\\internal</a> command. The text between <a href="#cmdinternal">\\internal</a> and <code>\\endinternal</code> will only be visible if <a href="/web-doxygen/docs/pages/config/#cfg_internal_docs">INTERNAL\_DOCS</a> is set to <code>YES</code>.

<hr/>


## \\extends &lt;name&gt; {#cmdextends}


This command can be used to manually indicate an inheritance relation, when the programming language does not support this concept natively (e.g. C).

The file <code>manual.c</code> in the example directory shows how to use this command (see also <a href="#cmdmemberof">\\memberof</a> for the complete file).
 
  Click <a href="pathname:///examples/manual/html/struct_car.html">here</a>
  for the corresponding HTML documentation that is generated by Doxygen.
  

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdimplements">\implements</a> and section <a href="#cmdmemberof">\memberof</a>
</dd>
</dl>


<hr/>


## \\file \[&lt;name&gt;\] {#cmdfile}


Indicates that a comment block contains documentation for a source or header file with name &lt;name&gt;. The file name may include (part of) the path if the file-name alone is not unique. If the file name is omitted (i.e. the line after <code>\\file</code> is left blank) then the documentation block that contains the <code>\\file</code> command will belong to the file it is located in.

:::tip
The documentation of global functions, variables, typedefs, and enums will only be included in the output if the file they are in is documented as well or if <a href="/web-doxygen/docs/pages/config/#cfg_extract_all">EXTRACT\_ALL</a> is set to <code>YES</code>.
:::


<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** \file file.h</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * A brief file description.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * A more elaborated file description.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/**</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * A global integer value.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * More details about this value.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">extern</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> globalValue;</span></span></div>

</div>

 
  Click <a href="pathname:///examples/file/html/file_8h.html">here</a>
  for the corresponding HTML documentation that is generated by Doxygen.
</dd>
</dl>


:::info
In the above example <a href="/web-doxygen/docs/pages/config/#cfg_javadoc_autobrief">JAVADOC\_AUTOBRIEF</a> has been set to <code>YES</code> in the configuration file.
:::


<hr/>


## \\fileinfo\['{'option'}'\] {#cmdfileinfo}


Shows (part) of the file name in which this command is placed. The <code>option</code> can be <code>name</code>, <code>extension</code>, <code>filename</code>, <code>directory</code> or, <code>full</code>, with

<ul class="doxyList ">
<li><code>name</code> the name of the file without extension</li>
<li><code>extension</code> the extension of the file</li>
<li><code>filename</code> the filename i.e. <code>name</code> plus <code>extension</code></li>
<li><code>directory</code> the directory of the given file</li>
<li><code>full</code> the full path and filename of the given file.</li>
</ul>

In case no option is specified the <code>filename</code> is used unless <a href="/web-doxygen/docs/pages/config/#cfg_full_path_names">FULL\_PATH\_NAMES</a> is set to <code>YES</code> in which case <code>full</code> is used.

:::info
the command \\fileinfo cannot be used as argument to the <a href="#cmdfile">\\file</a> command
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdlineinfo">\lineinfo</a>
</dd>
</dl>


<hr/>


## \\lineinfo {#cmdlineinfo}


Shows the line number inside the file at which this command is placed.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdfileinfo">\fileinfo</a>
</dd>
</dl>


<hr/>


## \\fn (function declaration) {#cmdfn}


Indicates that a comment block contains documentation for a function (either global or as a member of a class). This command is <em>only</em> needed if a comment block is <em>not</em> placed in front (or behind) the function declaration or definition.

If your comment block <em>is</em> in front of the function declaration or definition this command can (and to avoid redundancy should) be omitted.

A full function declaration including arguments should be specified after the <code>\\fn</code> command on a <em>single</em> line, since the argument ends at the end of the line!

This command is equivalent to <a href="#cmdvar">\\var</a>, <a href="#cmdtypedef">\\typedef</a>, and <a href="#cmdproperty">\\property</a>.

:::warning
Do not use this command if it is not absolutely needed, since it will lead to duplication of information and thus to errors.
:::


<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">Fn_Test</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">public</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *member(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">throw</span><span class="doxyHighlight">(std::out_of_range);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *Fn_Test::member(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> n) </span><span class="doxyHighlightKeywordFlow">throw</span><span class="doxyHighlight">(std::out_of_range) {}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! \class Fn_Test</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * \brief Fn_Test class.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * Details about Fn_Test.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! \fn const char *Fn_Test::member(char c,int n) </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \brief A member function.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \param c a character.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \param n an integer.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \exception std::out_of_range parameter is out of range.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \return a character pointer.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>

</div>

 
  Click <a href="pathname:///examples/func/html/class_fn___test.html">here</a>
  for the corresponding HTML documentation that is generated by Doxygen.
</dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
sections <a href="#cmdvar">\var</a>, <a href="#cmdproperty">\property</a>, and <a href="#cmdtypedef">\typedef</a>.
</dd>
</dl>


<hr/>


## \\headerfile &lt;header-file&gt; \[&lt;header-name&gt;\] {#cmdheaderfile}


Intended to be used for class, struct, or union documentation, where the documentation is in front of the definition. The arguments of this command are the same as the second and third argument of <a href="#cmdclass">\\class</a>. The &lt;header-file&gt; name refers to the file that should be included by the application to obtain the definition of the class, struct, or union. The &lt;header-name&gt; argument can be used to overwrite the name of the link that is used in the class documentation to something other than &lt;header-file&gt;. This can be useful if the include name is not located on the default include path (like &lt;X11/X.h&gt;).

With the &lt;header-name&gt; argument you can also specify how the include statement should look like, by adding either double quotes or sharp brackets around the name. By default sharp brackets are used if just the name is given.

If a pair of double quotes is given for either the &lt;header-file&gt; or &lt;header-name&gt; argument, the current file (in which the command was found) will be used but with quotes. So for a comment block with a <code>\\headerfile</code> command inside a file <code>test.h</code>, the following three commands are equivalent:


<pre><code>  \headerfile test.h "test.h"
  \headerfile test.h ""
  \headerfile ""
</code></pre>


To get sharp brackets you do not need to specify anything, but if you want to be explicit you could use any of the following:


<pre><code>  \headerfile test.h &lt;test.h&gt;
  \headerfile test.h &lt;&gt;
  \headerfile &lt;&gt;
</code></pre>


To globally reverse the default include representation to local includes you can set <a href="/web-doxygen/docs/pages/config/#cfg_force_local_includes">FORCE\_LOCAL\_INCLUDES</a> to <code>YES</code>.

To disable the include information altogether set <a href="/web-doxygen/docs/pages/config/#cfg_show_headerfile">SHOW\_HEADERFILE</a> to <code>NO</code>.

<hr/>


## \\hideinitializer {#cmdhideinitializer}


By default the value of a define and the initializer of a variable are displayed unless they are longer than 30 lines. By putting this command in a comment block of a define or variable, the initializer is always hidden. The maximum number of initialization lines can be changed by means of the configuration parameter <a href="/web-doxygen/docs/pages/config/#cfg_max_initializer_lines">MAX\_INITIALIZER\_LINES</a>, the default value is 30.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdshowinitializer">\showinitializer</a>.
</dd>
</dl>


<hr/>


## \\idlexcept &lt;name&gt; {#cmdidlexcept}


Indicates that a comment block contains documentation for a IDL exception with name &lt;name&gt;.

<hr/>


## \\implements &lt;name&gt; {#cmdimplements}


This command can be used to manually indicate an inheritance relation, when the programming language does not support this concept natively (e.g. C).

The file <code>manual.c</code> in the example directory shows how to use this command (see also <a href="#cmdmemberof">\\memberof</a> for the complete file).
 
  Click <a href="pathname:///examples/manual/html/struct_car.html">here</a>
  for the corresponding HTML documentation that is generated by Doxygen.
  

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdextends">\extends</a> and section <a href="#cmdmemberof">\memberof</a>
</dd>
</dl>


<hr/>


## \\ingroup (&lt;groupname&gt; \[&lt;groupname&gt;\]\*) {#cmdingroup}


If the <code>\\ingroup</code> command is placed in a comment block of a compound entity (like class, file or namespace), then it will be added to the group(s) identified by the <code>&lt;groupname&gt;</code>(s). In case of members (like variable, functions, typedefs and enums) the member will be added only to one group (to avoid ambiguous linking targets in case a member is not documented in the context of its class, namespace or file, but only visible as part of a group).

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
page <a href="/web-doxygen/docs/pages/grouping">Grouping</a>, sections <a href="#cmddefgroup">\defgroup</a>, <a href="#cmdaddtogroup">\addtogroup</a>, and <a href="#cmdweakgroup">\weakgroup</a>
</dd>
</dl>


<hr/>


## \\interface &lt;name&gt; \[&lt;header-file&gt;\] \[&lt;header-name&gt;\] {#cmdinterface}


Indicates that a comment block contains documentation for an interface with name &lt;name&gt;. The arguments are equal to the arguments of the <a href="#cmdclass">\\class</a> command.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdclass">\class</a>.
</dd>
</dl>


<hr/>


## \\internal {#cmdinternal}


This command starts a documentation fragment that is meant for internal use only. The fragment naturally ends at the end of the comment block. You can also force the internal section to end earlier by using the <a href="#cmdendinternal">\\endinternal</a> command.

If the <code>\\internal</code> command is put inside a section (see for example <a href="#cmdsection">\\section</a>) all subsections after the command are considered to be internal as well. Only a new section at the same level will end the fragment that is considered internal.

You can use <a href="/web-doxygen/docs/pages/config/#cfg_internal_docs">INTERNAL\_DOCS</a> in the configuration file to show (<code>YES</code>) or hide (<code>NO</code>) the internal documentation.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdendinternal">\endinternal</a>.
</dd>
</dl>


<hr/>


## \\mainpage \[(title)\] {#cmdmainpage}


If the <code>\\mainpage</code> command is placed in a comment block the block is used to customize the index page (in HTML) or the first chapter (in <code>{\LaTeX}</code>).

The title argument is optional and replaces the default title that Doxygen normally generates. If you do not want any title you can specify <code>notitle</code> as the argument of <code>\\mainpage</code>.

Here is an example:


<pre><code>/*! \mainpage My Personal Index Page
 *
 * \section intro_sec Introduction
 *
 * This is the introduction.
 *
 * \section install_sec Installation
 *
 * \subsection step1 Step 1: Opening the box
 *
 * etc...
 */
</code></pre>


You can refer to the main page using: <code><a href="#cmdref">\\ref</a> index</code>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdsection">\section</a>, section <a href="#cmdsubsection">\subsection</a>, and section <a href="#cmdpage">\page</a>.
</dd>
</dl>


<hr/>


## \\memberof &lt;name&gt; {#cmdmemberof}


This command makes a function a member of a class in a similar way as <a href="#cmdrelates">\\relates</a> does, only with this command the function is represented as a real member of the class. This can be useful when the programming language does not support the concept of member functions natively (e.g. C).

It is also possible to use this command together with <a href="#cmdpublic">\\public</a>, <a href="#cmdprotected">\\protected</a> or <a href="#cmdprivate">\\private</a>.

<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
The file <code>manual.c</code> in the example directory shows how to use this command:

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/**</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * \file manual.c</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">typedef</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">Object Object;   </span><span class="doxyHighlightComment">//!&lt; Object type</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">typedef</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">Vehicle Vehicle; </span><span class="doxyHighlightComment">//!&lt; Vehicle type</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">typedef</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">Car Car;         </span><span class="doxyHighlightComment">//!&lt; Car type</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">typedef</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">Truck Truck;     </span><span class="doxyHighlightComment">//!&lt; Truck type</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*!</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * Base object class.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">Object</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> ref;    </span><span class="doxyHighlightComment">//!&lt; \private Reference count.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*!</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * Increments object reference count by one.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * \public \memberof Object</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> Object * objRef(Object *obj);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*!</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * Decrements object reference count by one.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * \public \memberof Object</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> Object * objUnref(Object *obj);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*!</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * Vehicle class.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * \extends Object</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">Vehicle</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  Object base;    </span><span class="doxyHighlightComment">//!&lt; \protected Base class.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*!</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * Starts the vehicle.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * \public \memberof Vehicle</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> vehicleStart(Vehicle *obj);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*!</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * Stops the vehicle.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * \public \memberof Vehicle</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> vehicleStop(Vehicle *obj);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*!</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * Car class.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * \extends Vehicle</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">Car</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  Vehicle base;    </span><span class="doxyHighlightComment">//!&lt; \protected Base class.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*!</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * Truck class.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * \extends Vehicle</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">Truck</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  Vehicle base;    </span><span class="doxyHighlightComment">//!&lt; \protected Base class.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*!</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * Main function.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * Ref vehicleStart(), objRef(), objUnref().</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> main(</span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  Car c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  vehicleStart((Vehicle*) &amp;c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>

</div>

 
  Click <a href="pathname:///examples/manual/html/struct_car.html">here</a>
  for the corresponding HTML documentation that is generated by Doxygen.
</dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
sections <a href="#cmdextends">\extends</a>, <a href="#cmdimplements">\implements</a>, <a href="#cmdpublic">\public</a>, <a href="#cmdprotected">\protected</a> and <a href="#cmdprivate">\private</a>.
</dd>
</dl>


<hr/>


## \\module &lt;name&gt; {#cmdmodule}


Indicates that a comment block contains documentation for a C++20 module with name &lt;name&gt;.

<hr/>


## \\name \[(header)\] {#cmdname}


This command turns a comment block into a header definition of a member group. The comment block should be followed by a <code>@{</code> ... <code>@}</code> block containing the members of the group.

See section <a href="/web-doxygen/docs/pages/grouping/#memgroup">Member Groups</a> for an example.

<hr/>


## \\namespace &lt;name&gt; {#cmdnamespace}


Indicates that a comment block contains documentation for a namespace with name &lt;name&gt;.

<hr/>


## \\nosubgrouping {#cmdnosubgrouping}


This command can be put in the documentation of a class. It can be used in combination with member grouping to avoid that Doxygen puts a member group as a subgroup of a Public/Protected/Private/... section.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
sections <a href="#cmdpublicsection">\publicsection</a>, <a href="#cmdprotectedsection">\protectedsection</a> and <a href="#cmdprivatesection">\privatesection</a>.
</dd>
</dl>


<hr/>


## \\overload \[(function declaration)\] {#cmdoverload}


This command can be used to generate the following standard text for an overloaded member function:
<blockquote class="doxyBlockQuote">

This is an overloaded member function, provided for convenience. It differs from the above function only in what argument(s) it accepts.
</blockquote>

If the documentation for the overloaded member function is not located in front of the function declaration or definition, the optional argument should be used to specify the correct declaration of the overloaded function. Of course when the <code>\\overload</code> command is directly in front of the overloaded member function and the optional argument is used this should also be the correct declaration of the overloaded function.

Any other documentation that is inside the documentation block will by appended after the generated message.

<dl class="doxySectionUser">
<dt>Note 1:</dt>
<dd>
You are responsible that there is indeed an earlier documented member that is overloaded by this one. To prevent that document reorders the documentation you should set <a href="/web-doxygen/docs/pages/config/#cfg_sort_member_docs">SORT_MEMBER_DOCS</a> to <code>NO</code> in this case.
</dd>
</dl>


<dl class="doxySectionUser">
<dt>Note 2:</dt>
<dd>
Only one <code>\overload</code> command can be present in a comment block.
</dd>
</dl>


<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">Overload_Test </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">public</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> drawRect(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> drawRect(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> Rect &amp;r);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> Overload_Test::drawRect(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> x,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> y,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> w,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> h) {}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> Overload_Test::drawRect(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> Rect &amp;r) {}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! \class Overload_Test</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \brief A short description.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *   </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  More text.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! \fn void Overload_Test::drawRect(int x,int y,int w,int h)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * This command draws a rectangle with a left upper corner at ( \a x , \a y ),</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * width \a w and height \a h. </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*!</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * \overload void Overload_Test::drawRect(const Rect &amp;r)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>

</div>

 
  Click <a href="pathname:///examples/overload/html/class_overload___test.html">here</a>
  for the corresponding HTML documentation that is generated by Doxygen.
</dd>
</dl>


<hr/>


## \\package &lt;name&gt; {#cmdpackage}


Indicates that a comment block contains documentation for a Java package with name &lt;name&gt;.

<hr/>


## \\page &lt;name&gt; (title) {#cmdpage}


Indicates that a comment block contains a piece of documentation that is not directly related to one specific class, file or member. The HTML generator creates a page containing the documentation. The <code>{\LaTeX}</code> generator starts a new section in the chapter 'Page documentation'.

<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! \page page1 A documentation page</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  \tableofcontents</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  Leading text.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  \section sec An example section</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  This page contains the subsections \ref subsection1 and \ref subsection2.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  For more info see page \ref page2.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  \subsection subsection1 The first subsection</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  Text.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  \subsection subsection2 The second subsection</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  More text.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! \page page2 Another page</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  Even more info.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*/</span></span></div>

</div>

 
  Click <a href="pathname:///examples/page/html/page1.html">here</a>
  for the corresponding HTML documentation that is generated by Doxygen.
</dd>
</dl>


<dl class="doxySectionUser">
<dt>Note:</dt>
<dd>
The &lt;name&gt; argument consists of a combination of letters and number digits. If you wish to use upper case letters (e.g. <code>MYPAGE1</code>), or mixed case letters (e.g. <code>MyPage1</code>) in the &lt;name&gt; argument, you should set <a href="/web-doxygen/docs/pages/config/#cfg_case_sense_names">CASE_SENSE_NAMES</a> to <code>YES</code>. However, this is advisable only if your file system is case sensitive. Otherwise (and for better portability) you should use all lower case letters (e.g. <code>mypage1</code>) for &lt;name&gt; in all references to the page.
</dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdsection">\section</a>, section <a href="#cmdsubsection">\subsection</a>, and section <a href="#cmdref">\ref</a>.
</dd>
</dl>


<hr/>


## \\private {#cmdprivate}


Indicates that the member documented by the comment block is private, i.e., should only be accessed by other members in the same class.

Note that Doxygen automatically detects the protection level of members in object-oriented languages. This command is intended for use only when the language does not support the concept of protection level natively (e.g. C, PHP 4).

For starting a section of private members, in a way similar to the "private:" class marker in C++, use <a href="#cmdprivatesection">\\privatesection</a>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
sections <a href="#cmdmemberof">\memberof</a>, <a href="#cmdpublic">\public</a>, <a href="#cmdprotected">\protected</a> and <a href="#cmdprivatesection">\privatesection</a>.
</dd>
</dl>


<hr/>


## \\privatesection {#cmdprivatesection}


Starting a section of private members, in a way similar to the "private:" class marker in C++. Indicates that the member documented by the comment block is private, i.e., should only be accessed by other members in the same class.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
sections <a href="#cmdmemberof">\memberof</a>, <a href="#cmdpublic">\public</a>, <a href="#cmdprotected">\protected</a> and <a href="#cmdprivate">\private</a>.
</dd>
</dl>


<hr/>


## \\property (qualified property name) {#cmdproperty}


Indicates that a comment block contains documentation for a property (either global or as a member of a class). This command is equivalent to <a href="#cmdfn">\\fn</a>, <a href="#cmdtypedef">\\typedef</a>, and <a href="#cmdvar">\\var</a>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
sections <a href="#cmdfn">\fn</a>, <a href="#cmdtypedef">\typedef</a>, and <a href="#cmdvar">\var</a>.
</dd>
</dl>


<hr/>


## \\protected {#cmdprotected}


Indicates that the member documented by the comment block is protected, i.e., should only be accessed by other members in the same or derived classes.

Note that Doxygen automatically detects the protection level of members in object-oriented languages. This command is intended for use only when the language does not support the concept of protection level natively (e.g. C, PHP 4).

For starting a section of protected members, in a way similar to the "protected:" class marker in C++, use <a href="#cmdprotectedsection">\\protectedsection</a>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
sections <a href="#cmdmemberof">\memberof</a>, <a href="#cmdpublic">\public</a>, <a href="#cmdprivate">\private</a> and <a href="#cmdprotectedsection">\protectedsection</a>.
</dd>
</dl>


<hr/>


## \\protectedsection {#cmdprotectedsection}


Starting a section of protected members, in a way similar to the "protected:" class marker in C++. Indicates that the member documented by the comment block is protected, i.e., should only be accessed by other members in the same or derived classes.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
sections <a href="#cmdmemberof">\memberof</a>, <a href="#cmdpublic">\public</a>, <a href="#cmdprivate">\private</a> and <a href="#cmdprotected">\protected</a>.
</dd>
</dl>


<hr/>


## \\protocol &lt;name&gt; \[&lt;header-file&gt;\] \[&lt;header-name&gt;\] {#cmdprotocol}


Indicates that a comment block contains documentation for a protocol in Objective-C with name &lt;name&gt;. The arguments are equal to the <a href="#cmdclass">\\class</a> command.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdclass">\class</a>.
</dd>
</dl>


<hr/>


## \\public {#cmdpublic}


Indicates that the member documented by the comment block is public, i.e., can be accessed by any other class or function.

Note that Doxygen automatically detects the protection level of members in object-oriented languages. This command is intended for use only when the language does not support the concept of protection level natively (e.g. C, PHP 4).

For starting a section of public members, in a way similar to the "public:" class marker in C++, use <a href="#cmdpublicsection">\\publicsection</a>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
sections <a href="#cmdmemberof">\memberof</a>, <a href="#cmdprotected">\protected</a>, <a href="#cmdprivate">\private</a> and <a href="#cmdpublicsection">\publicsection</a>.
</dd>
</dl>


<hr/>


## \\publicsection {#cmdpublicsection}


Starting a section of public members, in a way similar to the "public:" class marker in C++. Indicates that the member documented by the comment block is public, i.e., can be accessed by any other class or function.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
sections <a href="#cmdmemberof">\memberof</a>, <a href="#cmdprotected">\protected</a>, <a href="#cmdprivate">\private</a> and <a href="#cmdpublic">\public</a>.
</dd>
</dl>


<hr/>


## \\pure {#cmdpure}


Indicates that the member documented by the comment block is pure virtual, i.e., it is abstract and has no implementation associated with it.

This command is intended for use only when the language does not support the concept of pure virtual methods natively (e.g. C, PHP 4).

<hr/>


## \\relates &lt;name&gt; {#cmdrelates}


This command can be used in the documentation of a non-member function &lt;name&gt;. It puts the function inside the 'related function' section of the class documentation. This command is useful for documenting non-friend functions that are nevertheless strongly coupled to a certain class. It prevents the need of having to document a file, but only works for functions.

<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * A String class.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span><span class="doxyHighlight"> </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">String</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">friend</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> strcmp(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> String &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> String &amp;);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * Compares two strings.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> strcmp(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> String &amp;s1,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> String &amp;s2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! \relates String</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * A string debug function.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> stringDebug()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

 
  Click <a href="pathname:///examples/relates/html/class_string.html">here</a>
  for the corresponding HTML documentation that is generated by Doxygen.
</dd>
</dl>


<hr/>


## \\related &lt;name&gt; {#cmdrelated}


Equivalent to <a href="#cmdrelates">\\relates</a>

<hr/>


## \\relatesalso &lt;name&gt; {#cmdrelatesalso}


This command can be used in the documentation of a non-member function &lt;name&gt;. It puts the function both inside the 'related function' section of the class documentation as well as leaving it at its normal file documentation location. This command is useful for documenting non-friend functions that are nevertheless strongly coupled to a certain class. It only works for functions.

<hr/>


## \\relatedalso &lt;name&gt; {#cmdrelatedalso}


Equivalent to <a href="#cmdrelatesalso">\\relatesalso</a>

<hr/>


## \\showinitializer {#cmdshowinitializer}


By default the value of a define and the initializer of a variable are only displayed if they are less than 30 lines long. By putting this command in a comment block of a define or variable, the initializer is shown unconditionally. The maximum number of initialization lines can be changed by means of the configuration parameter <a href="/web-doxygen/docs/pages/config/#cfg_max_initializer_lines">MAX\_INITIALIZER\_LINES</a>, the default value is 30.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdhideinitializer">\hideinitializer</a>.
</dd>
</dl>


<hr/>


## \\static {#cmdstatic}


Indicates that the member documented by the comment block is static, i.e., it works on a class, instead of on an instance of the class.

This command is intended for use only when the language does not support the concept of static methods natively (e.g. C).

<hr/>


## \\struct &lt;name&gt; \[&lt;header-file&gt;\] \[&lt;header-name&gt;\] {#cmdstruct}


Indicates that a comment block contains documentation for a struct with name &lt;name&gt;. The arguments are equal to the arguments of the <a href="#cmdclass">\\class</a> command.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdclass">\class</a>.
</dd>
</dl>


<hr/>


## \\typedef (typedef declaration) {#cmdtypedef}


Indicates that a comment block contains documentation for a typedef (either global or as a member of a class). This command is equivalent to <a href="#cmdfn">\\fn</a>, <a href="#cmdproperty">\\property</a>, and <a href="#cmdvar">\\var</a>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdfn">\fn</a>, <a href="#cmdproperty">\property</a>, and <a href="#cmdvar">\var</a>.
</dd>
</dl>


<hr/>


## \\union &lt;name&gt; \[&lt;header-file&gt;\] \[&lt;header-name&gt;\] {#cmdunion}


Indicates that a comment block contains documentation for a union with name &lt;name&gt;. The arguments are equal to the arguments of the <a href="#cmdclass">\\class</a> command.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdclass">\class</a>.
</dd>
</dl>


<hr/>


## \\var (variable declaration) {#cmdvar}


Indicates that a comment block contains documentation for a variable or enum value (either global or as a member of a class). This command is equivalent to <a href="#cmdfn">\\fn</a>, <a href="#cmdproperty">\\property</a>, and <a href="#cmdtypedef">\\typedef</a>.

Note that for PHP one can also specify the type of the variable. The syntax is similar as for the <code>phpDocumentor</code> but the description has to start at the next line, i.e.


<pre><code>@var  datatype $varname
Description
</code></pre>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdfn">\fn</a>, <a href="#cmdproperty">\property</a>, and <a href="#cmdtypedef">\typedef</a>.
</dd>
</dl>


<hr/>


## \\vhdlflow \[(title for the flow chart)\] {#cmdvhdlflow}


This is a VHDL specific command, which can be put in the documentation of a process to produce a flow chart of the logic in the process. Optionally a title for the flow chart can be given.

:::info
Currently the flow chart will only appear in the HTML output.
:::


<hr/>


## \\weakgroup &lt;name&gt; \[(title)\] {#cmdweakgroup}


Can be used exactly like <a href="#cmdaddtogroup">\\addtogroup</a>, but has a lower priority when it comes to resolving conflicting grouping definitions.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
page <a href="/web-doxygen/docs/pages/grouping">Grouping</a> and section <a href="#cmdaddtogroup">\addtogroup</a>.
</dd>
</dl>


<hr/>

 <center>

##  ---  Section indicators  ---  
 </center>

<hr/>


## \\attention { attention text } {#cmdattention}


Starts a paragraph where a message that needs attention may be entered. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <code>\\attention</code> commands will be joined into a single paragraph. The <code>\\attention</code> command ends when a blank line or some other sectioning command is encountered.

<hr/>


## \\author { list of authors } {#cmdauthor}


Starts a paragraph where one or more author names may be entered. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <code>\\author</code> commands will be joined into a single paragraph. Each author description will start a new line. Alternatively, one <code>\\author</code> command may mention several authors. The <code>\\author</code> command ends when a blank line or some other sectioning command is encountered.

<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \brief     Pretty nice class.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \details   This class is used to demonstrate a number of section commands.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \author    John Doe</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \author    Jan Doe</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \version   4.1a</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \date      1990-2011</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \pre       First initialize the system.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \bug       Not all memory is freed when deleting an object of this class.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \warning   Improper use can crash your application</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \copyright GNU Public License.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">SomeNiceClass {};</span></span></div>

</div>

 
  Click <a href="pathname:///examples/author/html/class_some_nice_class.html">here</a>
  for the corresponding HTML documentation that is generated by Doxygen.
</dd>
</dl>


<hr/>


## \\authors { list of authors } {#cmdauthors}


Equivalent to <a href="#cmdauthor">\\author</a>.

<hr/>


## \\brief { brief description } {#cmdbrief}


Starts a paragraph that serves as a brief description. For classes and files the brief description will be used in lists and at the start of the documentation page. For class and file members, the brief description will be placed at the declaration of the member and prepended to the detailed description. A brief description may span several lines (although it is advised to keep it brief!). A brief description ends when a blank line or another sectioning command is encountered. If multiple <code>\\brief</code> commands are present they will be joined. See section <a href="#cmdauthor">\\author</a> for an example.

Synonymous to <a href="#cmdshort">\\short</a>.

<hr/>


## \\bug { bug description } {#cmdbug}


Starts a paragraph where one or more bugs may be reported. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <code>\\bug</code> commands will be joined into a single paragraph. Each bug description will start on a new line. Alternatively, one <code>\\bug</code> command may mention several bugs. The <code>\\bug</code> command ends when a blank line or some other sectioning command is encountered. See section <a href="#cmdauthor">\\author</a> for an example.

The description will also add an item to a separate Bug list and the two instances of the description will be cross-referenced. Each item in the Bug list will be preceded by a header that indicates the origin of the item.

The Bug list and the corresponding entries can be disabled by setting the <a href="/web-doxygen/docs/pages/config/#cfg_generate_buglist">GENERATE\_BUGLIST</a> to <code>NO</code>.

<hr/>


## \\cond \[(section-label)\] {#cmdcond}


Starts a conditional section that ends with a corresponding <a href="#cmdendcond">\\endcond</a> command, which is typically found in another comment block. The main purpose of this pair of commands is to (conditionally) exclude part of a file from processing (in older version of Doxygen this could only be achieved using C preprocessor commands).

The section between <code>\\cond</code> and <a href="#cmdendcond">\\endcond</a> can be included by adding its section label to the <a href="/web-doxygen/docs/pages/config/#cfg_enabled_sections">ENABLED\_SECTIONS</a> configuration option. If the section label is omitted, the section will be excluded from processing unconditionally. The section label can be a logical expression build of section labels, round brackets, &amp;&amp; (AND), || (OR) and ! (NOT). If you use an expression you need to wrap it in round brackets, i.e <code>\\cond (!LABEL1 &amp;&amp; LABEL2)</code>.

For conditional sections within a comment block one should use a <a href="#cmdif">\\if</a> ... <a href="#cmdendif">\\endif</a> block. When using <code>\\cond</code> and the condition is not satisfied the current comment block is ended and everything until the matching <a href="#cmdendcond">\\endcond</a> is removed and a new command block is started there.

Conditional sections can be nested. In this case a nested section will only be shown if it and its containing section are included.

Here is an example showing the commands in action:


<pre><code>/** An interface */
class Intf
{
  public:
    /** A method */
    virtual void func() = 0;

    /// @cond TEST

    /** A method used for testing */
    virtual void test() = 0;

    /// @endcond
};

/// @cond DEV
/*
 *  The implementation of the interface
 */
class Implementation : public Intf
{
  public:
    void func();

    /// @cond TEST
    void test();
    /// @endcond

    /// @cond
    /** This method is obsolete and does
     *  not show up in the documentation.
     */
    void obsolete();
    /// @endcond
};

/// @endcond
</code></pre>


The output will be different depending on whether or not <a href="/web-doxygen/docs/pages/config/#cfg_enabled_sections">ENABLED\_SECTIONS</a> contains <code>TEST</code>, or <code>DEV</code>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
sections <a href="#cmdif">\if</a>, <a href="#cmdifnot">\ifnot</a>, <a href="#cmdelse">\else</a>, <a href="#cmdelseif">\elseif</a>, <a href="#cmdendif">\endif</a>, <a href="#cmdendcond">\endcond</a>, and <a href="/web-doxygen/docs/pages/config/#cfg_enabled_sections">ENABLED_SECTIONS</a>.
</dd>
</dl>


:::info
Due to the moment of parsing the <code>\\cond</code> and <a href="#cmdendcond">\\endcond</a> commands cannot be used in <a href="/web-doxygen/docs/pages/config/#cfg_aliases">ALIASES</a>.
:::


<hr/>


## \\copyright { copyright description } {#cmdcopyright}


Starts a paragraph where the copyright of an entity can be described. This paragraph will be indented. The text of the paragraph has no special internal structure. See section <a href="#cmdauthor">\\author</a> for an example.

<hr/>


## \\date { date description } {#cmddate}


Starts a paragraph where one or more dates may be entered. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <code>\\date</code> commands will be joined into a single paragraph. Each date description will start on a new line. Alternatively, one <code>\\date</code> command may mention several dates. The <code>\\date</code> command ends when a blank line or some other sectioning command is encountered. See section <a href="#cmdauthor">\\author</a> for an example.

<hr/>


## \\showdate "&lt;format&gt;" \[ &lt;date\_time&gt; \] {#cmdshowdate}


Shows the date and time based on the given &lt;format&gt; and &lt;date\_time&gt;. Where the &lt;format&gt; is a string in which the following tokens have a special meaning:

<table class="doxyTable">
<tr>
<th align="left">Code</th>
<th align="left">Description</th>
</tr>
<tr>
<td align="left">%y</td>
<td align="left">Year without century as a zero-padded decimal number.</td>
</tr>
<tr>
<td align="left">%Y</td>
<td align="left">Year with century as a decimal number.</td>
</tr>
<tr>
<td align="left">%m</td>
<td align="left">Month as a zero-padded decimal number.</td>
</tr>
<tr>
<td align="left">%-m</td>
<td align="left">The month as a decimal number.</td>
</tr>
<tr>
<td align="left">%b</td>
<td align="left">Month as locale’s abbreviated name.</td>
</tr>
<tr>
<td align="left">%B</td>
<td align="left">Month as locale’s full name.</td>
</tr>
<tr>
<td align="left">%d</td>
<td align="left">Day of the month as a zero-padded decimal number.</td>
</tr>
<tr>
<td align="left">%-d</td>
<td align="left">Day of the month as a decimal number.</td>
</tr>
<tr>
<td align="left">%u</td>
<td align="left">The weekday as a decimal number (1-7), where Monday is 1.</td>
</tr>
<tr>
<td align="left">%w</td>
<td align="left">The weekday as a decimal number (0-6), where Sunday is 0.</td>
</tr>
<tr>
<td align="left">%a</td>
<td align="left">Weekday as locale’s abbreviated name.</td>
</tr>
<tr>
<td align="left">%A</td>
<td align="left">Weekday as locale’s full name.</td>
</tr>
<tr>
<td align="left">&nbsp;</td>
<td align="left">&nbsp;</td>
</tr>
<tr>
<td align="left">%H</td>
<td align="left">Hour (24-hour clock) as a zero-padded decimal number.</td>
</tr>
<tr>
<td align="left">%-H</td>
<td align="left">Hour (24-hour clock) as a decimal number.</td>
</tr>
<tr>
<td align="left">%I</td>
<td align="left">Hour (12-hour clock) as a zero-padded decimal number.</td>
</tr>
<tr>
<td align="left">%-I</td>
<td align="left">Hour (12-hour clock) as a decimal number.</td>
</tr>
<tr>
<td align="left">%M</td>
<td align="left">Minute as a zero-padded decimal number.</td>
</tr>
<tr>
<td align="left">%-M</td>
<td align="left">Minute as a decimal number.</td>
</tr>
<tr>
<td align="left">%S</td>
<td align="left">Second as a zero-padded decimal number.</td>
</tr>
<tr>
<td align="left">%-S</td>
<td align="left">Second as a decimal number.</td>
</tr>
<tr>
<td align="left">%p</td>
<td align="left">Locale’s equivalent of either AM or PM.</td>
</tr>
<tr>
<td align="left">&nbsp;</td>
<td align="left">&nbsp;</td>
</tr>
<tr>
<td align="left">%%</td>
<td align="left">A % character.</td>
</tr>
</table>

Note that the &lt;format&gt; has to be between double quotes.

In case the &lt;date\_time&gt; is specified it has to have the following representation:

<ul class="doxyList ">
<li>optional <code>date</code> where <code>date</code> is:

<ul class="doxyList ">
<li>4 digits for the year</li>
<li>a minus sign</li>
<li>one or 2 digits for the month</li>
<li>a minus sign</li>
<li>one or 2 digits for the day</li>
</ul></li>
<li>optional <code>time</code> where <code>time</code> is:

<ul class="doxyList ">
<li>whitespace</li>
<li>one or 2 digits for the hours</li>
<li>a colon sign</li>
<li>one or 2 digits for the minutes</li>
<li>when the format contains %S or %-S

<ul class="doxyList ">
<li>a colon sign</li>
<li>2 digits for the seconds</li>
</ul></li>
</ul></li>
</ul>

in case the &lt;date\_time&gt; is not specified the current date and time are used.

Here is an example:

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">- \showdate </span><span class="doxyHighlightStringLiteral">"%A %d-%m-%Y"</span><span class="doxyHighlight"> 2015-3-14</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">- \showdate </span><span class="doxyHighlightStringLiteral">"%a %d-%m-%y"</span><span class="doxyHighlight"> 2015-3-14</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">- \showdate </span><span class="doxyHighlightStringLiteral">"%-m.%d%y"</span><span class="doxyHighlight"> 2015-3-14</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">- \showdate </span><span class="doxyHighlightStringLiteral">"%A %d-%m-%Y %H:%M:%S"</span><span class="doxyHighlight"> 2015-3-14 03:04:15</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">- \showdate </span><span class="doxyHighlightStringLiteral">"%A %d-%m-%Y %H:%M"</span><span class="doxyHighlight"> 2015-3-14 03:04</span></span></div>

</div>


In case <code>OUTPUT\_LANGUAGE=english</code> this results in:

<ul class="doxyList ">
<li>Saturday 14-03-2015</li>
<li>Sat 14-03-15</li>
<li>3.1415</li>
<li>Saturday 14-03-15 03:04:15</li>
<li>Saturday 14-03-15 03:04</li>
</ul>

In case <code>OUTPUT\_LANGUAGE=dutch</code> this results in:

<ul class="doxyList ">
<li>zaterdag 14-03-15</li>
<li>za 14-03-2015</li>
<li>3.1415</li>
<li>zaterdag 14-03-15 03:04:15</li>
<li>zaterdag 14-03-15 03:04</li>
</ul>

<hr/>


## \\deprecated { description } {#cmddeprecated}


Starts a paragraph indicating that this documentation block belongs to a deprecated entity. Can be used to describe alternatives, expected life span, etc. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <code>\\deprecated</code> commands will be joined into a single paragraph. Each deprecation description will start on a new line. The <code>\\deprecated</code> command ends when a blank line or some other sectioning command is encountered.

The description will also add an item to a separate Deprecated list and the two instances of the description will be cross-referenced. Each item in the Deprecated list will be preceded by a header that indicates the origin of the item.

The Deprecated list and the corresponding entries can be disabled by setting the <a href="/web-doxygen/docs/pages/config/#cfg_generate_deprecatedlist">GENERATE\_DEPRECATEDLIST</a> to <code>NO</code>.

<hr/>


## \\details { detailed description } {#cmddetails}


Just like <a href="#cmdbrief">\\brief</a> starts a brief description, <code>\\details</code> starts the detailed description. You can also start a new paragraph (blank line) then the <code>\\details</code> command is not needed.

<hr/>


## \\noop ( text to be ignored ) {#cmdnoop}


All the text, including the command, till the end of the line is ignored. The command will most commonly be used in combination with <a href="/web-doxygen/docs/pages/config/#cfg_aliases">ALIASES</a> to ignore not supported commands that are present for e.g. other processing tools.

<hr/>


## \\raisewarning ( text to be shown as warning ) {#cmdraisewarning}


All the text, excluding the command, till the end of the line is literally shown as a documentation warning. The text, including the command, is removed from the output. The command will most commonly be used in combination with <a href="/web-doxygen/docs/pages/config/#cfg_aliases">ALIASES</a> to show a specific warning.

<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<pre><code>\raisewarning My specific warning

\warnNoDoc

\warnNoDoc{My specific warning}
</code></pre>


together with:


<pre><code>ALIASES  = warnNoDoc="\raisewarning Missing documentation"
ALIASES += warnNoDoc{1}="\raisewarning Incomplete documentation: \1"
</code></pre>


will result in:


<pre><code>   ex_1.md:1: warning: My specific warning
   ex_1.md:3: warning: Missing documentation
   ex_1.md:5: warning: Incomplete documentation: My specific warning
</code></pre>
</dd>
</dl>


<hr/>


## \\else {#cmdelse}


Starts a conditional section if the previous conditional section was not enabled. The previous section should have been started with a <a href="#cmdif">\\if</a>, <a href="#cmdifnot">\\ifnot</a>, or <a href="#cmdelseif">\\elseif</a> command.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
sections <a href="#cmdif">\if</a>, <a href="#cmdifnot">\ifnot</a>, <a href="#cmdelseif">\elseif</a>, <a href="#cmdendif">\endif.</a>
</dd>
</dl>


<hr/>


## \\elseif (section-label) {#cmdelseif}


Starts a conditional documentation section if the previous section was not enabled. A conditional section is disabled by default. To enable it you must put the section-label after the <a href="/web-doxygen/docs/pages/config/#cfg_enabled_sections">ENABLED\_SECTIONS</a> tag in the configuration file. The section label can be a logical expression build of section names, round brackets, &amp;&amp; (AND), || (OR) and ! (NOT). Conditional blocks can be nested. A nested section is only enabled if all enclosing sections are enabled as well.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
sections <a href="#cmdif">\if</a>, <a href="#cmdifnot">\ifnot</a>, <a href="#cmdelse">\else</a>, <a href="#cmdendif">\endif.</a>
</dd>
</dl>


<hr/>


## \\endcond {#cmdendcond}


Ends a conditional section that was started by <a href="#cmdcond">\\cond</a>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdcond">\cond</a>.
</dd>
</dl>


:::info
Due to the moment of parsing the <code>\\endcond</code> and <a href="#cmdcond">\\cond</a> commands cannot be used in <a href="/web-doxygen/docs/pages/config/#cfg_aliases">ALIASES</a>.
:::


<hr/>


## \\endif {#cmdendif}


Ends a conditional section that was started by <a href="#cmdif">\\if</a> or <a href="#cmdifnot">\\ifnot</a> For each <a href="#cmdif">\\if</a> or <a href="#cmdifnot">\\ifnot</a> one and only one matching <a href="#cmdendif">\\endif</a> must follow.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
sections <a href="#cmdif">\if</a>, <a href="#cmdifnot">\ifnot</a>, <a href="#cmdelse">\else</a>, <a href="#cmdelseif">\elseif.</a>
</dd>
</dl>


<hr/>


## \\exception &lt;exception-object&gt; { exception description } {#cmdexception}


Starts an exception description for an exception object with name &lt;exception-object&gt;. Followed by a description of the exception. The existence of the exception object is not checked. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <code>\\exception</code> commands will be joined into a single paragraph. Each exception description will start on a new line. The <code>\\exception</code> description ends when a blank line or some other sectioning command is encountered. See section <a href="#cmdfn">\\fn</a> for an example.

<hr/>


## \\if (section-label) {#cmdif}


Starts a conditional documentation section. The section ends with a matching <a href="#cmdendif">\\endif</a> command. A conditional section is disabled by default. To enable it you must put the section-label after the <a href="/web-doxygen/docs/pages/config/#cfg_enabled_sections">ENABLED\_SECTIONS</a> tag in the configuration file.

The section label can be a logical expression build of section names, round brackets, &amp;&amp; (AND), || (OR) and ! (NOT). If you use an expression you need to wrap it in round brackets, i.e <code>\\if (!LABEL1 &amp;&amp; LABEL2)</code>.

Conditional blocks can be nested. A nested section is only enabled if all enclosing sections are enabled as well.

The <code>\\if</code> and corresponding <a href="#cmdendif">\\endif</a> have to be in the same comment block. When a conditional block needs to span more than one comment block one has to use <a href="#cmdcond">\\cond</a> ... <a href="#cmdendcond">\\endcond</a>.

<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<pre><code>  /*! Unconditionally shown documentation.
   *  \if Cond1
   *    Only included if Cond1 is set.
   *  \endif
   *  \if Cond2
   *    Only included if Cond2 is set.
   *    \if Cond3
   *      Only included if Cond2 and Cond3 are set.
   *    \endif
   *    More text.
   *  \endif
   *  Unconditional text.
   */
</code></pre>
</dd>
</dl>


You can also use conditional commands inside aliases. To document a class in two languages you could for instance use:

<dl class="doxySectionUser">
<dt>Example 2:</dt>
<dd>
<pre><code>/*! \english
 *  This is English.
 *  \endenglish
 *  \dutch
 *  Dit is Nederlands.
 *  \enddutch
 */
class Example
{
};
</code></pre>
</dd>
</dl>


Where the following aliases are defined in the configuration file:


<pre><code>ALIASES  = "english=\if english" \
           "endenglish=\endif" \
           "dutch=\if dutch" \
           "enddutch=\endif"
</code></pre>


and <a href="/web-doxygen/docs/pages/config/#cfg_enabled_sections">ENABLED\_SECTIONS</a> can be used to enable either <code>english</code> or <code>dutch</code>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
sections <a href="#cmdendif">\endif</a>, <a href="#cmdifnot">\ifnot</a>, <a href="#cmdelse">\else</a>, <a href="#cmdelseif">\elseif</a>, <a href="#cmdcond">\cond</a>, <a href="#cmdendcond">\endcond</a>, and <a href="/web-doxygen/docs/pages/config/#cfg_enabled_sections">ENABLED_SECTIONS</a>.
</dd>
</dl>


<hr/>


## \\ifnot (section-label) {#cmdifnot}


Starts a conditional documentation section. The section ends with a matching <a href="#cmdendif">\\endif</a> command. This conditional section is enabled by default. To disable it you must put the section-label after the <a href="/web-doxygen/docs/pages/config/#cfg_enabled_sections">ENABLED\_SECTIONS</a> tag in the configuration file. The section label can be a logical expression build of section names, round brackets, &amp;&amp; (AND), || (OR) and ! (NOT).

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
sections <a href="#cmdendif">\endif</a>, <a href="#cmdif">\if</a>, <a href="#cmdelse">\else</a>, and <a href="#cmdelseif">\elseif</a>, <a href="#cmdcond">\cond</a>, <a href="#cmdendcond">\endcond</a>, and <a href="/web-doxygen/docs/pages/config/#cfg_enabled_sections">ENABLED_SECTIONS</a>.
</dd>
</dl>


<hr/>


## \\important { important text } {#cmdimportant}


Starts a paragraph where a message that needs important may be entered. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <code>\\important</code> commands will be joined into a single paragraph. The <code>\\important</code> command ends when a blank line or some other sectioning command is encountered.

<hr/>


## \\invariant { description of invariant } {#cmdinvariant}


Starts a paragraph where the invariant of an entity can be described. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <code>\\invariant</code> commands will be joined into a single paragraph. Each invariant description will start on a new line. Alternatively, one <code>\\invariant</code> command may mention several invariants. The <code>\\invariant</code> command ends when a blank line or some other sectioning command is encountered.

<hr/>


## \\note { text } {#cmdnote}


Starts a paragraph where a note can be entered. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <code>\\note</code> commands will be joined into a single paragraph. Each note description will start on a new line. Alternatively, one <code>\\note</code> command may mention several notes. The <code>\\note</code> command ends when a blank line or some other sectioning command is encountered. See section <a href="#cmdpar">\\par</a> for an example.

<hr/>


## \\par \[(paragraph title)\] { paragraph } {#cmdpar}


If a paragraph title is given this command starts a paragraph with a user defined heading. The heading extends until the end of the line. The paragraph following the command will be indented.

If no paragraph title is given this command will start a new paragraph. This will also work inside other paragraph commands (like <a href="#cmdparam">\\param</a> or <a href="#cmdwarning">\\warning</a>) without ending that command.

The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. The <code>\\par</code> command ends when a blank line or some other sectioning command is encountered.

<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! \class Par_Test</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * Normal text.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * \par User defined paragraph:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * Contents of the paragraph.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * \par</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * New paragraph under the same heading.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * \note</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * This note consists of two paragraphs.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * This is the first paragraph.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * \par</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * And this is the second paragraph.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * More normal text. </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">Par_Test {};</span></span></div>

</div>

 
  Click <a href="pathname:///examples/par/html/class_par___test.html">here</a>
  for the corresponding HTML documentation that is generated by Doxygen.
</dd>
</dl>


<hr/>


## \\param\[&lt;dir&gt;\] &lt;parameter-name&gt; { parameter description } {#cmdparam}


Starts a parameter description for a function parameter with name &lt;parameter-name&gt;, followed by a description of the parameter. The existence of the parameter is checked and a warning is given if the documentation of this (or any other) parameter is missing or not present in the function declaration or definition.

The <code>\\param</code> command has an optional attribute, &lt;dir&gt;, specifying the direction of the parameter. Possible values are "\[in\]", "\[out\]", and "\[in,out\]"; note the \[square\] brackets in this description. For the bidirecional values, directions "in" and "out" can be specified in any order, and they can either be written altogether, or separated with a comma (<code>,</code>) or a space. That means that for example values "\[outin\]" or "\[in out\]" are also valid. Note that it is also possible to put whitespace between the command and the &lt;dir&gt;. When a parameter is both input and output, \[in,out\] is used as attribute. Here is an example for the function <code>memcpy:</code>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*!</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * Copies bytes from a source memory area to a destination memory area,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * where both areas may not overlap.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * @param[out] dest The memory area to copy to.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * @param[in]  src  The memory area to copy from.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> * @param[in]  n    The number of bytes to copy</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> memcpy(</span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> *dest, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> *src, </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> n);</span></span></div>

</div>


The parameter description is a paragraph with no special internal structure. All visual enhancement commands may be used inside the paragraph.

Multiple adjacent <code>\\param</code> commands will be joined into a single paragraph. Each parameter description will start on a new line. The <code>\\param</code> description ends when a blank line or some other sectioning command is encountered. See section <a href="#cmdfn">\\fn</a> for an example.

Note that you can also document multiple parameters with a single <code>\\param</code> command using a comma separated list. Here is an example:

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** Sets the position.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  @param x,y,z Coordinates of the position in 3D space.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> setPosition(</span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> x,</span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> y,</span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> z,</span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Note that for PHP one can also specify the type (or types if you separate them with a pipe symbol) which are allowed for a parameter (as this is not part of the definition). The syntax is the same as for the <code>phpDocumentor</code>, i.e.


<pre><code>@param  datatype1|datatype2 $paramname description
</code></pre>


<hr/>


## \\parblock {#cmdparblock}


For commands that expect a single paragraph as argument (such as <a href="#cmdpar">\\par</a>, <a href="#cmdparam">\\param</a> and <a href="#cmdwarning">\\warning</a>), the <a href="#cmdparblock">\\parblock</a> command allows to start a description that covers multiple paragraphs, which then ends with <a href="#cmdendparblock">\\endparblock</a>.

Example:


<pre><code>/** Example of a param command with a description consisting of two paragraphs
 *  \param p
 *  \parblock
 *  First paragraph of the param description.
 *
 *  Second paragraph of the param description.
 *  \endparblock
 *  Rest of the comment block continues.
 */
</code></pre>


Note that the <code>\\parblock</code> command may also appear directly after <a href="#cmdparam">\\param</a>'s first argument.

<hr/>


## \\endparblock {#cmdendparblock}


This ends a block of paragraphs started with <a href="#cmdparblock">\\parblock</a>.

<hr/>


## \\tparam &lt;template-parameter-name&gt; { description } {#cmdtparam}


Starts a template parameter for a class or function template parameter with name &lt;template-parameter-name&gt;, followed by a description of the template parameter.

Otherwise similar to <a href="#cmdparam">\\param</a>.

<hr/>


## \\post { description of the postcondition } {#cmdpost}


Starts a paragraph where the postcondition of an entity can be described. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <code>\\post</code> commands will be joined into a single paragraph. Each postcondition will start on a new line. Alternatively, one <code>\\post</code> command may mention several postconditions. The <code>\\post</code> command ends when a blank line or some other sectioning command is encountered.

<hr/>


## \\pre { description of the precondition } {#cmdpre}


Starts a paragraph where the precondition of an entity can be described. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <code>\\pre</code> commands will be joined into a single paragraph. Each precondition will start on a new line. Alternatively, one <code>\\pre</code> command may mention several preconditions. The <code>\\pre</code> command ends when a blank line or some other sectioning command is encountered.

<hr/>


## \\remark { remark text } {#cmdremark}


Starts a paragraph where one or more remarks may be entered. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <code>\\remark</code> commands will be joined into a single paragraph. Each remark will start on a new line. Alternatively, one <code>\\remark</code> command may mention several remarks. The <code>\\remark</code> command ends when a blank line or some other sectioning command is encountered.

<hr/>


## \\remarks { remark text } {#cmdremarks}


Equivalent to <a href="#cmdremark">\\remark</a>.

<hr/>


## \\result { description of the result value } {#cmdresult}


Equivalent to <a href="#cmdreturn">\\return</a>.

<hr/>


## \\return { description of the return value } {#cmdreturn}


Starts a return value description for a function. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <code>\\return</code> commands will be joined into a single paragraph. The <code>\\return</code> description ends when a blank line or some other sectioning command is encountered. See section <a href="#cmdfn">\\fn</a> for an example.

<hr/>


## \\returns { description of the return value } {#cmdreturns}


Equivalent to <a href="#cmdreturn">\\return</a>.

<hr/>


## \\retval &lt;return value&gt; { description } {#cmdretval}


Starts a description for a function's return value with name &lt;return value&gt;, followed by a description of the return value. The text of the paragraph that forms the description has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <code>\\retval</code> commands will be joined into a single paragraph. Each return value description will start on a new line. The <code>\\retval</code> description ends when a blank line or some other sectioning command is encountered.

<hr/>


## \\sa { references } {#cmdsa}


Starts a paragraph where one or more cross-references to classes, functions, methods, variables, files or URL may be specified. Two names joined by either <code>::</code> or <code>#</code> are understood as referring to a class and one of its members. One of several overloaded methods or constructors may be selected by including a parenthesized list of argument types after the method name.

Synonymous to <a href="#cmdsee">\\see</a>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="/web-doxygen/docs/pages/autolink">autolink</a> for information on how to create links to objects.
</dd>
</dl>


<hr/>


## \\see { references } {#cmdsee}


Equivalent to <a href="#cmdsa">\\sa</a>. Introduced for compatibility with Javadoc.

<hr/>


## \\short { short description } {#cmdshort}


Equivalent to <a href="#cmdbrief">\\brief</a>.

<hr/>


## \\since { text } {#cmdsince}


This command can be used to specify since when (version or time) an entity is available. The paragraph that follows <code>\\since</code> does not have any special internal structure. All visual enhancement commands may be used inside the paragraph. The <code>\\since</code> description ends when a blank line or some other sectioning command is encountered.

<hr/>


## \\test { paragraph describing a test case } {#cmdtest}


Starts a paragraph where one or more test cases can be described. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <code>\\test</code> commands will be joined into a single paragraph. Each test case description will start on a new line. Alternatively, one <code>\\test</code> command may mention several test cases. The <code>\\test</code> command ends when a blank line or some other sectioning command is encountered.

The description will also add an item to a separate Test list and the two instances of the description will be cross-referenced. Each item in the Test list will be preceded by a header that indicates the origin of the item.

The Test list and the corresponding entries can be disabled by setting the <a href="/web-doxygen/docs/pages/config/#cfg_generate_testlist">GENERATE\_TESTLIST</a> to <code>NO</code>.

<hr/>


## \\throw &lt;exception-object&gt; { exception description } {#cmdthrow}


Synonymous <a href="#cmdexception">\\exception</a>.

<dl class="doxySectionUser">
<dt>Note:</dt>
<dd>
the command <a href="#cmdthrows">\throws</a> is a synonym for this command.
</dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdexception">\exception</a>
</dd>
</dl>


<hr/>


## \\throws &lt;exception-object&gt; { exception description } {#cmdthrows}


Equivalent to <a href="#cmdthrow">\\throw</a>.

<hr/>


## \\todo { paragraph describing what is to be done } {#cmdtodo}


Starts a paragraph where one or more todo items are described. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <code>\\todo</code> commands will be joined into a single paragraph. Each todo description will start on a new line. Alternatively, one <code>\\todo</code> command may mention several todo descriptions. The <code>\\todo</code> command ends when a blank line or some other sectioning command is encountered.

The description will also add an item to a separate Todo list and the two instances of the description will be cross-referenced. Each item in the Todo list will be preceded by a header that indicates the origin of the item.

The Todo list and the corresponding entries can be disabled by setting the <a href="/web-doxygen/docs/pages/config/#cfg_generate_todolist">GENERATE\_TODOLIST</a> to <code>NO</code>.

<hr/>


## \\version { version number } {#cmdversion}


Starts a paragraph where one or more version strings may be entered. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <code>\\version</code> commands will be joined into a single paragraph. Each version description will start on a new line. Alternatively, one <code>\\version</code> command may mention several version strings. The \\version command ends when a blank line or some other sectioning command is encountered. See section <a href="#cmdauthor">\\author</a> for an example.

<hr/>


## \\warning { warning message } {#cmdwarning}


Starts a paragraph where one or more warning messages may be entered. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <code>\\warning</code> commands will be joined into a single paragraph. Each warning description will start on a new line. Alternatively, one <code>\\warning</code> command may mention several warnings. The <code>\\warning</code> command ends when a blank line or some other sectioning command is encountered. See section <a href="#cmdauthor">\\author</a> for an example.

<hr/>


## \\xrefitem &lt;key&gt; "heading" "list title" { text } {#cmdxrefitem}


This command is a generalization of commands such as <a href="#cmdtodo">\\todo</a> and <a href="#cmdbug">\\bug</a>. It can be used to create user-defined text sections which are automatically cross-referenced between the place of occurrence and a related page, which will be generated. On the related page all sections of the same type will be collected.

The first argument &lt;key&gt; is an identifier uniquely representing the type of the section. The second argument is a quoted string representing the heading of the section under which text passed as the fourth argument is put. The third argument (list title) is used as the title for the related page containing all items with the same key. The second and third string argument cannot contain a newline. The keys <code>"todo"</code>, <code>"test"</code>, <code>"bug"</code> and <code>"deprecated"</code> are predefined.

To get an idea on how to use the <code>\\xrefitem</code> command and what its effect is, consider the todo list, which (for English output) can be seen an alias for the command


<pre><code>\xrefitem todo "Todo" "Todo List"
</code></pre>


Since it is very tedious and error-prone to repeat the first three parameters of the command for each section, the command is meant to be used in combination with the <a href="/web-doxygen/docs/pages/config/#cfg_aliases">ALIASES</a> option in the configuration file. To define a new command <code>\\reminder</code>, for instance, one should add the following line to the configuration file:


<pre><code>ALIASES += "reminder=\xrefitem reminders \"Reminder\" \"Reminders\""
</code></pre>


Note the use of escaped quotes for the second and third argument of the <code>\\xrefitem</code> command.

In case parameter "(heading)" is the empty string no heading is generated. This can be useful when used in combination with the <a href="#cmdpage">\\page</a> command e.g.


<pre><code>/** @page my_errors My Errors
 *  @brief Errors page
 *
 *  Errors page contents.
 */

/** \error ERROR 101: in case a file can not be opened.
    Check about file system read/write access. */
#define MY_ERR_CANNOT_OPEN_FILE                   101

/** \error ERROR 102: in case a file can not be closed.
    Check about file system read/write access. */
#define MY_ERR_CANNOT_CLOSE_FILE                  102
</code></pre>


with <code>\\error</code> defined as


<pre><code>ALIASES += "error=\xrefitem my_errors \"\" \"\""
</code></pre>


<hr/>

 <center>

##  ---  Commands to create links  ---  
 </center>

<hr/>


## \\addindex (text) {#cmdaddindex}


This command adds (text) to the <code>{\LaTeX}</code> , DocBook and RTF index.

<hr/>


## \\anchor &lt;word&gt; {#cmdanchor}


This command places an invisible, named anchor into the documentation to which you can refer with the <a href="#cmdref">\\ref</a> command.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdref">\ref</a>.
</dd>
</dl>


<hr/>


## \\cite\['{'\[option\]'}'\] &lt;label&gt; {#cmdcite}


Adds a bibliographic reference in the text and in the list of bibliographic references. The &lt;label&gt; must be a valid BibTeX label that can be found in one of the .bib files listed in <a href="/web-doxygen/docs/pages/config/#cfg_cite_bib_files">CITE\_BIB\_FILES</a>. For the <code>{\LaTeX}</code> output the formatting of the reference in the text can be configured with <a href="/web-doxygen/docs/pages/config/#cfg_latex_bib_style">LATEX\_BIB\_STYLE</a>. For other output formats a fixed representation is used. Note that using this command requires the <code>bibtex</code> tool to be present in the search path.

There are a number of options possible:

<ul class="doxyList ">
<li><code>number</code>, <code>shortauthor</code>, <code>year</code>, these options are mutually exclusive, in case none of these is specified <code>number</code> is assumed.

<ul class="doxyList ">
<li><code>number</code> create a numerical reference</li>
<li><code>shortauthor</code> just the surname of the first author is given, and in case multiple authors are present the text "et al." is added</li>
<li><code>year</code>, the year of publication is mentioned (when specified in the bibtex file.</li>
</ul></li>
<li><code>nopar</code>, no (square) brackets are added</li>
<li><code>nocite</code>, no link to a citation in the bibliography is made (and the reference is not added to the bibliography based on this item)</li>
</ul>

<hr/>


## \\endlink {#cmdendlink}


This command ends a link that is started with the <a href="#cmdlink">\\link</a> command.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdlink">\link</a>.
</dd>
</dl>


<hr/>


## \\link &lt;link-object&gt; {#cmdlink}


The links that are automatically generated by Doxygen always have the name of the object they point to as link-text.

The <code>\\link</code> command can be used to create a link to an object (a file, class, or member) with a user specified link-text. The link command should end with an <a href="#cmdendlink">\\endlink</a> command. All text between the <code>\\link</code> and <a href="#cmdendlink">\\endlink</a> commands serves as text for a link to the &lt;link-object&gt; specified as the first argument of <code>\\link</code>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
Section <a href="/web-doxygen/docs/pages/autolink">autolink</a> for more information on automatically generated links and valid link-objects.
</dd>
</dl>


<hr/>


## \\ref &lt;name&gt; \["(text)"\] {#cmdref}


Creates a reference to a named symbol, file, section, subsection, page or anchor.

For HTML documentation the reference command will generate a link to the section. For a section or subsection the title of the section will be used as the text of the link. For an anchor the optional text between quotes will be used or &lt;name&gt; if no text is specified.

In case &lt;name&gt; has spaces (for instance if it refers a file name containing spaces) you need to add double quotes around the &lt;name&gt;, e.g. "my file.md".

For <code>{\LaTeX}</code> documentation the reference command will be the same unless the <a href="/web-doxygen/docs/pages/config/#cfg_pdf_hyperlinks">PDF\_HYPERLINKS</a> option has been set to <code>NO</code>, in this case it generates the section title for sections or the text if &lt;name&gt; refers to an anchor followed by a page number.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
Section <a href="#cmdpage">\page</a> for an example of the <code>\ref</code> command.
</dd>
</dl>


<hr/>


## \\refitem &lt;name&gt; {#cmdrefitem}


Just like the <a href="#cmdref">\\ref</a> command, this command creates a reference to a named section, but this reference appears in a list that is started by <a href="#cmdsecreflist">\\secreflist</a> and ends with <a href="#cmdendsecreflist">\\endsecreflist</a>. An example of such a list can be seen <a href="#showsecreflist">at the top of the page</a>.

<hr/>


## \\secreflist {#cmdsecreflist}


Starts an index list of item, created with <a href="#cmdrefitem">\\refitem</a> that each link to a named section.

<hr/>


## \\endsecreflist {#cmdendsecreflist}


End an index list started with <a href="#cmdsecreflist">\\secreflist</a>.

<hr/>


## \\subpage &lt;name&gt; \["(text)"\] {#cmdsubpage}


This command can be used to create a hierarchy of pages. The same structure can be made using the <a href="#cmddefgroup">\\defgroup</a> and <a href="#cmdingroup">\\ingroup</a> commands, but for pages the <code>\\subpage</code> command is often more convenient. The main page (see <a href="#cmdmainpage">\\mainpage</a>) is typically the root of hierarchy.

This command behaves similar as <a href="#cmdref">\\ref</a> in the sense that it creates a reference to a page labeled &lt;name&gt; with the optional link text as specified in the second argument.

It differs from the <a href="#cmdref">\\ref</a> command in that it only works for pages, and creates a parent-child relation between pages, where the child page (or sub page) is identified by label &lt;name&gt;.

See the <a href="#cmdsection">\\section</a> and <a href="#cmdsubsection">\\subsection</a> commands if you want to add structure without creating multiple pages.

:::info
Each page can be the sub page of only one other page and no cyclic relations are allowed, i.e. the page hierarchy must have a tree structure.
:::


Here is an example:


<pre><code>/*! \mainpage A simple manual

Some general info.

This manual is divided in the following sections:
- \subpage intro
- \subpage advanced "Advanced usage"
*/

//-----------------------------------------------------------

/*! \page intro Introduction
This page introduces the user to the topic.
Now you can proceed to the \ref advanced "advanced section".
*/

//-----------------------------------------------------------

/*! \page advanced Advanced Usage
This page is for advanced users.
Make sure you have first read \ref intro "the introduction".
*/
</code></pre>


<hr/>


## \\tableofcontents\['{'\[option\[:level\]\]\[,option\[:level\]\]\*'}'\] {#cmdtableofcontents}


Creates a table of contents at the top of a page, listing all sections and subsections in the page. The <code>option</code> can be <code>HTML</code> or <code>LaTeX</code> or <code>XML</code> or <code>DocBook</code>. When a <code>level</code> is specified this means the maximum nesting level that is shown. The value of <code>level</code> should be in the range 1..6, values outside this range are considered to be 6. In case no <code>level</code> is specified <code>level</code> is set to 6 (show all) In case no <code>option</code>. is specified <code>\\tableofcontents</code> acts as if just the <code>option</code> <code>HTML</code> and <code>XML</code> was specified. In case of multiple <code>\\tableofcontents</code> commands in a page the <code>option</code>(s) will be used additional to the already specified <code>option</code>(s), but only the last <code>level</code> of an <code>option</code> is valid.

:::warning
This command only works inside related page documentation and <em>not</em> in other documentation blocks and only has effect in the specified output!
:::


<hr/>


## \\section &lt;section-name&gt; (section title) {#cmdsection}


Creates a section with name &lt;section-name&gt;. The title of the section should be specified as the second argument of the <code>\\section</code> command.

:::warning
This command only works inside related page documentation and <em>not</em> in other documentation blocks!
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
Section <a href="#cmdpage">\page</a> for an example of the <code>\section</code> command.
</dd>
</dl>


<hr/>


## \\subsection &lt;subsection-name&gt; (subsection title) {#cmdsubsection}


Creates a subsection with name &lt;subsection-name&gt;. The title of the subsection should be specified as the second argument of the <code>\\subsection</code> command.

:::warning
This command only works inside a section of a related page documentation block and <em>not</em> in other documentation blocks!
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
Section <a href="#cmdpage">\page</a> for an example of the <code>\subsection</code> command.
</dd>
</dl>


<hr/>


## \\subsubsection &lt;subsubsection-name&gt; (subsubsection title) {#cmdsubsubsection}


Creates a subsubsection with name &lt;subsubsection-name&gt;. The title of the subsubsection should be specified as the second argument of the <code>\\subsubsection</code> command.

:::warning
This command only works inside a subsection of a related page documentation block and <em>not</em> in other documentation blocks!
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
Section <a href="#cmdpage">\page</a> for an example of the <a href="#cmdsection">\section</a> command and <a href="#cmdsubsection">\subsection</a> command.
</dd>
</dl>


<hr/>


## \\paragraph &lt;paragraph-name&gt; (paragraph title) {#cmdparagraph}


Creates a named paragraph with name &lt;paragraph-name&gt;. The title of the paragraph should be specified as the second argument of the <code>\\paragraph</code> command.

:::warning
This command only works inside a subsubsection of a related page documentation block and <em>not</em> in other documentation blocks!
:::


<hr/>


## \\subparagraph &lt;subparagraph-name&gt; (subparagraph title) {#cmdsubparagraph}


Creates a named subparagraph with name &lt;subparagraph-name&gt;. The title of the subparagraph should be specified as the second argument of the <code>\\subparagraph</code> command.

:::warning
This command only works inside a paragraph of a related page documentation block and <em>not</em> in other documentation blocks!
:::


<hr/>


## \\subsubparagraph &lt;subsubparagraph-name&gt; (subsubparagraph title) {#cmdsubsubparagraph}


Creates a named subsubparagraph with name &lt;subsubparagraph-name&gt;. The title of the subsubparagraph should be specified as the second argument of the <code>\\subsubparagraph</code> command.

:::warning
This command only works inside a subparagraph of a related page documentation block and <em>not</em> in other documentation blocks!
:::


<hr/>

 <center>

##  ---  Commands for displaying examples  ---  
 </center>

<hr/>


## \\dontinclude\['{lineno}'\] &lt;file-name&gt; {#cmddontinclude}


This command can be used to parse a source file without actually verbatim including it in the documentation (as the <a href="#cmdinclude">\\include</a> command does). This is useful if you want to divide the source file into smaller pieces and add documentation between the pieces. Source files or directories can be specified using the <a href="/web-doxygen/docs/pages/config/#cfg_example_path">EXAMPLE\_PATH</a> tag of Doxygen's configuration file.

You can add the option <code>lineno</code> to enable line numbers for the included code if desired.

You can add the option <code>strip</code> that will always hide any special comments from the included code, overruling the <a href="/web-doxygen/docs/pages/config/#cfg_strip_code_comments">STRIP\_CODE\_COMMENTS</a> setting, or add the option <code>nostrip</code> to always show the special comments.

The class and member declarations and definitions inside the code fragment are 'remembered' during the parsing of the comment block that contained the <code>\\dontinclude</code> command.

For line by line descriptions of source files, one or more lines of the example can be displayed using the <a href="#cmdline">\\line</a>, <a href="#cmdskip">\\skip</a>, <a href="#cmdskipline">\\skipline</a>, and <a href="#cmduntil">\\until</a> commands. An internal pointer is used for these commands. The <code>\\dontinclude</code> command sets the pointer to the first line of the example.

<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! A test class. */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">Include_Test</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">public</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    /// a member function</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> example();</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! \page pag_example</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \dontinclude include_test.cpp</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  Our main function starts like this:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \skip main</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \until {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  First we create an object \c t of the Include_Test class.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \skipline Include_Test</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  Then we call the example member function </span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \line example</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  After that our little test routine ends.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \line }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>

</div>


Where the example file <code>include_test.cpp</code> looks as follows:

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> main()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  Include_Test t;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  t.example();</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

 
  Click <a href="pathname:///examples/include/html/pag_example.html">here</a>
  for the corresponding HTML documentation that is generated by Doxygen.
</dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
sections <a href="#cmdline">\line</a>, <a href="#cmdskip">\skip</a>, <a href="#cmdskipline">\skipline</a>, <a href="#cmduntil">\until</a>, and <a href="#cmdinclude">\include</a>.
</dd>
</dl>


<hr/>


## \\include\['{'option'}'\] &lt;file-name&gt; {#cmdinclude}


This command can be used to include a source file as a block of code. The command takes the name of an include file as an argument. Source files or directories can be specified using the <a href="/web-doxygen/docs/pages/config/#cfg_example_path">EXAMPLE\_PATH</a> tag of Doxygen's configuration file.

If &lt;file-name&gt; itself is not unique for the set of example files specified by the <a href="/web-doxygen/docs/pages/config/#cfg_example_path">EXAMPLE\_PATH</a> tag, you can include part of the absolute path to disambiguate it.

Using the <code>\\include</code> command is equivalent to inserting the file into the documentation block and surrounding it with <a href="#cmdcode">\\code</a> and <a href="#cmdendcode">\\endcode</a> commands.

The main purpose of the <code>\\include</code> command is to avoid code duplication in case of example blocks that consist of multiple source and header files.

For a line by line description of a source files use the <a href="#cmddontinclude">\\dontinclude</a> command in combination with the <a href="#cmdline">\\line</a>, <a href="#cmdskip">\\skip</a>, <a href="#cmdskipline">\\skipline</a>, and <a href="#cmduntil">\\until</a> commands.

Alternatively, the <a href="#cmdsnippet">\\snippet</a> command can be used to include only a fragment of a source file. For this to work the fragment has to be marked.

:::info
Doxygen's special commands do not work inside blocks of code. It is allowed to nest C-style comments inside a code block though.
:::


The <code>option</code> can either be <code>lineno</code>, or <code>doc</code>, and additionally <code>local</code> can be specified.

<ul class="doxyList ">
<li>The <code>option</code> <code>lineno</code> can be used to enable line numbers for the included code if desired.</li>
<li>The <code>option</code> <code>doc</code> can be used to treat the file as documentation rather than code.</li>
<li>The <code>option</code> <code>local</code> can be used make Doxygen interpret the code as if it was in the class or namespace in which the include command appears, rather than the global namespace.</li>
<li>The <code>option</code> <code>strip</code> can be used to always hide any special comments from the included code, overruling the <a href="/web-doxygen/docs/pages/config/#cfg_strip_code_comments">STRIP_CODE_COMMENTS</a> setting, and option <code>nostrip</code> can be used to always show the special comments. These options have no effect in combination with the <code>option</code> <code>doc</code>.</li>
</ul>

When using option <code>doc</code>, there is also the option <code>raise</code> that can be specified to raise all sections found in the referenced file by a certain amount. For example


<pre><code>  \include{doc,raise=1} file.dox
</code></pre>


will treat any level 1 <code>\\section</code> found in <code>file.dox</code> as a level 2 <code>\\subsection</code>, and any level 2 <code>\\subsection</code> into a level 3 <code>\\subsubsection</code>, etc. Similarly, for Markdown a <code>#</code> section will be treated as a <code>##</code> section.

Furthermore, there is the option <code>prefix</code> that can be used to add a prefix to each label of the included sections, so that they remain unique. For example:


<pre><code>  \include{doc,prefix=fn_} file.dox
</code></pre>


will treat e.g. <code>\\section s1</code> found in <code>file.dox</code> as if it was specified as <code>\\section fn\_s1</code>.

:::info
The included documentation should not have comment signs in it as they will appear in the documentation as well.
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
sections <a href="#cmdexample">\example</a>, <a href="#cmddontinclude">\dontinclude</a>, <a href="#cmdverbatim">\verbatim</a>, <a href="#cmdincludedoc">\includedoc</a>, and <a href="#cmdsnippet">\snippet</a>.
</dd>
</dl>


<hr/>


## \\includelineno &lt;file-name&gt; {#cmdincludelineno}


This command is obsolete and is still supported for backward compatibility reasons, it works the same way as <a href="#cmdinclude">\\include{lineno}</a>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
sections <a href="#cmdinclude">\include{lineno}</a>.
</dd>
</dl>


<hr/>


## \\includedoc\['{'option'}'\] &lt;file-name&gt; {#cmdincludedoc}


This command is obsolete and is still supported for backward compatibility reasons, it works the same way as <a href="#cmdinclude">\\include{doc}</a>

The <code>option</code>s are the same <code>option</code>s that can be used with the <code>\\include</code> when using there the option <code>doc</code>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdinclude">\include{doc}</a>.
</dd>
</dl>


<hr/>


## \\line ( pattern ) {#cmdline}


This command searches line by line through the example that was last included using <a href="#cmdinclude">\\include</a> or <a href="#cmddontinclude">\\dontinclude</a> until it finds a non-blank line. If that line contains the specified pattern, it is written to the output.

The internal pointer that is used to keep track of the current line in the example, is set to the start of the line following the non-blank line that was found (or to the end of the example if no such line could be found).

See section <a href="#cmddontinclude">\\dontinclude</a> for an example.

<hr/>


## \\skip ( pattern ) {#cmdskip}


This command searches line by line through the example that was last included using <a href="#cmdinclude">\\include</a> or <a href="#cmddontinclude">\\dontinclude</a> until it finds a line that contains the specified pattern.

The internal pointer that is used to keep track of the current line in the example, is set to the start of the line that contains the specified pattern (or to the end of the example if the pattern could not be found).

See section <a href="#cmddontinclude">\\dontinclude</a> for an example.

<hr/>


## \\skipline ( pattern ) {#cmdskipline}


This command searches line by line through the example that was last included using <a href="#cmdinclude">\\include</a> or <a href="#cmddontinclude">\\dontinclude</a> until it finds a line that contains the specified pattern. It then writes the line to the output.

The internal pointer that is used to keep track of the current line in the example, is set to the start of the line following the line that is written (or to the end of the example if the pattern could not be found).

<dl class="doxySectionUser">
<dt>Note:</dt>
<dd>
The command:


<pre><code>\skipline pattern
</code></pre>


is equivalent to:


<pre><code>\skip pattern
\line pattern
</code></pre>
</dd>
</dl>


See section <a href="#cmddontinclude">\\dontinclude</a> for an example.

<hr/>


## \\snippet\['{'option'}'\] &lt;file-name&gt; ( block\_id ) {#cmdsnippet}


Where the <a href="#cmdinclude">\\include</a> command can be used to include a complete file as source code, this command can be used to quote only a fragment of a source file. In case <code>this</code> is used as &lt;file-name&gt; the current file is taken as file to take the snippet from.

For example, the putting the following command in the documentation, references a snippet in file <code>example.cpp</code> residing in a subdirectory which should be pointed to by <a href="/web-doxygen/docs/pages/config/#cfg_example_path">EXAMPLE\_PATH</a>.


<pre><code>  \snippet snippets/example.cpp Adding a resource
</code></pre>


The text following the file name is the unique identifier for the snippet. This is used to delimit the quoted code in the relevant snippet file as shown in the following example that corresponds to the above <code>\\snippet</code> command:

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    QImage image(64, 64, QImage::Format_RGB32);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    image.fill(qRgb(255, 160, 128));</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">//! [Adding a resource]</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    document-&gt;addResource(QTextDocument::ImageResource,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        QUrl(</span><span class="doxyHighlightStringLiteral">"mydata://image.png"</span><span class="doxyHighlight">), QVariant(image));</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">//! [Adding a resource]</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    ...</span></span></div>

</div>


Note that the lines containing the block markers will not be included, so the output will be:

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">document-&gt;addResource(QTextDocument::ImageResource,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    QUrl(</span><span class="doxyHighlightStringLiteral">"mydata://image.png"</span><span class="doxyHighlight">), QVariant(image));</span></span></div>

</div>


Note also that the \[block\_id\] markers should appear exactly twice in the source file.

The <code>option</code> can either be <code>lineno</code>, <code>trimleft</code> or <code>doc</code>, and additionally <code>local</code> can be specified.

<ul class="doxyList ">
<li>The <code>option</code> <code>lineno</code> can be used to enable line numbers for the included code if desired.</li>
<li>The <code>option</code> <code>trimleft</code> can be used to remove the common spacing in front of all lines (also taking in account the setting of the <a href="/web-doxygen/docs/pages/config/#cfg_tab_size">TAB_SIZE</a> tag).</li>
<li>The <code>option</code> <code>doc</code> can be used to treat the file as documentation rather than code.</li>
<li>The <code>option</code> <code>local</code> can be used make Doxygen interpret the code as if it was in the class or namespace in which the include command appears, rather than the global namespace.</li>
<li>The <code>option</code> <code>strip</code> can be used to always hide any special comments from the included code, overruling the <a href="/web-doxygen/docs/pages/config/#cfg_strip_code_comments">STRIP_CODE_COMMENTS</a> setting, and option <code>nostrip</code> can be used to always show the special comments. These options have no effect in combination with the <code>option</code> <code>doc</code>.</li>
</ul>

When using option <code>doc</code>, there is also the option <code>raise</code> that can be specified to raise all sections found in the referenced file by a certain amount. For example


<pre><code> \snippet{doc,raise=1} file.dox XXX
</code></pre>


will treat any level 1 <code>\\section</code> found the snippet as a level 2 <code>\\subsection</code>, and any level 2 <code>\\subsection</code> into a level 3 <code>\\subsubsection</code>, etc. Similarly, for Markdown a <code>#</code> section will be treated as a <code>##</code> section.

Furthermore, there is the option <code>prefix</code> that can be used to add a prefix to each label of the included sections, so that they remain unique. For example:


<pre><code> \include{doc,prefix=fn_} file.dox
</code></pre>


will treat e.g. <code>\\section s1</code> found in <code>file.dox</code> as if it was specified as <code>\\section fn\_s1</code>.

:::info
The included documentation should not have comment signs in it as they will appear in the documentation as well.
:::


see section <a href="#cmddontinclude">\\dontinclude</a> for an alternative way to include fragments of a source file that does not require markers.

<hr/>


## \\snippetlineno &lt;file-name&gt; ( block\_id ) {#cmdsnippetlineno}


This command is obsolete and is still supported for backward compatibility reasons, it works the same way as <a href="#cmdsnippet">\\snippet{lineno}</a>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
sections <a href="#cmdsnippet">\snippet{lineno}</a>
</dd>
</dl>


<hr/>


## \\snippetdoc\['{'option'}'\] &lt;file-name&gt; ( block\_id ) {#cmdsnippetdoc}


This command is obsolete and is still supported for backward compatibility reasons, it works the same way as <a href="#cmdsnippet">\\snippet{doc}</a>

The <code>option</code>s are the same <code>option</code>s that can be used with the <code>\\snippet</code> when using there the option <code>doc</code>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdsnippet">\snippet{doc}</a> and <a href="#cmdinclude">\include{doc}</a>.
</dd>
</dl>


<hr/>


## \\until ( pattern ) {#cmduntil}


This command writes all lines of the example that was last included using <a href="#cmdinclude">\\include</a> or <a href="#cmddontinclude">\\dontinclude</a> to the output, until it finds a line containing the specified pattern. The line containing the pattern will be written as well.

The internal pointer that is used to keep track of the current line in the example, is set to the start of the line following last written line (or to the end of the example if the pattern could not be found).

See section <a href="#cmddontinclude">\\dontinclude</a> for an example.

<hr/>


## \\verbinclude &lt;file-name&gt; {#cmdverbinclude}


This command includes the contents of the file &lt;file-name&gt; verbatim in the documentation. The command is equivalent to pasting the contents of the file in the documentation and placing <a href="#cmdverbatim">\\verbatim</a> and <a href="#cmdendverbatim">\\endverbatim</a> commands around it.

Files or directories that Doxygen should look for can be specified using the <a href="/web-doxygen/docs/pages/config/#cfg_example_path">EXAMPLE\_PATH</a> tag of Doxygen's configuration file.

<hr/>


## \\htmlinclude\['\[block\]'\] &lt;file-name&gt; {#cmdhtmlinclude}


This command includes the contents of the file &lt;file-name&gt; as is in the HTML documentation and tagged with <code>&lt;htmlonly&gt;</code> in the generated XML output. The command is equivalent to pasting the contents of the file in the documentation and placing <a href="#cmdhtmlonly">\\htmlonly</a> and <a href="#cmdendhtmlonly">\\endhtmlonly</a> commands around it.

Normally the contents of the file indicated by <a href="#cmdhtmlinclude">\\htmlinclude</a> is inserted as-is. When you want to insert a HTML fragment that has block scope like a table or list which should appear outside &lt;p&gt;..&lt;/p&gt;, this can lead to invalid HTML. You can use <code>\\htmlinclude\[block\]</code> to make Doxygen end the current paragraph and restart after the file is included.

Files or directories that Doxygen should look for can be specified using the <a href="/web-doxygen/docs/pages/config/#cfg_example_path">EXAMPLE\_PATH</a> tag of Doxygen's configuration file.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdhtmlonly">\htmlonly</a>, <a href="#cmdlatexinclude">\latexinclude</a>, <a href="#cmdrtfinclude">\rtfinclude</a>, <a href="#cmdmaninclude">\maninclude</a>, <a href="#cmddocbookinclude">\docbookinclude</a> and <a href="#cmdxmlinclude">\xmlinclude</a>.
</dd>
</dl>


<hr/>


## \\latexinclude &lt;file-name&gt; {#cmdlatexinclude}


This command includes the contents of the file &lt;file-name&gt; as is in the <code>{\LaTeX}</code> documentation and tagged with <code>&lt;latexonly&gt;</code> in the generated XML output. The command is equivalent to pasting the contents of the file in the documentation and placing <a href="#cmdlatexonly">\\latexonly</a> and <a href="#cmdendlatexonly">\\endlatexonly</a> commands around it.

Files or directories that Doxygen should look for can be specified using the <a href="/web-doxygen/docs/pages/config/#cfg_example_path">EXAMPLE\_PATH</a> tag of Doxygen's configuration file.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdlatexonly">\latexonly</a>, <a href="#cmdhtmlinclude">\htmlinclude</a>, <a href="#cmdrtfinclude">\rtfinclude</a>, <a href="#cmdmaninclude">\maninclude</a>, <a href="#cmddocbookinclude">\docbookinclude</a> and <a href="#cmdxmlinclude">\xmlinclude</a>.
</dd>
</dl>


<hr/>


## \\rtfinclude &lt;file-name&gt; {#cmdrtfinclude}


This command includes the contents of the file &lt;file-name&gt; as is in the RTF documentation and tagged with <code>&lt;rtfonly&gt;</code> in the generated XML output. The command is equivalent to pasting the contents of the file in the documentation and placing <a href="#cmdrtfonly">\\rtfonly</a> and <a href="#cmdendrtfonly">\\endrtfonly</a> commands around it.

Files or directories that Doxygen should look for can be specified using the <a href="/web-doxygen/docs/pages/config/#cfg_example_path">EXAMPLE\_PATH</a> tag of Doxygen's configuration file.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdrtfonly">\rtfonly</a>, <a href="#cmdhtmlinclude">\htmlinclude</a>, <a href="#cmdlatexinclude">\latexinclude</a>, <a href="#cmdmaninclude">\maninclude</a>, <a href="#cmddocbookinclude">\docbookinclude</a> and <a href="#cmdxmlinclude">\xmlinclude</a>.
</dd>
</dl>


<hr/>


## \\maninclude &lt;file-name&gt; {#cmdmaninclude}


This command includes the contents of the file &lt;file-name&gt; as is in the MAN documentation and tagged with <code>&lt;manonly&gt;</code> in the generated XML output. The command is equivalent to pasting the contents of the file in the documentation and placing <a href="#cmdmanonly">\\manonly</a> and <a href="#cmdendmanonly">\\endmanonly</a> commands around it.

Files or directories that Doxygen should look for can be specified using the <a href="/web-doxygen/docs/pages/config/#cfg_example_path">EXAMPLE\_PATH</a> tag of Doxygen's configuration file.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdmanonly">\manonly</a>, <a href="#cmdhtmlinclude">\htmlinclude</a>, <a href="#cmdlatexinclude">\latexinclude</a>, <a href="#cmdrtfinclude">\rtfinclude</a>, <a href="#cmddocbookinclude">\docbookinclude</a> and <a href="#cmdxmlinclude">\xmlinclude</a>.
</dd>
</dl>


<hr/>


## \\docbookinclude &lt;file-name&gt; {#cmddocbookinclude}


This command includes the contents of the file &lt;file-name&gt; as is in the DocBook documentation and tagged with <code>&lt;docbookonly&gt;</code> in the generated XML output. The command is equivalent to pasting the contents of the file in the documentation and placing <a href="#cmddocbookonly">\\docbookonly</a> and <a href="#cmdenddocbookonly">\\enddocbookonly</a> commands around it.

Files or directories that Doxygen should look for can be specified using the <a href="/web-doxygen/docs/pages/config/#cfg_example_path">EXAMPLE\_PATH</a> tag of Doxygen's configuration file.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmddocbookonly">\docbookonly</a>, <a href="#cmdhtmlinclude">\htmlinclude</a>, <a href="#cmdlatexinclude">\latexinclude</a>, <a href="#cmdrtfinclude">\rtfinclude</a>, <a href="#cmdmaninclude">\maninclude</a> and <a href="#cmdxmlinclude">\xmlinclude</a>.
</dd>
</dl>


<hr/>


## \\xmlinclude &lt;file-name&gt; {#cmdxmlinclude}


This command includes contents of the file &lt;file-name&gt; as is in the XML documentation. The command is equivalent to pasting the contents of the file in the documentation and placing <a href="#cmdxmlonly">\\xmlonly</a> and <a href="#cmdendxmlonly">\\endxmlonly</a> commands around it.

Files or directories that Doxygen should look for can be specified using the <a href="/web-doxygen/docs/pages/config/#cfg_example_path">EXAMPLE\_PATH</a> tag of Doxygen's configuration file.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdxmlonly">\xmlonly</a>, <a href="#cmdhtmlinclude">\htmlinclude</a>, <a href="#cmdlatexinclude">\latexinclude</a>, <a href="#cmdrtfinclude">\rtfinclude</a>, <a href="#cmdmaninclude">\maninclude</a> and <a href="#cmddocbookinclude">\docbookinclude</a>.
</dd>
</dl>


<hr/>

 <center>

##  ---  Commands for visual enhancements  ---  
 </center>

## \\a &lt;word&gt; {#cmda}


Displays the argument &lt;word&gt; in italics. Use this command to emphasize words. Use this command to refer to member arguments in the running text.

<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<pre><code>  ... the \a x and \a y coordinates are used to ...
</code></pre>


This will result in the following text:
<br/>

<br/>
 ... the <em>x</em> and <em>y</em> coordinates are used to ...
</dd>
</dl>


Equivalent to <a href="#cmde">\\e</a> and <a href="#cmdem">\\em</a>. To emphasize multiple words use <a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_EM">&lt;em&gt;</a>multiple words<a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_endEM">&lt;/em&gt;</a>.

<hr/>


## \\arg { item-description } {#cmdarg}


This command has one argument that continues until the first blank line or until another <code>\\arg</code> is encountered. The command can be used to generate a simple, not nested list of arguments. Each argument should start with a <code>\\arg</code> command.

<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
Typing:


<pre><code>  \arg \c AlignLeft left alignment.
  \arg \c AlignCenter center alignment.
  \arg \c AlignRight right alignment

  No other types of alignment are supported.
</code></pre>


will result in the following text:
<br/>

<br/>

<ul class="doxyList ">
<li><code>AlignLeft</code> left alignment.</li>
<li><code>AlignCenter</code> center alignment.</li>
<li><code>AlignRight</code> right alignment</li>
</ul>

<br/>
 No other types of alignment are supported.
</dd>
</dl>


<dl class="doxySectionUser">
<dt>Note:</dt>
<dd>
For nested lists, HTML commands should be used.
</dd>
</dl>


Equivalent to <a href="#cmdli">\\li</a>

<hr/>


## \\b &lt;word&gt; {#cmdb}


Displays the argument &lt;word&gt; using a bold font. Equivalent to <a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_B">&lt;b&gt;</a>word<a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_endB">&lt;/b&gt;</a>. To put multiple words in bold use <a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_B">&lt;b&gt;</a>multiple words<a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_endB">&lt;/b&gt;</a>.

<hr/>


## \\c &lt;word&gt; {#cmdc}


Displays the argument &lt;word&gt; using a typewriter font. Use this to refer to a word of code. Equivalent to <a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_TT">&lt;tt&gt;</a>word<a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_endTT">&lt;/tt&gt;</a>.

<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
Typing:


<pre><code>     ... This function returns \c void and not \c int ...
</code></pre>


will result in the following text:
<br/>

<br/>
 ... This function returns <code>void</code> and not <code>int</code> ...
</dd>
</dl>


Equivalent to <a href="#cmdp">\\p</a>. To have multiple words in typewriter font use <a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_TT">&lt;tt&gt;</a>multiple words<a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_endTT">&lt;/tt&gt;</a>.

<hr/>


## \\code\['{'&lt;word&gt;'}'\] {#cmdcode}


Starts a block of code. A code block is treated differently from ordinary text. It is interpreted as source code. The names of classes and members and other documented entities are automatically replaced by links to the documentation.

By default the language that is assumed for syntax highlighting is based on the location where the <code>\\code</code> block was found. If this part of a Python file for instance, the syntax highlight will be done according to the Python syntax.

If it is unclear from the context which language is meant (for instance the comment is in a <code>.txt</code> or <code>.markdown</code> file) then you can also explicitly indicate the language, by putting the file extension typically that Doxygen associated with the language in curly brackets after the code block. Here is an example:


<pre><code>  \code{.py}
  class Python:
     pass
  \endcode

  \code{.cpp}
  class Cpp {};
  \endcode
</code></pre>


If the contents of the code block are in a language that Doxygen cannot parse, Doxygen will just show the output as-is. You can make this explicit using .unparsed, or by giving some other extension that Doxygen doesn't support, e.g.


<pre><code>  \code{.unparsed}
  Show this as-is please
  \endcode

  \code{.sh}
  echo "This is a shell script"
  \endcode
</code></pre>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdendcode">\endcode</a> and section <a href="#cmdverbatim">\verbatim</a>.
</dd>
</dl>


<hr/>


## \\copydoc &lt;link-object&gt; {#cmdcopydoc}


Copies a documentation block from the object specified by &lt;link-object&gt; and pastes it at the location of the command. This command can be useful to avoid cases where a documentation block would otherwise have to be duplicated or it can be used to extend the documentation of an inherited member.

The link object can point to a member (of a class, file or group), a class, a namespace, a group, a page, or a file (checked in that order). Note that if the object pointed to is a member (function, variable, typedef, etc), the compound (class, file, or group) containing it should also be documented for the copying to work.

To copy the documentation for a member of a class one can, for instance, put the following in the documentation:


<pre><code>  /*! @copydoc MyClass::myfunction()
   *  More documentation.
   */
</code></pre>


if the member is overloaded, you should specify the argument types explicitly (without spaces!), like in the following:


<pre><code>  //! @copydoc MyClass::myfunction(type1,type2)
</code></pre>


Qualified names are only needed if the context in which the documentation block is found requires them.

The <code>\\copydoc</code> command can be used recursively, but cycles in the <code>\\copydoc</code> relation will be broken and flagged as an error.

Note that <code>\\copydoc foo()</code> is roughly equivalent to doing:


<pre><code>  \brief \copybrief foo()
  \details \copydetails foo()
</code></pre>


See <a href="#cmdcopybrief">\\copybrief</a> and <a href="#cmdcopydetails">\\copydetails</a> for copying only the brief or detailed part of the comment block.

<hr/>


## \\copybrief &lt;link-object&gt; {#cmdcopybrief}


Works in a similar way as <a href="#cmdcopydoc">\\copydoc</a> but will only copy the brief description, not the detailed documentation.

<hr/>


## \\copydetails &lt;link-object&gt; {#cmdcopydetails}


Works in a similar way as <a href="#cmdcopydoc">\\copydoc</a> but will only copy the detailed documentation, not the brief description.

<hr/>


## \\docbookonly {#cmddocbookonly}


Starts a block of text that only will be verbatim included in the generated DocBook documentation and tagged with <code>&lt;docbookonly&gt;</code> in the generated XML output. The block ends with a <a href="#cmdenddocbookonly">\\enddocbookonly</a> command.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdmanonly">\manonly</a>, <a href="#cmdlatexonly">\latexonly</a>, <a href="#cmdrtfonly">\rtfonly</a>, <a href="#cmdxmlonly">\xmlonly</a>, <a href="#cmdhtmlonly">\htmlonly</a> and <a href="#cmddocbookinclude">\docbookinclude</a>.
</dd>
</dl>


<hr/>


## \\dot \["caption"\] \[&lt;sizeindication&gt;=&lt;size&gt;\] {#cmddot}


Starts a text fragment which should contain a valid description of a dot graph. The text fragment ends with <a href="#cmdenddot">\\enddot</a>. Doxygen will pass the text on to dot and include the resulting image (and image map) into the output.

The first argument is optional and can be used to specify the caption that is displayed below the image. This argument has to be specified between quotes even if it does not contain any spaces. The quotes are stripped before the caption is displayed.

The second argument is also optional and can be used to specify the width or height of the image. For a description of the possibilities see the paragraph <a href="#image_sizeindicator">Size indication</a> with the <a href="#cmdimage">\\image</a> command.

The nodes of a graph can be made clickable by using the URL attribute. By using the command <a href="#cmdref">\\ref</a> inside the URL value you can conveniently link to an item inside Doxygen. Here is an example:

:::info
usage of this command requires that <a href="/web-doxygen/docs/pages/config/#cfg_have_dot">HAVE\_DOT</a> is set to <code>YES</code>
:::


:::info
Doxygen creates a temporary file that is automatically removed unless the <a href="/web-doxygen/docs/pages/config/#cfg_dot_cleanup">DOT\_CLEANUP</a> tag is set to <code>NO</code>.
:::


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! class B */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">B {};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! class C */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">C {};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/*! \mainpage</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  Class relations expressed via an inline dot graph:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \dot</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  digraph example {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *      node [shape=record, fontname=Helvetica, fontsize=10];</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *      b [ label="class B" URL="\ref B"];</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *      c [ label="class C" URL="\ref C"];</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *      b -&gt; c [ arrowhead="open", style="dashed" ];</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \enddot</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  Note that the classes in the above graph are clickable</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  (in the HTML output).</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>

</div>


<hr/>


## \\emoji "name" {#cmdemoji}


This command will produce an emoji character given its name.

The supported names are the ones also supported by GitHub and listed here <a href="https://gist.github.com/rxaviers/7360908">https://gist.github.com/rxaviers/7360908</a>

You can use the name with or without colons, i.e. <code>\\emoji smile</code> is the same as writing <code>\\emoji :smile:</code>. When an emoji is not supported the name with by places in the text with in between colons, i.e. <code>\\emoji unsupported</code> will produce <code>:unsupported:</code> in the output. Doxygen will also give a warning message.

See also the <a href="/web-doxygen/docs/pages/emojisup">emoji support page</a> for details.

<hr/>


## \\msc \["caption"\] \[&lt;sizeindication&gt;=&lt;size&gt;\] {#cmdmsc}


Starts a text fragment which should contain a valid description of a message sequence chart. See <a href="https://www.mcternan.me.uk/mscgen/">https://www.mcternan.me.uk/mscgen/</a> for examples. The text fragment ends with <a href="#cmdendmsc">\\endmsc</a>.

The first argument is optional and can be used to specify the caption that is displayed below the image. This argument has to be specified between quotes even if it does not contain any spaces. The quotes are stripped before the caption is displayed.

The second argument is also optional and can be used to specify the width or height of the image. For a description of the possibilities see the paragraph <a href="#image_sizeindicator">Size indication</a> with the <a href="#cmdimage">\\image</a> command.

:::info
The text fragment should only include the part of the message sequence chart that is within the <code>msc {...}</code> block (this is different from <a href="#cmdmscfile">\\mscfile</a>).
:::


:::info
mscgen is now built in into Doxygen
:::


:::info
Doxygen creates a temporary file that is automatically removed unless the <a href="/web-doxygen/docs/pages/config/#cfg_dot_cleanup">DOT\_CLEANUP</a> tag is set to <code>NO</code>.
:::


Here is an example of the use of the <code>\\msc</code> command.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** Sender class. Can be used to send a command to the server.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  The receiver will acknowledge the command by calling Ack().</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \msc</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *    Sender,Receiver;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *    Sender-&gt;Receiver [label="Command()", URL="\ref Receiver::Command()"];</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *    Sender&lt;-Receiver [label="Ack()", URL="\ref Ack()", ID="1"];</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \endmsc</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">Sender</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">public</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    /** Acknowledgment from server */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> Ack(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ok);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** Receiver class. Can be used to receive and execute commands.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  After execution of a command, the receiver will send an acknowledgment</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \msc</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *    Receiver,Sender;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *    Receiver&lt;-Sender [label="Command()", URL="\ref Command()"];</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *    Receiver-&gt;Sender [label="Ack()", URL="\ref Sender::Ack()", ID="1"];</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \endmsc</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">Receiver</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">public</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    /** Executable a command on the server */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> Command(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> commandId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdmscfile">\mscfile</a>.
</dd>
</dl>


<hr/>


## \\startuml \['{'option\[,option\]'}'\] \["caption"\] \[&lt;sizeindication&gt;=&lt;size&gt;\] {#cmdstartuml}


Starts a text fragment which should contain a valid description of a PlantUML diagram. See <a href="https://plantuml.com/">https://plantuml.com/</a> for examples. The text fragment ends with <a href="#cmdenduml">\\enduml</a>.

:::info
You need to install Java and the PlantUML's jar file, if you want to use this command. When using PlantUML in <code>{\LaTeX}</code> you have to download some more <code>jar</code> files, for details see the PlantUML documentation. This also is valid for the <code>&lt;engine&gt;</code>s <code>latex</code> and <code>math</code>. The location of the PlantUML file should be specified using <a href="/web-doxygen/docs/pages/config/#cfg_plantuml_jar_path">PLANTUML\_JAR\_PATH</a>. The other jar files should also reside in this directory.
:::


:::info
The use of the <code>&lt;engine&gt;</code> <code>ditaa</code> is not possible in <code>{\LaTeX}</code> as PlantUML only supports the <code>png</code> format and Doxygen requires, temporary, <code>eps</code> output.
:::


Not all diagrams can be created with the PlantUML <code>@startuml</code> command but need another PlantUML <code>@start...</code> command. This will look like <code>@start&lt;engine&gt;</code> where currently supported are the following <code>&lt;engine&gt;</code>s: <code>uml</code>, <code>bpm</code>, <code>wire</code>, <code>dot</code>, <code>ditaa</code>, <code>salt</code>, <code>math</code>, <code>latex</code>, <code>gantt</code>, <code>mindmap</code>, <code>wbs</code>, <code>yaml</code>, <code>creole</code>, <code>json</code>, <code>flow</code>, <code>board</code>, <code>git</code>, <code>hcl</code>, <code>regex</code>, <code>ebnf</code>, <code>files</code>, <code>chen</code> and <code>chronology</code>. By default the <code>&lt;engine&gt;</code> is <code>uml</code>. The <code>&lt;engine&gt;</code> can be specified as an option. Also the file to write the resulting image to can be specified by means of an option, see the description of the first (optional) argument for details. Of course only one <code>&lt;engine&gt;</code> can be specified and also the filename can only be specified once.

The first argument is optional and is for compatibility with running PlantUML as a preprocessing step before running Doxygen, you can also add the name of the image file after <code>\\startuml</code> and inside curly brackets as option, i.e.


<pre><code>  @startuml{myimage.png} "Image Caption" width=5cm
  Alice -&gt; Bob : Hello
  @enduml
</code></pre>


When the name of the image is specified, Doxygen will generate an image with that name. Without the name Doxygen will choose a name automatically.

The second argument is optional and can be used to specify the caption that is displayed below the image. This argument has to be specified between quotes even if it does not contain any spaces. The quotes are stripped before the caption is displayed.

The third argument is also optional and can be used to specify the width or height of the image. For a description of the possibilities see the paragraph <a href="#image_sizeindicator">Size indication</a> with the <a href="#cmdimage">\\image</a> command.

:::info
Doxygen does not support the Plantuml commands like <code>@startjson</code>, by design, directly but the support can be accomplished, by the user, by adding to the Doxygen settings file:


<pre><code>  ALIASES += startjson=@startuml{json}
  ALIASES += endjson=@enduml
</code></pre>
:::


:::info
Doxygen creates a temporary file that is automatically removed unless the <a href="/web-doxygen/docs/pages/config/#cfg_dot_cleanup">DOT\_CLEANUP</a> tag is set to <code>NO</code>.
:::


Here is an example of the use of the <code>\\startuml</code> command.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** Sender class. Can be used to send a command to the server.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  The receiver will acknowledge the command by calling Ack().</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \startuml</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *    Sender-&gt;Receiver  : Command()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *    Sender&lt;--Receiver : Ack()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \enduml</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">Sender</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">public</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    /** Acknowledgment from server */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> Ack(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ok);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** Receiver class. Can be used to receive and execute commands.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  After execution of a command, the receiver will send an acknowledgment</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \startuml</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *    Receiver&lt;-Sender  : Command()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *    Receiver--&gt;Sender : Ack()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  \enduml</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">Receiver</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">public</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    /** Executable a command on the server */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> Command(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> commandId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


<hr/>


## \\dotfile &lt;file&gt; \["caption"\] \[&lt;sizeindication&gt;=&lt;size&gt;\] {#cmddotfile}


Inserts an image generated by dot from &lt;file&gt; into the documentation.

The first argument specifies the file name of the image. Doxygen will look for files in the paths (or files) that you specified after the <a href="/web-doxygen/docs/pages/config/#cfg_dotfile_dirs">DOTFILE\_DIRS</a> tag. If the dot file is found it will be used as an input file to the dot tool. The resulting image will be put into the correct output directory. If the dot file name contains spaces you'll have to put quotes ("...") around it.

The second argument is optional and can be used to specify the caption that is displayed below the image. This argument has to be specified between quotes even if it does not contain any spaces. The quotes are stripped before the caption is displayed.

The third argument is also optional and can be used to specify the width or height of the image. For a description of the possibilities see the paragraph <a href="#image_sizeindicator">Size indication</a> with the <a href="#cmdimage">\\image</a> command.

:::info
usage of this command requires that <a href="/web-doxygen/docs/pages/config/#cfg_have_dot">HAVE\_DOT</a> is set to <code>YES</code>
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmddot">\dot</a>.
</dd>
</dl>


<hr/>


## \\mscfile &lt;file&gt; \["caption"\] \[&lt;sizeindication&gt;=&lt;size&gt;\] {#cmdmscfile}


Inserts an image generated by mscgen from &lt;file&gt; into the documentation. See <a href="https://www.mcternan.me.uk/mscgen/">https://www.mcternan.me.uk/mscgen/</a> for examples.

The first argument specifies the file name of the image. Doxygen will look for files in the paths (or files) that you specified after the <a href="/web-doxygen/docs/pages/config/#cfg_mscfile_dirs">MSCFILE\_DIRS</a> tag. If the msc file is found it will be used as an input file to the built in mscgen tool. The resulting image will be put into the correct output directory. If the msc file name contains spaces you'll have to put quotes ("...") around it.

The second argument is optional and can be used to specify the caption that is displayed below the image. This argument has to be specified between quotes even if it does not contain any spaces. The quotes are stripped before the caption is displayed.

The third argument is also optional and can be used to specify the width or height of the image. For a description of the possibilities see the paragraph <a href="#image_sizeindicator">Size indication</a> with the <a href="#cmdimage">\\image</a> command.

:::info
The text fragment should include the part message of the sequence chart as well as the starting <code>msc {</code> and ending <code>}</code> (this is different from <a href="#cmdmsc">\\msc</a>).
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdmsc">\msc</a>.
</dd>
</dl>


<hr/>


## \\diafile &lt;file&gt; \["caption"\] \[&lt;sizeindication&gt;=&lt;size&gt;\] {#cmddiafile}


Inserts an image made in dia from &lt;file&gt; into the documentation.

The first argument specifies the file name of the image. Doxygen will look for files in the paths (or files) that you specified after the <a href="/web-doxygen/docs/pages/config/#cfg_diafile_dirs">DIAFILE\_DIRS</a> tag. If the dia file is found it will be used as an input file dia. The resulting image will be put into the correct output directory. If the dia file name contains spaces you'll have to put quotes ("...") around it.

The second argument is optional and can be used to specify the caption that is displayed below the image. This argument has to be specified between quotes even if it does not contain any spaces. The quotes are stripped before the caption is displayed.

The third argument is also optional and can be used to specify the width or height of the image. For a description of the possibilities see the paragraph <a href="#image_sizeindicator">Size indication</a> with the <a href="#cmdimage">\\image</a> command.

<hr/>


## \\doxyconfig &lt;config\_option&gt; {#cmddoxyconfig}


Displays the value of the configuration option <code>&lt;config\_option&gt;</code> as used in Doxygen's configuration file that is in use when this command is processed.

<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
When creating this manual the following:


<pre><code>  ... Project name = \doxyconfig PROJECT_NAME ...
</code></pre>


gives:
<br/>
 ... Project name = Manual ...
</dd>
</dl>


<hr/>


## \\e &lt;word&gt; {#cmde}


Displays the argument &lt;word&gt; in italics. Use this command to emphasize words.

<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
Typing:


<pre><code>  ... this is a \e really good example ...
</code></pre>


will result in the following text:
<br/>

<br/>
 ... this is a <em>really</em> good example ...
</dd>
</dl>


Equivalent to <a href="#cmda">\\a</a> and <a href="#cmdem">\\em</a>. To emphasize multiple words use <a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_EM">&lt;em&gt;</a>multiple words<a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_endEM">&lt;/em&gt;</a>.

<hr/>


## \\em &lt;word&gt; {#cmdem}


Displays the argument &lt;word&gt; in italics. Use this command to emphasize words.

<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
Typing:


<pre><code>  ... this is a \em really good example ...
</code></pre>


will result in the following text:
<br/>

<br/>
 ... this is a <em>really</em> good example ...
</dd>
</dl>


Equivalent to <a href="#cmda">\\a</a> and <a href="#cmde">\\e</a>. To emphasize multiple words use <a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_EM">&lt;em&gt;</a>multiple words<a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_endEM">&lt;/em&gt;</a>.

<hr/>


## \\endcode {#cmdendcode}


Ends a block of code.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdcode">\code</a>
</dd>
</dl>


<hr/>


## \\enddocbookonly {#cmdenddocbookonly}


Ends a block of text that was started with a <a href="#cmddocbookonly">\\docbookonly</a> command.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmddocbookonly">\docbookonly</a>.
</dd>
</dl>


<hr/>


## \\enddot {#cmdenddot}


Ends a block that was started with <a href="#cmddot">\\dot</a>.

<hr/>


## \\endmsc {#cmdendmsc}


Ends a block that was started with <a href="#cmdmsc">\\msc</a>.

<hr/>


## \\enduml {#cmdenduml}


Ends a block that was started with <a href="#cmdstartuml">\\startuml</a>.

<hr/>


## \\plantumlfile &lt;file&gt; \["caption"\] \[&lt;sizeindication&gt;=&lt;size&gt;\] {#cmdplantumlfile}


Inserts an image made in PlantUml from &lt;file&gt; into the documentation.

The first argument specifies the file name of the image. Doxygen will look for files in the paths (or files) that you specified after the <a href="/web-doxygen/docs/pages/config/#cfg_plantumlfile_dirs">PLANTUMLFILE\_DIRS</a> tag. If the plantuml file is found it will be used as an input file for the plantuml program. The resulting image will be put into the correct output directory. If the plantuml file name contains spaces you'll have to put quotes ("...") around it.

The second argument is optional and can be used to specify the caption that is displayed below the image. This argument has to be specified between quotes even if it does not contain any spaces. The quotes are stripped before the caption is displayed.

The third argument is also optional and can be used to specify the width or height of the image. For a description of the possibilities see the paragraph <a href="#image_sizeindicator">Size indication</a> with the <a href="#cmdimage">\\image</a> command.

<hr/>


## \\endhtmlonly {#cmdendhtmlonly}


Ends a block of text that was started with a <a href="#cmdhtmlonly">\\htmlonly</a> command.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdhtmlonly">\htmlonly</a>.
</dd>
</dl>


<hr/>


## \\endlatexonly {#cmdendlatexonly}


Ends a block of text that was started with a <a href="#cmdlatexonly">\\latexonly</a> command.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdlatexonly">\latexonly</a>.
</dd>
</dl>


<hr/>


## \\endmanonly {#cmdendmanonly}


Ends a block of text that was started with a <a href="#cmdmanonly">\\manonly</a> command.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdmanonly">\manonly</a>.
</dd>
</dl>


<hr/>


## \\endrtfonly {#cmdendrtfonly}


Ends a block of text that was started with a <a href="#cmdrtfonly">\\rtfonly</a> command.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdrtfonly">\rtfonly</a>.
</dd>
</dl>


<hr/>


## \\endverbatim {#cmdendverbatim}


Ends a block of text that was started with a <a href="#cmdverbatim">\\verbatim</a> command.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdverbatim">\verbatim</a>.
</dd>
</dl>


<hr/>


## \\endxmlonly {#cmdendxmlonly}


Ends a block of text that was started with a <a href="#cmdxmlonly">\\xmlonly</a> command.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdxmlonly">\xmlonly</a>.
</dd>
</dl>


<hr/>


## \\f$ {#cmdfdollar}


Marks the start and end of an in-text formula.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="/web-doxygen/docs/pages/formulas">formulas</a> for an example.
</dd>
</dl>


<hr/>


## \\f( {#cmdfrndopen}


Marks the start of an in-text formula, but contrary to <a href="#cmdfdollar">\\f$</a> it will not explicitly open the math-mode in <code>{\LaTeX}</code>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdfrndclose">\f)</a> and section <a href="/web-doxygen/docs/pages/formulas">formulas</a>.
</dd>
</dl>


<hr/>


## \\f) {#cmdfrndclose}


Marks the end of an in-text formula started with <a href="#cmdfrndopen">\\f(</a>.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdfrndopen">\f(</a> and section <a href="/web-doxygen/docs/pages/formulas">formulas</a>.
</dd>
</dl>


<hr/>


## \\f\[ {#cmdfbropen}


Marks the start of a long formula that is displayed centered on a separate line.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdfbrclose">\f]</a> and section <a href="/web-doxygen/docs/pages/formulas">formulas</a>.
</dd>
</dl>


<hr/>


## \\f\] {#cmdfbrclose}


Marks the end of a long formula that is displayed centered on a separate line.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdfbropen">\f[</a> and section <a href="/web-doxygen/docs/pages/formulas">formulas</a>.
</dd>
</dl>


<hr/>


## \\f{environment}{ {#cmdfcurlyopen}


Marks the start of a formula that is in a specific environment.

:::info
The second <code>{</code> is optional and is only to help editors (such as <code>Vim</code>) to do proper syntax highlighting by making the number of opening and closing braces the same.
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdfcurlyclose">\f}</a> and section <a href="/web-doxygen/docs/pages/formulas">formulas</a>.
</dd>
</dl>


<hr/>


## \\f} {#cmdfcurlyclose}


Marks the end of a formula that is in a specific environment.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdfcurlyopen">\f{</a> and section <a href="/web-doxygen/docs/pages/formulas">formulas</a>.
</dd>
</dl>


<hr/>


## \\htmlonly\['\[block\]'\] {#cmdhtmlonly}


Starts a block of text that only will be verbatim included in the generated HTML documentation and tagged with <code>&lt;htmlonly&gt;</code> in the generated XML output. The block ends with a <a href="#cmdendhtmlonly">\\endhtmlonly</a> command.

This command can be used to include HTML code that is too complex for Doxygen (i.e. applets, java-scripts, and HTML tags that require specific attributes).

Normally the contents between <a href="#cmdhtmlonly">\\htmlonly</a> and <a href="#cmdendhtmlonly">\\endhtmlonly</a> is inserted as-is. When you want to insert a HTML fragment that has block scope like a table or list which should appear outside &lt;p&gt;..&lt;/p&gt;, this can lead to invalid HTML. You can use <code>\\htmlonly\[block\]</code> to make Doxygen end the current paragraph and restart it after <code>\\endhtmlonly</code>.

:::info
environment variables (like $(HOME) ) are resolved inside a HTML-only block.
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
section <a href="#cmdmanonly">\manonly</a>, <a href="#cmdlatexonly">\latexonly</a>, <a href="#cmdrtfonly">\rtfonly</a>, <a href="#cmdxmlonly">\xmlonly</a>, <a href="#cmddocbookonly">\docbookonly</a>, and <a href="#cmdhtmlinclude">\htmlinclude</a>.
</dd>
</dl>


<hr/>


## \\image\['{'option\[,option\]'}'\] &lt;format&gt; &lt;file&gt; \["caption"\] \[&lt;sizeindication&gt;=&lt;size&gt;\] {#cmdimage}


Inserts an image into the documentation. This command is format specific, so if you want to insert an image for more than one format you'll have to repeat this command for each format.

The first argument specifies the output format in which the image should be embedded. Currently, the following values are supported: <code>html</code>, <code>latex</code>, <code>docbook</code>, <code>rtf</code> and <code>xml</code>.

The second argument specifies the file name of the image. Doxygen will look for files in the paths (or files) that you specified after the <a href="/web-doxygen/docs/pages/config/#cfg_image_path">IMAGE\_PATH</a> tag. If the image is found it will be copied to the correct output directory. If the image name contains spaces you'll have to put quotes ("...") around the name. You can also specify an absolute URL instead of a file name, but then Doxygen does not copy the image nor check its existence.

The third argument is optional and can be used to specify the caption that is displayed below the image. This argument has to be specified on a single line and between quotes even if it does not contain any spaces. The quotes are stripped before the caption is displayed.

The fourth argument is also optional and can be used to specify the width or height of the image. This can be useful for <code>{\LaTeX}</code> or DocBook output (i.e. format=<code>latex</code> or format=<code>docbook</code>). <a id="image_sizeindicator"></a>

<dl class="doxySectionUser">
<dt>Size indication</dt>
<dd>
The <code>sizeindication</code> can specify the width or height to be used (or a combination). The size specifier in <code>{\LaTeX}</code> (for example <code>10cm</code> or <code>4in</code> or a symbolic width like <code>\textwidth</code>).
</dd>
</dl>


Currently only the options <code>inline</code> and <code>anchor</code> are supported. In case the option <code>inline</code> is specified the image is placed "in the line", when a caption is present it is shown in HTML as tooltip (ignored for the other formats). For the <code>anchor</code> option the syntax is: <code>anchor:&lt;anchorId&gt;</code>.

Here is example of a comment block:


<pre><code>  /*! Here is a snapshot of my new application:
   *  \image html application.jpg
   *  \image latex application.eps "My application" width=10cm
   */
</code></pre>


And this is an example of how the relevant part of the configuration file may look:


<pre><code>  IMAGE_PATH     = my_image_dir
</code></pre>


:::warning
The image format for HTML is limited to what your browser supports.
<br/>
For <code>{\LaTeX}</code>, the image format must be supported by the <code>{\LaTeX}</code> <code>\\includegraphics</code> command i.e. Encapsulated PostScript (eps), Portable network graphics (png), Joint photographic experts group (jpg / jpeg). 
<br/>

<br/>
 Doxygen does not check if the image is in the correct format. So <em>you</em> have to make sure this is the case!
:::


<hr/>


## \\latexonly {#cmdlatexonly}


Starts a block of text that only will be verbatim included in the generated <code>{\LaTeX}</code> documentation and tagged with <code>&lt;latexonly&gt;</code> in the generated XML output. The block ends with a <a href="#cmdendlatexonly">\\endlatexonly</a> command.

This command can be used to include <code>{\LaTeX}</code> code that is too complex for Doxygen (i.e. images, formulas, special characters). You can use the <a href="#cmdhtmlonly">\\htmlonly</a> and <a href="#cmdendhtmlonly">\\endhtmlonly</a> pair to provide a proper HTML alternative.

<b>Note:</b> environment variables (like $(HOME) ) are resolved inside a <code>{\LaTeX}</code>-only block.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
sections <a href="#cmdrtfonly">\rtfonly</a>, <a href="#cmdxmlonly">\xmlonly</a>, <a href="#cmdmanonly">\manonly</a>, <a href="#cmdhtmlonly">\htmlonly</a>, <a href="#cmddocbookonly">\docbookonly</a>, and <a href="#cmdlatexinclude">\latexinclude</a>.
</dd>
</dl>


<hr/>


## \\manonly {#cmdmanonly}


Starts a block of text that only will be verbatim included in the generated MAN documentation and tagged with <code>&lt;manonly&gt;</code> in the generated XML output. The block ends with a <a href="#cmdendmanonly">\\endmanonly</a> command.

This command can be used to include groff code directly into MAN pages. You can use the <a href="#cmdhtmlonly">\\htmlonly</a> and <a href="#cmdendhtmlonly">\\endhtmlonly</a> and <a href="#cmdlatexonly">\\latexonly</a> and <a href="#cmdendlatexonly">\\endlatexonly</a> pairs to provide proper HTML and <code>{\LaTeX}</code> alternatives.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
sections <a href="#cmdhtmlonly">\htmlonly</a>, <a href="#cmdxmlonly">\xmlonly</a>, <a href="#cmdrtfonly">\rtfonly</a>, <a href="#cmdlatexonly">\latexonly</a>, <a href="#cmddocbookonly">\docbookonly</a> and <a href="#cmdmaninclude">\maninclude</a>.
</dd>
</dl>


<hr/>


## \\li { item-description } {#cmdli}


This command has one argument that continues until the first blank line or until another <code>\\li</code> is encountered. The command can be used to generate a simple, not nested list of arguments. Each argument should start with a <code>\\li</code> command.

<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
Typing:


<pre><code>  \li \c AlignLeft left alignment.
  \li \c AlignCenter center alignment.
  \li \c AlignRight right alignment

  No other types of alignment are supported.
</code></pre>


will result in the following text:
<br/>

<br/>

<ul class="doxyList ">
<li><code>AlignLeft</code> left alignment.</li>
<li><code>AlignCenter</code> center alignment.</li>
<li><code>AlignRight</code> right alignment</li>
</ul>

<br/>
 No other types of alignment are supported.
</dd>
</dl>


<dl class="doxySectionUser">
<dt>Note:</dt>
<dd>
For nested lists, HTML commands should be used.
</dd>
</dl>


Equivalent to <a href="#cmdarg">\\arg</a>

<hr/>


## \\n {#cmdn}


Forces a new line. Equivalent to <a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_BR">&lt;br&gt;</a> and inspired by the <code>printf</code> function.

<hr/>


## \\p &lt;word&gt; {#cmdp}


Displays the parameter &lt;word&gt; using a typewriter font. You can use this command to refer to member function parameters in the running text.

<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<pre><code>  ... the \p x and \p y coordinates are used to ...
</code></pre>


This will result in the following text:
<br/>

<br/>
 ... the <code>x</code> and <code>y</code> coordinates are used to ...
</dd>
</dl>


Equivalent to <a href="#cmdc">\\c</a>. To have multiple words in typewriter font use <a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_TT">&lt;tt&gt;</a>multiple words<a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_endTT">&lt;/tt&gt;</a>.

<hr/>


## \\rtfonly {#cmdrtfonly}


Starts a block of text that only will be verbatim included in the generated RTF documentation and tagged with <code>&lt;rtfonly&gt;</code> in the generated XML output. The block ends with a <a href="#cmdendrtfonly">\\endrtfonly</a> command.

This command can be used to include RTF code that is too complex for Doxygen.

<b>Note:</b> environment variables (like $(HOME) ) are resolved inside a RTF-only block.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
sections <a href="#cmdmanonly">\manonly</a>, <a href="#cmdxmlonly">\xmlonly</a>, <a href="#cmdlatexonly">\latexonly</a>, <a href="#cmdhtmlonly">\htmlonly</a>, <a href="#cmddocbookonly">\docbookonly</a> and <a href="#cmdrtfinclude">\rtfinclude</a>.
</dd>
</dl>


<hr/>


## \\verbatim {#cmdverbatim}


Starts a block of text that will be verbatim included in the documentation. The block should end with a <a href="#cmdendverbatim">\\endverbatim</a> command. All commands are disabled in a verbatim block.

:::warning
Make sure you include a <a href="#cmdendverbatim">\\endverbatim</a> command for each <code>\\verbatim</code> command or the parser will get confused!
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
sections <a href="#cmdcode">\code</a>, <a href="#cmdendverbatim">\endverbatim</a> and <a href="#cmdverbinclude">\verbinclude</a>.
</dd>
</dl>


<hr/>


## \\xmlonly {#cmdxmlonly}


Starts a block of text that only will be verbatim included in the generated XML output. The block ends with a <a href="#cmdendxmlonly">\\endxmlonly</a> command.

This command can be used to include custom XML tags.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
sections <a href="#cmdmanonly">\manonly</a>, <a href="#cmdrtfonly">\rtfonly</a>, <a href="#cmdlatexonly">\latexonly</a>, <a href="#cmdhtmlonly">\htmlonly</a>, and <a href="#cmddocbookonly">\docbookonly</a>.
</dd>
</dl>


<hr/>


## \\\\ {#cmdbackslash}


This command writes a backslash character (<code>\\</code>) to the output. The backslash has to be escaped in some cases because Doxygen uses it to detect commands.

<hr/>


## \\@ {#cmdat}


This command writes an at-sign (<code>@</code>) to the output. The at-sign has to be escaped in some cases because Doxygen uses it to detect Javadoc commands.

<hr/>


## \\\~\[LanguageId\] {#cmdtilde}


This command enables/disables a language specific filter. This can be used to put documentation for different language into one comment block and use the <a href="/web-doxygen/docs/pages/config/#cfg_output_language">OUTPUT\_LANGUAGE</a> tag to filter out only a specific language. Use <code>\\\~language\_id</code> to enable output for a specific language only and <code>\\\~</code> to enable output for all languages (this is also the default mode).

Example:


<pre><code>/*! \~english This is English \~dutch Dit is Nederlands \~german Dies ist
    Deutsch. \~ output for all languages.
 */
</code></pre>


<hr/>


## \\&amp; {#cmdamp}


This command writes the <code>&amp;</code> character to the output. This character has to be escaped because it has a special meaning in HTML.

<hr/>


## \\$ {#cmddollar}


This command writes the <code>$</code> character to the output. This character has to be escaped in some cases, because it is used to expand environment variables.

<hr/>


## \\# {#cmdhash}


This command writes the <code>#</code> character to the output. This character has to be escaped in some cases, because it is used to refer to documented entities.

<hr/>


## \\&lt; {#cmdlt}


This command writes the <code>&lt;</code> character to the output. This character has to be escaped because it has a special meaning in HTML.

<hr/>


## \\&gt; {#cmdgt}


This command writes the <code>&gt;</code> character to the output. This character has to be escaped because it has a special meaning in HTML.

<hr/>


## \\% {#cmdperc}


This command writes the <code>%</code> character to the output. This character has to be escaped in some cases, because it is used to prevent auto-linking to a word that is also a documented class or struct.

<hr/>


## \\" {#cmdquot}


This command writes the <code>"</code> character to the output. This character has to be escaped in some cases, because it is used in pairs to indicate an unformatted text fragment.

<hr/>


## \\ {#cmdchardot}


This command writes a dot (<code>.</code>) to the output. This can be useful to prevent ending a brief description when <a href="/web-doxygen/docs/pages/config/#cfg_javadoc_autobrief">JAVADOC\_AUTOBRIEF</a> or <a href="/web-doxygen/docs/pages/config/#cfg_qt_autobrief">QT\_AUTOBRIEF</a> is enabled or to prevent starting a numbered list when the dot follows a number at the start of a line.

<hr/>


## \\? {#cmdquest}


This command writes a question mark (<code>?</code>) to the output. This can be useful to prevent ending a brief description when <a href="/web-doxygen/docs/pages/config/#cfg_javadoc_autobrief">JAVADOC\_AUTOBRIEF</a> or <a href="/web-doxygen/docs/pages/config/#cfg_qt_autobrief">QT\_AUTOBRIEF</a> is enabled.

<hr/>


## \\! {#cmdexclam}


This command writes a exclamation mark (<code>!</code>) to the output. This can be useful to prevent ending a brief description when <a href="/web-doxygen/docs/pages/config/#cfg_javadoc_autobrief">JAVADOC\_AUTOBRIEF</a> or <a href="/web-doxygen/docs/pages/config/#cfg_qt_autobrief">QT\_AUTOBRIEF</a> is enabled.

<hr/>


## \\= {#cmdeq}


This command writes an equal sign (<code>=</code>) to the output. This character sequence has to be escaped in some cases, because it is used in Markdown header processing.

<hr/>


## \\:: {#cmddcolon}


This command writes a double colon (<code>::</code>) to the output. This character sequence has to be escaped in some cases, because it is used to reference to documented entities.

<hr/>


## \\| {#cmdpipe}


This command writes a pipe symbol (|) to the output. This character has to be escaped in some cases, because it is used for Markdown tables.

<hr/>


## \\-- {#cmdndash}


This command writes two dashes (--) to the output. This allows writing two consecutive dashes to the output instead of one n-dash character (–).

<hr/>


## \\--- {#cmdmdash}


This command writes three dashes (---) to the output. This allows writing three consecutive dashes to the output instead of one m-dash character (—).

<hr/>

 
Go to the <a href="/docs/pages/htmlcmds/">next</a> section or return to the
 <a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
