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


<p>All commands in the documentation start with a backslash (<b>\</b>) or an at-sign (<b>@</b>). If you prefer you can replace all commands starting with a backslash below by their counterparts that start with an at-sign.</p>


<p>Some commands have one or more arguments. Each argument has a certain range:</p>


<ul class="doxyList ">
<li>If &lt;sharp&gt; braces are used the argument is a single word.</li>
<li>If (round) braces are used the argument extends until the end of the line on which the command was found.</li>
<li>If {curly} braces are used the argument extends until the next paragraph. Paragraphs are delimited by a blank line or by a section indicator. Note that {curly} braces are also used for command options, here the braces are mandatory and just 'normal' characters. The starting curly brace has to directly follow the command, so without whitespace.</li>
</ul>

<p>If in addition to the above argument specifiers [square] brackets are used the argument is optional, unless they are placed between quotes in that case they are a mandatory part of the command argument.</p>


<p>Here is an alphabetically sorted list of all commands with references to their documentation: <a id="showsecreflist"></a></p>



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

<p>The following subsections provide a list of all commands that are recognized by Doxygen. Unrecognized commands are treated as normal text.</p>

 <center>

##  ---  Structural indicators  ---  
 </center>

## \\addtogroup &lt;name&gt; \[(title)\] {#cmdaddtogroup}


<p>Defines a group just like <a href="#cmddefgroup">\defgroup</a>, but in contrast to that command using the same &lt;name&gt; more than once will not result in a warning, but rather one group with a merged documentation and the first title found in any of the commands.</p>


<p>The title is optional, so this command can also be used to add a number of entities to an existing group using <span class="doxyComputerOutput">@{</span> and <span class="doxyComputerOutput">@}</span> like this:</p>



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
<dd><p>page <a href="/web-doxygen/docs/pages/grouping">Grouping</a>, sections <a href="#cmddefgroup">\defgroup</a>, <a href="#cmdingroup">\ingroup</a>, and <a href="#cmdweakgroup">\weakgroup</a>.</p></dd>
</dl>


<hr/>


## \\callgraph {#cmdcallgraph}


<p>When this command is put in a comment block of a function or method and <a href="/web-doxygen/docs/pages/config/#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span>, then Doxygen will generate a call graph for that function (provided the implementation of the function or method calls other documented functions). The call graph will be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_call_graph">CALL_GRAPH</a>.</p>



:::info
<p>The completeness (and correctness) of the call graph depends on the Doxygen code parser which is not perfect.</p>
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdcallergraph">\callergraph</a>, section <a href="#cmdhidecallgraph">\hidecallgraph</a>, section <a href="#cmdhidecallergraph">\hidecallergraph</a> and option <a href="/web-doxygen/docs/pages/config/#cfg_call_graph">CALL_GRAPH</a></p></dd>
</dl>


<hr/>


## \\hidecallgraph {#cmdhidecallgraph}


<p>When this command is put in a comment block of a function or method and then Doxygen will not generate a call graph for that function. The call graph will not be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_call_graph">CALL_GRAPH</a>.</p>



:::info
<p>The completeness (and correctness) of the call graph depends on the Doxygen code parser which is not perfect.</p>
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdcallergraph">\callergraph</a>, section <a href="#cmdcallgraph">\callgraph</a>, section <a href="#cmdhidecallergraph">\hidecallergraph</a> and option <a href="/web-doxygen/docs/pages/config/#cfg_call_graph">CALL_GRAPH</a></p></dd>
</dl>


<hr/>


## \\callergraph {#cmdcallergraph}


<p>When this command is put in a comment block of a function or method and <a href="/web-doxygen/docs/pages/config/#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span>, then Doxygen will generate a caller graph for that function (provided the implementation of the function or method is called by other documented functions). The caller graph will be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_caller_graph">CALLER_GRAPH</a>.</p>



:::info
<p>The completeness (and correctness) of the caller graph depends on the Doxygen code parser which is not perfect.</p>
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdcallgraph">\callgraph</a>, section <a href="#cmdhidecallgraph">\hidecallgraph</a>, section <a href="#cmdhidecallergraph">\hidecallergraph</a> and option <a href="/web-doxygen/docs/pages/config/#cfg_caller_graph">CALLER_GRAPH</a></p></dd>
</dl>


<hr/>


## \\hidecallergraph {#cmdhidecallergraph}


<p>When this command is put in a comment block of a function or method and then Doxygen will not generate a caller graph for that function. The caller graph will not be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_caller_graph">CALLER_GRAPH</a>.</p>



:::info
<p>The completeness (and correctness) of the caller graph depends on the Doxygen code parser which is not perfect.</p>
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdcallergraph">\callergraph</a>, section <a href="#cmdcallgraph">\callgraph</a>, section <a href="#cmdhidecallgraph">\hidecallgraph</a> and option <a href="/web-doxygen/docs/pages/config/#cfg_caller_graph">CALLER_GRAPH</a></p></dd>
</dl>


<hr/>


## \\showrefby {#cmdshowrefby}


<p>When this command is put in a comment block of a function, method or variable, then Doxygen will generate an overview for that function, method, variable of the, documented, functions and methods that call / use it. The overview will be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_referenced_by_relation">REFERENCED_BY_RELATION</a>.</p>



:::info
<p>The completeness (and correctness) of the overview depends on the Doxygen code parser which is not perfect.</p>
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdshowrefs">\showrefs</a>, section <a href="#cmdhiderefby">\hiderefby</a>, section <a href="#cmdhiderefs">\hiderefs</a> and option <a href="/web-doxygen/docs/pages/config/#cfg_referenced_by_relation">REFERENCED_BY_RELATION</a></p></dd>
</dl>


<hr/>


## \\hiderefby {#cmdhiderefby}


<p>When this command is put in a comment block of a function, method or variable then Doxygen will not generate an overview for that function, method or variable of the functions and methods that call / use it. The overview will not be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_referenced_by_relation">REFERENCED_BY_RELATION</a>.</p>



:::info
<p>The completeness (and correctness) of the overview depends on the Doxygen code parser which is not perfect.</p>
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdshowrefs">\showrefs</a>, section <a href="#cmdshowrefby">\showrefby</a>, section <a href="#cmdhiderefs">\hiderefs</a> and option <a href="/web-doxygen/docs/pages/config/#cfg_referenced_by_relation">REFERENCED_BY_RELATION</a></p></dd>
</dl>


<hr/>


## \\showrefs {#cmdshowrefs}


<p>When this command is put in a comment block of a function or method, then Doxygen will generate an overview for that function or method of the functions and methods that call it. The overview will be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_references_relation">REFERENCES_RELATION</a>.</p>



:::info
<p>The completeness (and correctness) of the overview depends on the Doxygen code parser which is not perfect.</p>
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdshowrefby">\showrefby</a>, section <a href="#cmdhiderefby">\hiderefby</a>, section <a href="#cmdhiderefs">\hiderefs</a> and option <a href="/web-doxygen/docs/pages/config/#cfg_references_relation">REFERENCES_RELATION</a></p></dd>
</dl>


<hr/>


## \\hiderefs {#cmdhiderefs}


<p>When this command is put in a comment block of a function or method and then Doxygen will not generate an overview for that function or method of the functions and methods that call it. The overview will not be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_references_relation">REFERENCES_RELATION</a>.</p>



:::info
<p>The completeness (and correctness) of the overview depends on the Doxygen code parser which is not perfect.</p>
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdshowrefs">\showrefs</a>, section <a href="#cmdshowrefby">\showrefby</a>, section <a href="#cmdhiderefby">\hiderefby</a> and option <a href="/web-doxygen/docs/pages/config/#cfg_references_relation">REFERENCES_RELATION</a></p></dd>
</dl>


<hr/>


## \\showinlinesource {#cmdshowinlinesource}


<p>When this command is put in a comment block of a function, multi-line macro, enum or a list initialized variable then Doxygen will generate the inline source for that member. The inline source will be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_inline_sources">INLINE_SOURCES</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdhideinlinesource">\hideinlinesource</a>, option <a href="/web-doxygen/docs/pages/config/#cfg_inline_sources">INLINE_SOURCES</a></p></dd>
</dl>


<hr/>


## \\hideinlinesource {#cmdhideinlinesource}


<p>When this command is put in a comment block of a function, multi-line macro, enum or a list initialized variable then Doxygen will not generate the inline source for that member. The inline source will not be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_inline_sources">INLINE_SOURCES</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdshowinlinesource">\showinlinesource</a>, option <a href="/web-doxygen/docs/pages/config/#cfg_inline_sources">INLINE_SOURCES</a></p></dd>
</dl>


<hr/>


## \\includegraph {#cmdincludegraph}


<p>When this command is put in a comment block of a file then Doxygen will generate an include graph for that file. The include graph will be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_include_graph">INCLUDE_GRAPH</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdhideincludegraph">\hideincludegraph</a>, section <a href="#cmdincludedbygraph">\includedbygraph</a>, section <a href="#cmdhideincludedbygraph">\hideincludedbygraph</a> and option <a href="/web-doxygen/docs/pages/config/#cfg_include_graph">INCLUDE_GRAPH</a></p></dd>
</dl>


<hr/>


## \\hideincludegraph {#cmdhideincludegraph}


<p>When this command is put in a comment block of a file then Doxygen will not generate an include graph for that file. The include graph will not be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_include_graph">INCLUDE_GRAPH</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdincludegraph">\includegraph</a>, section <a href="#cmdincludedbygraph">\includedbygraph</a>, section <a href="#cmdhideincludedbygraph">\hideincludedbygraph</a> and option <a href="/web-doxygen/docs/pages/config/#cfg_include_graph">INCLUDE_GRAPH</a></p></dd>
</dl>


<hr/>


## \\includedbygraph {#cmdincludedbygraph}


<p>When this command is put in a comment block of an include file then Doxygen will generate an included by graph for that include file. The included by graph will be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_included_by_graph">INCLUDED_BY_GRAPH</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdhideincludedbygraph">\hideincludedbygraph</a>, section <a href="#cmdincludegraph">\ncludegraph</a>, section <a href="#cmdhideincludegraph">\hideincludegraph</a> and option <a href="/web-doxygen/docs/pages/config/#cfg_included_by_graph">INCLUDED_BY_GRAPH</a></p></dd>
</dl>


<hr/>


## \\hideincludedbygraph {#cmdhideincludedbygraph}


<p>When this command is put in a comment block of an include file then Doxygen will not generate an included by graph for that include file. The included by graph will not be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_included_by_graph">INCLUDED_BY_GRAPH</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdincludedbygraph">\includedbygraph</a>, section <a href="#cmdincludegraph">\ncludegraph</a>, section <a href="#cmdhideincludegraph">\hideincludegraph</a> and option <a href="/web-doxygen/docs/pages/config/#cfg_included_by_graph">INCLUDED_BY_GRAPH</a></p></dd>
</dl>


<hr/>


## \\directorygraph {#cmddirectorygraph}


<p>When this command is put in a comment block of a directory (see section <a href="#cmddir">\dir</a>) then Doxygen will generate a directory graph for that directory. The directory graph will be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_directory_graph">DIRECTORY_GRAPH</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdhidedirectorygraph">\hidedirectorygraph</a>, option <a href="/web-doxygen/docs/pages/config/#cfg_directory_graph">DIRECTORY_GRAPH</a></p></dd>
</dl>


<hr/>


## \\hidedirectorygraph {#cmdhidedirectorygraph}


<p>When this command is put in a comment block of a directory (see section <a href="#cmddir">\dir</a>) then Doxygen will not generate a directory graph for that directory. The directory graph will not be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_directory_graph">DIRECTORY_GRAPH</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmddirectorygraph">\directorygraph</a>, option <a href="/web-doxygen/docs/pages/config/#cfg_directory_graph">DIRECTORY_GRAPH</a></p></dd>
</dl>


<hr/>


## \\collaborationgraph {#cmdcollaborationgraph}


<p>When this command is put in a comment block of a class then Doxygen will generate a collaboration graph for that class. The collaboration graph will be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_collaboration_graph">COLLABORATION_GRAPH</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdhidecollaborationgraph">\hidecollaborationgraph</a>, option <a href="/web-doxygen/docs/pages/config/#cfg_collaboration_graph">COLLABORATION_GRAPH</a></p></dd>
</dl>


<hr/>


## \\hidecollaborationgraph {#cmdhidecollaborationgraph}


<p>When this command is put in a comment block of a class then Doxygen will not generate a collaboration graph for that class. The collaboration graph will not be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_collaboration_graph">COLLABORATION_GRAPH</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdcollaborationgraph">\collaborationgraph</a>, option <a href="/web-doxygen/docs/pages/config/#cfg_collaboration_graph">COLLABORATION_GRAPH</a></p></dd>
</dl>


<hr/>


## \\inheritancegraph\['{option}'\] {#cmdinheritancegraph}


<p>When this command is put in a comment block of a class then Doxygen will generate an inheritance graph for that class conforming the <span class="doxyComputerOutput">option</span>. The inheritance graph will be generated, conforming the <span class="doxyComputerOutput">option</span>, regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_class_graph">CLASS_GRAPH</a>. The possible values of <span class="doxyComputerOutput">option</span> are the same values as can be used with <a href="/web-doxygen/docs/pages/config/#cfg_class_graph">CLASS_GRAPH</a>. In case no <span class="doxyComputerOutput">option</span> is specified the value <span class="doxyComputerOutput">YES</span> is assumed.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdhideinheritancegraph">\hideinheritancegraph</a>, option <a href="/web-doxygen/docs/pages/config/#cfg_class_graph">CLASS_GRAPH</a></p></dd>
</dl>


<hr/>


## \\hideinheritancegraph {#cmdhideinheritancegraph}


<p>When this command is put in a comment block of a class then Doxygen will not generate an inheritance graph for that class. The inheritance graph will not be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_class_graph">CLASS_GRAPH</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdinheritancegraph">\inheritancegraph</a>, option <a href="/web-doxygen/docs/pages/config/#cfg_class_graph">CLASS_GRAPH</a></p></dd>
</dl>


<hr/>


## \\groupgraph {#cmdgroupgraph}


<p>When this command is put in a comment block of a <a href="#cmddefgroup">\defgroup</a> command then Doxygen will generate a group dependency graph for that group. The group graph will be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_group_graphs">GROUP_GRAPHS</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdhidegroupgraph">\hidegroupgraph</a>, option <a href="/web-doxygen/docs/pages/config/#cfg_group_graphs">GROUP_GRAPHS</a></p></dd>
</dl>


<hr/>


## \\hidegroupgraph {#cmdhidegroupgraph}


<p>When this command is put in a comment block of a <a href="#cmddefgroup">\defgroup</a> command then Doxygen will not generate a group dependency graph for that group. The group graph will not be generated regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_group_graphs">GROUP_GRAPHS</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdgroupgraph">\groupgraph</a>, option <a href="/web-doxygen/docs/pages/config/#cfg_group_graphs">GROUP_GRAPHS</a></p></dd>
</dl>


<hr/>


## \\showenumvalues {#cmdshowenumvalues}


<p>When this command is put in a comment block of an enum then doxygen will show the specified enum values for that enum, regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_show_enum_values">SHOW_ENUM_VALUES</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdhideenumvalues">\hideenumvalues</a>, option <a href="/web-doxygen/docs/pages/config/#cfg_show_enum_values">SHOW_ENUM_VALUES</a></p></dd>
</dl>


<hr/>


## \\hideenumvalues {#cmdhideenumvalues}


<p>When this command is put in a comment block of an enum then doxygen will not show the specified enum values for that enum, regardless of the value of <a href="/web-doxygen/docs/pages/config/#cfg_show_enum_values">SHOW_ENUM_VALUES</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdshowenumvalues">\showenumvalues</a>, option <a href="/web-doxygen/docs/pages/config/#cfg_show_enum_values">SHOW_ENUM_VALUES</a></p></dd>
</dl>


<hr/>


## \\qualifier &lt;label&gt; | "(text)" {#cmdqualifier}


<p>With this command it is possible to add custom qualifier labels to members and classes. These labels will be shown in the output in the same way as the automatically generated labels such as "static", "inline", and "final".</p>


<p>For instance to indicate that a function is only meant for testing purposes one could add <span class="doxyComputerOutput">\qualifier test</span></p>


<hr/>


## \\category &lt;name&gt; \[&lt;header-file&gt;\] \[&lt;header-name&gt;\] {#cmdcategory}


<p>For Objective-C only: Indicates that a comment block contains documentation for a class category with name &lt;name&gt;. The arguments are equal to the <a href="#cmdclass">\class</a> command.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdclass">\class</a>.</p></dd>
</dl>


<hr/>


## \\class &lt;name&gt; \[&lt;header-file&gt;\] \[&lt;header-name&gt;\] {#cmdclass}


<p>Indicates that a comment block contains documentation for a class with name &lt;name&gt;. Optionally a header file and a header name can be specified. If the header-file is specified, a link to a verbatim copy of the header will be included in the HTML documentation. The &lt;header-name&gt; argument can be used to overwrite the name of the link that is used in the class documentation to something other than &lt;header-file&gt;. This can be useful if the include name is not located on the default include path (like &lt;X11/X.h&gt;). With the &lt;header-name&gt; argument you can also specify how the include statement should look like, by adding either quotes or sharp brackets around the name. Sharp brackets are used if just the name is given. Note that the last two arguments can also be specified using the <a href="#cmdheaderfile">\headerfile</a> command.</p>


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


<p>Indicates that a comment block contains documentation for a C++20 concept with name &lt;name&gt;. See also the <a href="#cmdheaderfile">\headerfile</a> command to specify the header a user should be included to use the concept.</p>


<hr/>


## \\def &lt;name&gt; {#cmddef}


<p>Indicates that a comment block contains documentation for a <span class="doxyComputerOutput">#define</span> macro.</p>


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


<p>Indicates that a comment block contains documentation for a <a href="/web-doxygen/docs/pages/grouping/#topics">topics</a> of classes, modules, concepts, files or namespaces. This can be used to categorize symbols, and document those categories. You can also use groups as members of other groups, thus building a hierarchy of groups.</p>


<p>The &lt;name&gt; argument should be a single-word identifier.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>page <a href="/web-doxygen/docs/pages/grouping">Grouping</a>, sections <a href="#cmdingroup">\ingroup</a>, <a href="#cmdaddtogroup">\addtogroup</a>, and <a href="#cmdweakgroup">\weakgroup</a>.</p></dd>
</dl>


<hr/>


## \\dir \[&lt;path fragment&gt;\] {#cmddir}


<p>Indicates that a comment block contains documentation for a directory. The "path fragment" argument should include the directory name and enough of the path to be unique with respect to the other directories in the project. The <a href="/web-doxygen/docs/pages/config/#cfg_strip_from_path">STRIP_FROM_PATH</a> option determines what is stripped from the full path before it appears in the output.</p>


<hr/>


## \\enum &lt;name&gt; {#cmdenum}


<p>Indicates that a comment block contains documentation for an enumeration, with name &lt;name&gt;. If the enum is a member of a class and the documentation block is located outside the class definition, the scope of the class should be specified as well. If a comment block is located directly in front of an enum declaration, the <span class="doxyComputerOutput">\enum</span> comment may be omitted.</p>


<dl class="doxySectionUser">
<dt>Note:</dt>
<dd><p>The type of an anonymous enum cannot be documented, but the values of an anonymous enum can.</p></dd>
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


<p>Indicates that a comment block contains documentation for a source code example. The name of the source file is &lt;file-name&gt;. The contents of this file will be included in the documentation, just after the documentation contained in the comment block. You can add option <span class="doxyComputerOutput">{lineno}</span> to enable line numbers for the example if desired. All examples are placed in a list. The source code is scanned for documented members and classes. If any are found, the names are cross-referenced with the documentation. Source files or directories can be specified using the <a href="/web-doxygen/docs/pages/config/#cfg_example_path">EXAMPLE_PATH</a> tag of Doxygen's configuration file.</p>


<p>If &lt;file-name&gt; itself is not unique for the set of example files specified by the <a href="/web-doxygen/docs/pages/config/#cfg_example_path">EXAMPLE_PATH</a> tag, you can include part of the absolute path to disambiguate it.</p>


<p>If more than one source file is needed for the example, the <a href="#cmdinclude">\include</a> command can be used.</p>


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


<p>Where the example file <span class="doxyComputerOutput">example_test.cpp</span> looks as follows:</p>


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
<dd><p>section <a href="#cmdinclude">\include</a>.</p></dd>
</dl>


<hr/>


## \\endinternal {#cmdendinternal}


<p>This command ends a documentation fragment that was started with a <a href="#cmdinternal">\internal</a> command. The text between <a href="#cmdinternal">\internal</a> and <span class="doxyComputerOutput">\endinternal</span> will only be visible if <a href="/web-doxygen/docs/pages/config/#cfg_internal_docs">INTERNAL_DOCS</a> is set to <span class="doxyComputerOutput">YES</span>.</p>


<hr/>


## \\extends &lt;name&gt; {#cmdextends}


<p>This command can be used to manually indicate an inheritance relation, when the programming language does not support this concept natively (e.g. C).</p>


<p>The file <span class="doxyComputerOutput">manual.c</span> in the example directory shows how to use this command (see also <a href="#cmdmemberof">\memberof</a> for the complete file).</p>

 
  Click <a href="pathname:///examples/manual/html/struct_car.html">here</a>
  for the corresponding HTML documentation that is generated by Doxygen.
  

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdimplements">\implements</a> and section <a href="#cmdmemberof">\memberof</a></p></dd>
</dl>


<hr/>


## \\file \[&lt;name&gt;\] {#cmdfile}


<p>Indicates that a comment block contains documentation for a source or header file with name &lt;name&gt;. The file name may include (part of) the path if the file-name alone is not unique. If the file name is omitted (i.e. the line after <span class="doxyComputerOutput">\file</span> is left blank) then the documentation block that contains the <span class="doxyComputerOutput">\file</span> command will belong to the file it is located in.</p>



:::tip
<p>The documentation of global functions, variables, typedefs, and enums will only be included in the output if the file they are in is documented as well or if <a href="/web-doxygen/docs/pages/config/#cfg_extract_all">EXTRACT_ALL</a> is set to <span class="doxyComputerOutput">YES</span>.</p>
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
<p>In the above example <a href="/web-doxygen/docs/pages/config/#cfg_javadoc_autobrief">JAVADOC_AUTOBRIEF</a> has been set to <span class="doxyComputerOutput">YES</span> in the configuration file.</p>
:::


<hr/>


## \\fileinfo\['{'option'}'\] {#cmdfileinfo}


<p>Shows (part) of the file name in which this command is placed. The <span class="doxyComputerOutput">option</span> can be <span class="doxyComputerOutput">name</span>, <span class="doxyComputerOutput">extension</span>, <span class="doxyComputerOutput">filename</span>, <span class="doxyComputerOutput">directory</span> or, <span class="doxyComputerOutput">full</span>, with</p>


<ul class="doxyList ">
<li><span class="doxyComputerOutput">name</span> the name of the file without extension</li>
<li><span class="doxyComputerOutput">extension</span> the extension of the file</li>
<li><span class="doxyComputerOutput">filename</span> the filename i.e. <span class="doxyComputerOutput">name</span> plus <span class="doxyComputerOutput">extension</span></li>
<li><span class="doxyComputerOutput">directory</span> the directory of the given file</li>
<li><span class="doxyComputerOutput">full</span> the full path and filename of the given file.</li>
</ul>

<p>In case no option is specified the <span class="doxyComputerOutput">filename</span> is used unless <a href="/web-doxygen/docs/pages/config/#cfg_full_path_names">FULL_PATH_NAMES</a> is set to <span class="doxyComputerOutput">YES</span> in which case <span class="doxyComputerOutput">full</span> is used.</p>



:::info
<p>the command \fileinfo cannot be used as argument to the <a href="#cmdfile">\file</a> command</p>
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdlineinfo">\lineinfo</a></p></dd>
</dl>


<hr/>


## \\lineinfo {#cmdlineinfo}


<p>Shows the line number inside the file at which this command is placed.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdfileinfo">\fileinfo</a></p></dd>
</dl>


<hr/>


## \\fn (function declaration) {#cmdfn}


<p>Indicates that a comment block contains documentation for a function (either global or as a member of a class). This command is <em>only</em> needed if a comment block is <em>not</em> placed in front (or behind) the function declaration or definition.</p>


<p>If your comment block <em>is</em> in front of the function declaration or definition this command can (and to avoid redundancy should) be omitted.</p>


<p>A full function declaration including arguments should be specified after the <span class="doxyComputerOutput">\fn</span> command on a <em>single</em> line, since the argument ends at the end of the line!</p>


<p>This command is equivalent to <a href="#cmdvar">\var</a>, <a href="#cmdtypedef">\typedef</a>, and <a href="#cmdproperty">\property</a>.</p>



:::warning
<p>Do not use this command if it is not absolutely needed, since it will lead to duplication of information and thus to errors.</p>
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
<dd><p>sections <a href="#cmdvar">\var</a>, <a href="#cmdproperty">\property</a>, and <a href="#cmdtypedef">\typedef</a>.</p></dd>
</dl>


<hr/>


## \\headerfile &lt;header-file&gt; \[&lt;header-name&gt;\] {#cmdheaderfile}


<p>Intended to be used for class, struct, or union documentation, where the documentation is in front of the definition. The arguments of this command are the same as the second and third argument of <a href="#cmdclass">\class</a>. The &lt;header-file&gt; name refers to the file that should be included by the application to obtain the definition of the class, struct, or union. The &lt;header-name&gt; argument can be used to overwrite the name of the link that is used in the class documentation to something other than &lt;header-file&gt;. This can be useful if the include name is not located on the default include path (like &lt;X11/X.h&gt;).</p>


<p>With the &lt;header-name&gt; argument you can also specify how the include statement should look like, by adding either double quotes or sharp brackets around the name. By default sharp brackets are used if just the name is given.</p>


<p>If a pair of double quotes is given for either the &lt;header-file&gt; or &lt;header-name&gt; argument, the current file (in which the command was found) will be used but with quotes. So for a comment block with a <span class="doxyComputerOutput">\headerfile</span> command inside a file <span class="doxyComputerOutput">test.h</span>, the following three commands are equivalent:</p>



<pre><code>  \headerfile test.h "test.h"
  \headerfile test.h ""
  \headerfile ""
</code></pre>


<p>To get sharp brackets you do not need to specify anything, but if you want to be explicit you could use any of the following:</p>



<pre><code>  \headerfile test.h &lt;test.h&gt;
  \headerfile test.h &lt;&gt;
  \headerfile &lt;&gt;
</code></pre>


<p>To globally reverse the default include representation to local includes you can set <a href="/web-doxygen/docs/pages/config/#cfg_force_local_includes">FORCE_LOCAL_INCLUDES</a> to <span class="doxyComputerOutput">YES</span>.</p>


<p>To disable the include information altogether set <a href="/web-doxygen/docs/pages/config/#cfg_show_headerfile">SHOW_HEADERFILE</a> to <span class="doxyComputerOutput">NO</span>.</p>


<hr/>


## \\hideinitializer {#cmdhideinitializer}


<p>By default the value of a define and the initializer of a variable are displayed unless they are longer than 30 lines. By putting this command in a comment block of a define or variable, the initializer is always hidden. The maximum number of initialization lines can be changed by means of the configuration parameter <a href="/web-doxygen/docs/pages/config/#cfg_max_initializer_lines">MAX_INITIALIZER_LINES</a>, the default value is 30.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdshowinitializer">\showinitializer</a>.</p></dd>
</dl>


<hr/>


## \\idlexcept &lt;name&gt; {#cmdidlexcept}


<p>Indicates that a comment block contains documentation for a IDL exception with name &lt;name&gt;.</p>


<hr/>


## \\implements &lt;name&gt; {#cmdimplements}


<p>This command can be used to manually indicate an inheritance relation, when the programming language does not support this concept natively (e.g. C).</p>


<p>The file <span class="doxyComputerOutput">manual.c</span> in the example directory shows how to use this command (see also <a href="#cmdmemberof">\memberof</a> for the complete file).</p>

 
  Click <a href="pathname:///examples/manual/html/struct_car.html">here</a>
  for the corresponding HTML documentation that is generated by Doxygen.
  

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdextends">\extends</a> and section <a href="#cmdmemberof">\memberof</a></p></dd>
</dl>


<hr/>


## \\ingroup (&lt;groupname&gt; \[&lt;groupname&gt;\]\*) {#cmdingroup}


<p>If the <span class="doxyComputerOutput">\ingroup</span> command is placed in a comment block of a compound entity (like class, file or namespace), then it will be added to the group(s) identified by the <span class="doxyComputerOutput">&lt;groupname&gt;</span>(s). In case of members (like variable, functions, typedefs and enums) the member will be added only to one group (to avoid ambiguous linking targets in case a member is not documented in the context of its class, namespace or file, but only visible as part of a group).</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>page <a href="/web-doxygen/docs/pages/grouping">Grouping</a>, sections <a href="#cmddefgroup">\defgroup</a>, <a href="#cmdaddtogroup">\addtogroup</a>, and <a href="#cmdweakgroup">\weakgroup</a></p></dd>
</dl>


<hr/>


## \\interface &lt;name&gt; \[&lt;header-file&gt;\] \[&lt;header-name&gt;\] {#cmdinterface}


<p>Indicates that a comment block contains documentation for an interface with name &lt;name&gt;. The arguments are equal to the arguments of the <a href="#cmdclass">\class</a> command.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdclass">\class</a>.</p></dd>
</dl>


<hr/>


## \\internal {#cmdinternal}


<p>This command starts a documentation fragment that is meant for internal use only. The fragment naturally ends at the end of the comment block. You can also force the internal section to end earlier by using the <a href="#cmdendinternal">\endinternal</a> command.</p>


<p>If the <span class="doxyComputerOutput">\internal</span> command is put inside a section (see for example <a href="#cmdsection">\section</a>) all subsections after the command are considered to be internal as well. Only a new section at the same level will end the fragment that is considered internal.</p>


<p>You can use <a href="/web-doxygen/docs/pages/config/#cfg_internal_docs">INTERNAL_DOCS</a> in the configuration file to show (<span class="doxyComputerOutput">YES</span>) or hide (<span class="doxyComputerOutput">NO</span>) the internal documentation.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdendinternal">\endinternal</a>.</p></dd>
</dl>


<hr/>


## \\mainpage \[(title)\] {#cmdmainpage}


<p>If the <span class="doxyComputerOutput">\mainpage</span> command is placed in a comment block the block is used to customize the index page (in HTML) or the first chapter (in <code>{\LaTeX}</code>).</p>


<p>The title argument is optional and replaces the default title that Doxygen normally generates. If you do not want any title you can specify <span class="doxyComputerOutput">notitle</span> as the argument of <span class="doxyComputerOutput">\mainpage</span>.</p>


<p>Here is an example:</p>



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


<p>You can refer to the main page using: <span class="doxyComputerOutput"><a href="#cmdref">\ref</a> index</span>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdsection">\section</a>, section <a href="#cmdsubsection">\subsection</a>, and section <a href="#cmdpage">\page</a>.</p></dd>
</dl>


<hr/>


## \\memberof &lt;name&gt; {#cmdmemberof}


<p>This command makes a function a member of a class in a similar way as <a href="#cmdrelates">\relates</a> does, only with this command the function is represented as a real member of the class. This can be useful when the programming language does not support the concept of member functions natively (e.g. C).</p>


<p>It is also possible to use this command together with <a href="#cmdpublic">\public</a>, <a href="#cmdprotected">\protected</a> or <a href="#cmdprivate">\private</a>.</p>


<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<p>The file <span class="doxyComputerOutput">manual.c</span> in the example directory shows how to use this command:</p>


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
<dd><p>sections <a href="#cmdextends">\extends</a>, <a href="#cmdimplements">\implements</a>, <a href="#cmdpublic">\public</a>, <a href="#cmdprotected">\protected</a> and <a href="#cmdprivate">\private</a>.</p></dd>
</dl>


<hr/>


## \\module &lt;name&gt; {#cmdmodule}


<p>Indicates that a comment block contains documentation for a C++20 module with name &lt;name&gt;.</p>


<hr/>


## \\name \[(header)\] {#cmdname}


<p>This command turns a comment block into a header definition of a member group. The comment block should be followed by a <span class="doxyComputerOutput">@{</span> ... <span class="doxyComputerOutput">@}</span> block containing the members of the group.</p>


<p>See section <a href="/web-doxygen/docs/pages/grouping/#memgroup">Member Groups</a> for an example.</p>


<hr/>


## \\namespace &lt;name&gt; {#cmdnamespace}


<p>Indicates that a comment block contains documentation for a namespace with name &lt;name&gt;.</p>


<hr/>


## \\nosubgrouping {#cmdnosubgrouping}


<p>This command can be put in the documentation of a class. It can be used in combination with member grouping to avoid that Doxygen puts a member group as a subgroup of a Public/Protected/Private/... section.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>sections <a href="#cmdpublicsection">\publicsection</a>, <a href="#cmdprotectedsection">\protectedsection</a> and <a href="#cmdprivatesection">\privatesection</a>.</p></dd>
</dl>


<hr/>


## \\overload \[(function declaration)\] {#cmdoverload}


<p>This command can be used to generate the following standard text for an overloaded member function:</p>

<blockquote class="doxyBlockQuote">

<p>This is an overloaded member function, provided for convenience. It differs from the above function only in what argument(s) it accepts.</p>

</blockquote>

<p>If the documentation for the overloaded member function is not located in front of the function declaration or definition, the optional argument should be used to specify the correct declaration of the overloaded function. Of course when the <span class="doxyComputerOutput">\overload</span> command is directly in front of the overloaded member function and the optional argument is used this should also be the correct declaration of the overloaded function.</p>


<p>Any other documentation that is inside the documentation block will by appended after the generated message.</p>


<dl class="doxySectionUser">
<dt>Note 1:</dt>
<dd><p>You are responsible that there is indeed an earlier documented member that is overloaded by this one. To prevent that document reorders the documentation you should set <a href="/web-doxygen/docs/pages/config/#cfg_sort_member_docs">SORT_MEMBER_DOCS</a> to <span class="doxyComputerOutput">NO</span> in this case.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Note 2:</dt>
<dd><p>Only one <span class="doxyComputerOutput">\overload</span> command can be present in a comment block.</p></dd>
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


<p>Indicates that a comment block contains documentation for a Java package with name &lt;name&gt;.</p>


<hr/>


## \\page &lt;name&gt; (title) {#cmdpage}


<p>Indicates that a comment block contains a piece of documentation that is not directly related to one specific class, file or member. The HTML generator creates a page containing the documentation. The <code>{\LaTeX}</code> generator starts a new section in the chapter 'Page documentation'.</p>


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
<dd><p>The &lt;name&gt; argument consists of a combination of letters and number digits. If you wish to use upper case letters (e.g. <span class="doxyComputerOutput">MYPAGE1</span>), or mixed case letters (e.g. <span class="doxyComputerOutput">MyPage1</span>) in the &lt;name&gt; argument, you should set <a href="/web-doxygen/docs/pages/config/#cfg_case_sense_names">CASE_SENSE_NAMES</a> to <span class="doxyComputerOutput">YES</span>. However, this is advisable only if your file system is case sensitive. Otherwise (and for better portability) you should use all lower case letters (e.g. <span class="doxyComputerOutput">mypage1</span>) for &lt;name&gt; in all references to the page.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdsection">\section</a>, section <a href="#cmdsubsection">\subsection</a>, and section <a href="#cmdref">\ref</a>.</p></dd>
</dl>


<hr/>


## \\private {#cmdprivate}


<p>Indicates that the member documented by the comment block is private, i.e., should only be accessed by other members in the same class.</p>


<p>Note that Doxygen automatically detects the protection level of members in object-oriented languages. This command is intended for use only when the language does not support the concept of protection level natively (e.g. C, PHP 4).</p>


<p>For starting a section of private members, in a way similar to the "private:" class marker in C++, use <a href="#cmdprivatesection">\privatesection</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>sections <a href="#cmdmemberof">\memberof</a>, <a href="#cmdpublic">\public</a>, <a href="#cmdprotected">\protected</a> and <a href="#cmdprivatesection">\privatesection</a>.</p></dd>
</dl>


<hr/>


## \\privatesection {#cmdprivatesection}


<p>Starting a section of private members, in a way similar to the "private:" class marker in C++. Indicates that the member documented by the comment block is private, i.e., should only be accessed by other members in the same class.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>sections <a href="#cmdmemberof">\memberof</a>, <a href="#cmdpublic">\public</a>, <a href="#cmdprotected">\protected</a> and <a href="#cmdprivate">\private</a>.</p></dd>
</dl>


<hr/>


## \\property (qualified property name) {#cmdproperty}


<p>Indicates that a comment block contains documentation for a property (either global or as a member of a class). This command is equivalent to <a href="#cmdfn">\fn</a>, <a href="#cmdtypedef">\typedef</a>, and <a href="#cmdvar">\var</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>sections <a href="#cmdfn">\fn</a>, <a href="#cmdtypedef">\typedef</a>, and <a href="#cmdvar">\var</a>.</p></dd>
</dl>


<hr/>


## \\protected {#cmdprotected}


<p>Indicates that the member documented by the comment block is protected, i.e., should only be accessed by other members in the same or derived classes.</p>


<p>Note that Doxygen automatically detects the protection level of members in object-oriented languages. This command is intended for use only when the language does not support the concept of protection level natively (e.g. C, PHP 4).</p>


<p>For starting a section of protected members, in a way similar to the "protected:" class marker in C++, use <a href="#cmdprotectedsection">\protectedsection</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>sections <a href="#cmdmemberof">\memberof</a>, <a href="#cmdpublic">\public</a>, <a href="#cmdprivate">\private</a> and <a href="#cmdprotectedsection">\protectedsection</a>.</p></dd>
</dl>


<hr/>


## \\protectedsection {#cmdprotectedsection}


<p>Starting a section of protected members, in a way similar to the "protected:" class marker in C++. Indicates that the member documented by the comment block is protected, i.e., should only be accessed by other members in the same or derived classes.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>sections <a href="#cmdmemberof">\memberof</a>, <a href="#cmdpublic">\public</a>, <a href="#cmdprivate">\private</a> and <a href="#cmdprotected">\protected</a>.</p></dd>
</dl>


<hr/>


## \\protocol &lt;name&gt; \[&lt;header-file&gt;\] \[&lt;header-name&gt;\] {#cmdprotocol}


<p>Indicates that a comment block contains documentation for a protocol in Objective-C with name &lt;name&gt;. The arguments are equal to the <a href="#cmdclass">\class</a> command.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdclass">\class</a>.</p></dd>
</dl>


<hr/>


## \\public {#cmdpublic}


<p>Indicates that the member documented by the comment block is public, i.e., can be accessed by any other class or function.</p>


<p>Note that Doxygen automatically detects the protection level of members in object-oriented languages. This command is intended for use only when the language does not support the concept of protection level natively (e.g. C, PHP 4).</p>


<p>For starting a section of public members, in a way similar to the "public:" class marker in C++, use <a href="#cmdpublicsection">\publicsection</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>sections <a href="#cmdmemberof">\memberof</a>, <a href="#cmdprotected">\protected</a>, <a href="#cmdprivate">\private</a> and <a href="#cmdpublicsection">\publicsection</a>.</p></dd>
</dl>


<hr/>


## \\publicsection {#cmdpublicsection}


<p>Starting a section of public members, in a way similar to the "public:" class marker in C++. Indicates that the member documented by the comment block is public, i.e., can be accessed by any other class or function.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>sections <a href="#cmdmemberof">\memberof</a>, <a href="#cmdprotected">\protected</a>, <a href="#cmdprivate">\private</a> and <a href="#cmdpublic">\public</a>.</p></dd>
</dl>


<hr/>


## \\pure {#cmdpure}


<p>Indicates that the member documented by the comment block is pure virtual, i.e., it is abstract and has no implementation associated with it.</p>


<p>This command is intended for use only when the language does not support the concept of pure virtual methods natively (e.g. C, PHP 4).</p>


<hr/>


## \\relates &lt;name&gt; {#cmdrelates}


<p>This command can be used in the documentation of a non-member function &lt;name&gt;. It puts the function inside the 'related function' section of the class documentation. This command is useful for documenting non-friend functions that are nevertheless strongly coupled to a certain class. It prevents the need of having to document a file, but only works for functions.</p>


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


<p>Equivalent to <a href="#cmdrelates">\relates</a></p>


<hr/>


## \\relatesalso &lt;name&gt; {#cmdrelatesalso}


<p>This command can be used in the documentation of a non-member function &lt;name&gt;. It puts the function both inside the 'related function' section of the class documentation as well as leaving it at its normal file documentation location. This command is useful for documenting non-friend functions that are nevertheless strongly coupled to a certain class. It only works for functions.</p>


<hr/>


## \\relatedalso &lt;name&gt; {#cmdrelatedalso}


<p>Equivalent to <a href="#cmdrelatesalso">\relatesalso</a></p>


<hr/>


## \\showinitializer {#cmdshowinitializer}


<p>By default the value of a define and the initializer of a variable are only displayed if they are less than 30 lines long. By putting this command in a comment block of a define or variable, the initializer is shown unconditionally. The maximum number of initialization lines can be changed by means of the configuration parameter <a href="/web-doxygen/docs/pages/config/#cfg_max_initializer_lines">MAX_INITIALIZER_LINES</a>, the default value is 30.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdhideinitializer">\hideinitializer</a>.</p></dd>
</dl>


<hr/>


## \\static {#cmdstatic}


<p>Indicates that the member documented by the comment block is static, i.e., it works on a class, instead of on an instance of the class.</p>


<p>This command is intended for use only when the language does not support the concept of static methods natively (e.g. C).</p>


<hr/>


## \\struct &lt;name&gt; \[&lt;header-file&gt;\] \[&lt;header-name&gt;\] {#cmdstruct}


<p>Indicates that a comment block contains documentation for a struct with name &lt;name&gt;. The arguments are equal to the arguments of the <a href="#cmdclass">\class</a> command.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdclass">\class</a>.</p></dd>
</dl>


<hr/>


## \\typedef (typedef declaration) {#cmdtypedef}


<p>Indicates that a comment block contains documentation for a typedef (either global or as a member of a class). This command is equivalent to <a href="#cmdfn">\fn</a>, <a href="#cmdproperty">\property</a>, and <a href="#cmdvar">\var</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdfn">\fn</a>, <a href="#cmdproperty">\property</a>, and <a href="#cmdvar">\var</a>.</p></dd>
</dl>


<hr/>


## \\union &lt;name&gt; \[&lt;header-file&gt;\] \[&lt;header-name&gt;\] {#cmdunion}


<p>Indicates that a comment block contains documentation for a union with name &lt;name&gt;. The arguments are equal to the arguments of the <a href="#cmdclass">\class</a> command.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdclass">\class</a>.</p></dd>
</dl>


<hr/>


## \\var (variable declaration) {#cmdvar}


<p>Indicates that a comment block contains documentation for a variable or enum value (either global or as a member of a class). This command is equivalent to <a href="#cmdfn">\fn</a>, <a href="#cmdproperty">\property</a>, and <a href="#cmdtypedef">\typedef</a>.</p>


<p>Note that for PHP one can also specify the type of the variable. The syntax is similar as for the <span class="doxyComputerOutput">phpDocumentor</span> but the description has to start at the next line, i.e.</p>



<pre><code>@var  datatype $varname
Description
</code></pre>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdfn">\fn</a>, <a href="#cmdproperty">\property</a>, and <a href="#cmdtypedef">\typedef</a>.</p></dd>
</dl>


<hr/>


## \\vhdlflow \[(title for the flow chart)\] {#cmdvhdlflow}


<p>This is a VHDL specific command, which can be put in the documentation of a process to produce a flow chart of the logic in the process. Optionally a title for the flow chart can be given.</p>



:::info
<p>Currently the flow chart will only appear in the HTML output.</p>
:::


<hr/>


## \\weakgroup &lt;name&gt; \[(title)\] {#cmdweakgroup}


<p>Can be used exactly like <a href="#cmdaddtogroup">\addtogroup</a>, but has a lower priority when it comes to resolving conflicting grouping definitions.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>page <a href="/web-doxygen/docs/pages/grouping">Grouping</a> and section <a href="#cmdaddtogroup">\addtogroup</a>.</p></dd>
</dl>


<hr/>

 <center>

##  ---  Section indicators  ---  
 </center>

<hr/>


## \\attention { attention text } {#cmdattention}


<p>Starts a paragraph where a message that needs attention may be entered. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <span class="doxyComputerOutput">\attention</span> commands will be joined into a single paragraph. The <span class="doxyComputerOutput">\attention</span> command ends when a blank line or some other sectioning command is encountered.</p>


<hr/>


## \\author { list of authors } {#cmdauthor}


<p>Starts a paragraph where one or more author names may be entered. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <span class="doxyComputerOutput">\author</span> commands will be joined into a single paragraph. Each author description will start a new line. Alternatively, one <span class="doxyComputerOutput">\author</span> command may mention several authors. The <span class="doxyComputerOutput">\author</span> command ends when a blank line or some other sectioning command is encountered.</p>


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


<p>Equivalent to <a href="#cmdauthor">\author</a>.</p>


<hr/>


## \\brief { brief description } {#cmdbrief}


<p>Starts a paragraph that serves as a brief description. For classes and files the brief description will be used in lists and at the start of the documentation page. For class and file members, the brief description will be placed at the declaration of the member and prepended to the detailed description. A brief description may span several lines (although it is advised to keep it brief!). A brief description ends when a blank line or another sectioning command is encountered. If multiple <span class="doxyComputerOutput">\brief</span> commands are present they will be joined. See section <a href="#cmdauthor">\author</a> for an example.</p>


<p>Synonymous to <a href="#cmdshort">\short</a>.</p>


<hr/>


## \\bug { bug description } {#cmdbug}


<p>Starts a paragraph where one or more bugs may be reported. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <span class="doxyComputerOutput">\bug</span> commands will be joined into a single paragraph. Each bug description will start on a new line. Alternatively, one <span class="doxyComputerOutput">\bug</span> command may mention several bugs. The <span class="doxyComputerOutput">\bug</span> command ends when a blank line or some other sectioning command is encountered. See section <a href="#cmdauthor">\author</a> for an example.</p>


<p>The description will also add an item to a separate Bug list and the two instances of the description will be cross-referenced. Each item in the Bug list will be preceded by a header that indicates the origin of the item.</p>


<p>The Bug list and the corresponding entries can be disabled by setting the <a href="/web-doxygen/docs/pages/config/#cfg_generate_buglist">GENERATE_BUGLIST</a> to <span class="doxyComputerOutput">NO</span>.</p>


<hr/>


## \\cond \[(section-label)\] {#cmdcond}


<p>Starts a conditional section that ends with a corresponding <a href="#cmdendcond">\endcond</a> command, which is typically found in another comment block. The main purpose of this pair of commands is to (conditionally) exclude part of a file from processing (in older version of Doxygen this could only be achieved using C preprocessor commands).</p>


<p>The section between <span class="doxyComputerOutput">\cond</span> and <a href="#cmdendcond">\endcond</a> can be included by adding its section label to the <a href="/web-doxygen/docs/pages/config/#cfg_enabled_sections">ENABLED_SECTIONS</a> configuration option. If the section label is omitted, the section will be excluded from processing unconditionally. The section label can be a logical expression build of section labels, round brackets, &amp;&amp; (AND), || (OR) and ! (NOT). If you use an expression you need to wrap it in round brackets, i.e <span class="doxyComputerOutput">\cond (!LABEL1 &amp;&amp; LABEL2)</span>.</p>


<p>For conditional sections within a comment block one should use a <a href="#cmdif">\if</a> ... <a href="#cmdendif">\endif</a> block. When using <span class="doxyComputerOutput">\cond</span> and the condition is not satisfied the current comment block is ended and everything until the matching <a href="#cmdendcond">\endcond</a> is removed and a new command block is started there.</p>


<p>Conditional sections can be nested. In this case a nested section will only be shown if it and its containing section are included.</p>


<p>Here is an example showing the commands in action:</p>



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


<p>The output will be different depending on whether or not <a href="/web-doxygen/docs/pages/config/#cfg_enabled_sections">ENABLED_SECTIONS</a> contains <span class="doxyComputerOutput">TEST</span>, or <span class="doxyComputerOutput">DEV</span></p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>sections <a href="#cmdif">\if</a>, <a href="#cmdifnot">\ifnot</a>, <a href="#cmdelse">\else</a>, <a href="#cmdelseif">\elseif</a>, <a href="#cmdendif">\endif</a>, <a href="#cmdendcond">\endcond</a>, and <a href="/web-doxygen/docs/pages/config/#cfg_enabled_sections">ENABLED_SECTIONS</a>.</p></dd>
</dl>



:::info
<p>Due to the moment of parsing the <span class="doxyComputerOutput">\cond</span> and <a href="#cmdendcond">\endcond</a> commands cannot be used in <a href="/web-doxygen/docs/pages/config/#cfg_aliases">ALIASES</a>.</p>
:::


<hr/>


## \\copyright { copyright description } {#cmdcopyright}


<p>Starts a paragraph where the copyright of an entity can be described. This paragraph will be indented. The text of the paragraph has no special internal structure. See section <a href="#cmdauthor">\author</a> for an example.</p>


<hr/>


## \\date { date description } {#cmddate}


<p>Starts a paragraph where one or more dates may be entered. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <span class="doxyComputerOutput">\date</span> commands will be joined into a single paragraph. Each date description will start on a new line. Alternatively, one <span class="doxyComputerOutput">\date</span> command may mention several dates. The <span class="doxyComputerOutput">\date</span> command ends when a blank line or some other sectioning command is encountered. See section <a href="#cmdauthor">\author</a> for an example.</p>


<hr/>


## \\showdate "&lt;format&gt;" \[ &lt;date\_time&gt; \] {#cmdshowdate}


<p>Shows the date and time based on the given &lt;format&gt; and &lt;date_time&gt;. Where the &lt;format&gt; is a string in which the following tokens have a special meaning:</p>


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

<p>Note that the &lt;format&gt; has to be between double quotes.</p>


<p>In case the &lt;date_time&gt; is specified it has to have the following representation:</p>


<ul class="doxyList ">
<li>optional <span class="doxyComputerOutput">date</span> where <span class="doxyComputerOutput">date</span> is:

<ul class="doxyList ">
<li>4 digits for the year</li>
<li>a minus sign</li>
<li>one or 2 digits for the month</li>
<li>a minus sign</li>
<li>one or 2 digits for the day</li>
</ul></li>
<li>optional <span class="doxyComputerOutput">time</span> where <span class="doxyComputerOutput">time</span> is:

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

<p>in case the &lt;date_time&gt; is not specified the current date and time are used.</p>


<p>Here is an example:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">- \showdate </span><span class="doxyHighlightStringLiteral">"%A %d-%m-%Y"</span><span class="doxyHighlight"> 2015-3-14</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">- \showdate </span><span class="doxyHighlightStringLiteral">"%a %d-%m-%y"</span><span class="doxyHighlight"> 2015-3-14</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">- \showdate </span><span class="doxyHighlightStringLiteral">"%-m.%d%y"</span><span class="doxyHighlight"> 2015-3-14</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">- \showdate </span><span class="doxyHighlightStringLiteral">"%A %d-%m-%Y %H:%M:%S"</span><span class="doxyHighlight"> 2015-3-14 03:04:15</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">- \showdate </span><span class="doxyHighlightStringLiteral">"%A %d-%m-%Y %H:%M"</span><span class="doxyHighlight"> 2015-3-14 03:04</span></span></div>

</div>


<p>In case <span class="doxyComputerOutput">OUTPUT_LANGUAGE=english</span> this results in:</p>


<ul class="doxyList ">
<li>Saturday 14-03-2015</li>
<li>Sat 14-03-15</li>
<li>3.1415</li>
<li>Saturday 14-03-15 03:04:15</li>
<li>Saturday 14-03-15 03:04</li>
</ul>

<p>In case <span class="doxyComputerOutput">OUTPUT_LANGUAGE=dutch</span> this results in:</p>


<ul class="doxyList ">
<li>zaterdag 14-03-15</li>
<li>za 14-03-2015</li>
<li>3.1415</li>
<li>zaterdag 14-03-15 03:04:15</li>
<li>zaterdag 14-03-15 03:04</li>
</ul>

<hr/>


## \\deprecated { description } {#cmddeprecated}


<p>Starts a paragraph indicating that this documentation block belongs to a deprecated entity. Can be used to describe alternatives, expected life span, etc. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <span class="doxyComputerOutput">\deprecated</span> commands will be joined into a single paragraph. Each deprecation description will start on a new line. The <span class="doxyComputerOutput">\deprecated</span> command ends when a blank line or some other sectioning command is encountered.</p>


<p>The description will also add an item to a separate Deprecated list and the two instances of the description will be cross-referenced. Each item in the Deprecated list will be preceded by a header that indicates the origin of the item.</p>


<p>The Deprecated list and the corresponding entries can be disabled by setting the <a href="/web-doxygen/docs/pages/config/#cfg_generate_deprecatedlist">GENERATE_DEPRECATEDLIST</a> to <span class="doxyComputerOutput">NO</span>.</p>


<hr/>


## \\details { detailed description } {#cmddetails}


<p>Just like <a href="#cmdbrief">\brief</a> starts a brief description, <span class="doxyComputerOutput">\details</span> starts the detailed description. You can also start a new paragraph (blank line) then the <span class="doxyComputerOutput">\details</span> command is not needed.</p>


<hr/>


## \\noop ( text to be ignored ) {#cmdnoop}


<p>All the text, including the command, till the end of the line is ignored. The command will most commonly be used in combination with <a href="/web-doxygen/docs/pages/config/#cfg_aliases">ALIASES</a> to ignore not supported commands that are present for e.g. other processing tools.</p>


<hr/>


## \\raisewarning ( text to be shown as warning ) {#cmdraisewarning}


<p>All the text, excluding the command, till the end of the line is literally shown as a documentation warning. The text, including the command, is removed from the output. The command will most commonly be used in combination with <a href="/web-doxygen/docs/pages/config/#cfg_aliases">ALIASES</a> to show a specific warning.</p>


<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<pre><code>\raisewarning My specific warning

\warnNoDoc

\warnNoDoc{My specific warning}
</code></pre>


<p>together with:</p>



<pre><code>ALIASES  = warnNoDoc="\raisewarning Missing documentation"
ALIASES += warnNoDoc{1}="\raisewarning Incomplete documentation: \1"
</code></pre>


<p>will result in:</p>



<pre><code>   ex_1.md:1: warning: My specific warning
   ex_1.md:3: warning: Missing documentation
   ex_1.md:5: warning: Incomplete documentation: My specific warning
</code></pre>
</dd>
</dl>


<hr/>


## \\else {#cmdelse}


<p>Starts a conditional section if the previous conditional section was not enabled. The previous section should have been started with a <a href="#cmdif">\if</a>, <a href="#cmdifnot">\ifnot</a>, or <a href="#cmdelseif">\elseif</a> command.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>sections <a href="#cmdif">\if</a>, <a href="#cmdifnot">\ifnot</a>, <a href="#cmdelseif">\elseif</a>, <a href="#cmdendif">\endif.</a></p></dd>
</dl>


<hr/>


## \\elseif (section-label) {#cmdelseif}


<p>Starts a conditional documentation section if the previous section was not enabled. A conditional section is disabled by default. To enable it you must put the section-label after the <a href="/web-doxygen/docs/pages/config/#cfg_enabled_sections">ENABLED_SECTIONS</a> tag in the configuration file. The section label can be a logical expression build of section names, round brackets, &amp;&amp; (AND), || (OR) and ! (NOT). Conditional blocks can be nested. A nested section is only enabled if all enclosing sections are enabled as well.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>sections <a href="#cmdif">\if</a>, <a href="#cmdifnot">\ifnot</a>, <a href="#cmdelse">\else</a>, <a href="#cmdendif">\endif.</a></p></dd>
</dl>


<hr/>


## \\endcond {#cmdendcond}


<p>Ends a conditional section that was started by <a href="#cmdcond">\cond</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdcond">\cond</a>.</p></dd>
</dl>



:::info
<p>Due to the moment of parsing the <span class="doxyComputerOutput">\endcond</span> and <a href="#cmdcond">\cond</a> commands cannot be used in <a href="/web-doxygen/docs/pages/config/#cfg_aliases">ALIASES</a>.</p>
:::


<hr/>


## \\endif {#cmdendif}


<p>Ends a conditional section that was started by <a href="#cmdif">\if</a> or <a href="#cmdifnot">\ifnot</a> For each <a href="#cmdif">\if</a> or <a href="#cmdifnot">\ifnot</a> one and only one matching <a href="#cmdendif">\endif</a> must follow.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>sections <a href="#cmdif">\if</a>, <a href="#cmdifnot">\ifnot</a>, <a href="#cmdelse">\else</a>, <a href="#cmdelseif">\elseif.</a></p></dd>
</dl>


<hr/>


## \\exception &lt;exception-object&gt; { exception description } {#cmdexception}


<p>Starts an exception description for an exception object with name &lt;exception-object&gt;. Followed by a description of the exception. The existence of the exception object is not checked. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <span class="doxyComputerOutput">\exception</span> commands will be joined into a single paragraph. Each exception description will start on a new line. The <span class="doxyComputerOutput">\exception</span> description ends when a blank line or some other sectioning command is encountered. See section <a href="#cmdfn">\fn</a> for an example.</p>


<hr/>


## \\if (section-label) {#cmdif}


<p>Starts a conditional documentation section. The section ends with a matching <a href="#cmdendif">\endif</a> command. A conditional section is disabled by default. To enable it you must put the section-label after the <a href="/web-doxygen/docs/pages/config/#cfg_enabled_sections">ENABLED_SECTIONS</a> tag in the configuration file.</p>


<p>The section label can be a logical expression build of section names, round brackets, &amp;&amp; (AND), || (OR) and ! (NOT). If you use an expression you need to wrap it in round brackets, i.e <span class="doxyComputerOutput">\if (!LABEL1 &amp;&amp; LABEL2)</span>.</p>


<p>Conditional blocks can be nested. A nested section is only enabled if all enclosing sections are enabled as well.</p>


<p>The <span class="doxyComputerOutput">\if</span> and corresponding <a href="#cmdendif">\endif</a> have to be in the same comment block. When a conditional block needs to span more than one comment block one has to use <a href="#cmdcond">\cond</a> ... <a href="#cmdendcond">\endcond</a>.</p>


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


<p>You can also use conditional commands inside aliases. To document a class in two languages you could for instance use:</p>


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


<p>Where the following aliases are defined in the configuration file:</p>



<pre><code>ALIASES  = "english=\if english" \
           "endenglish=\endif" \
           "dutch=\if dutch" \
           "enddutch=\endif"
</code></pre>


<p>and <a href="/web-doxygen/docs/pages/config/#cfg_enabled_sections">ENABLED_SECTIONS</a> can be used to enable either <span class="doxyComputerOutput">english</span> or <span class="doxyComputerOutput">dutch</span>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>sections <a href="#cmdendif">\endif</a>, <a href="#cmdifnot">\ifnot</a>, <a href="#cmdelse">\else</a>, <a href="#cmdelseif">\elseif</a>, <a href="#cmdcond">\cond</a>, <a href="#cmdendcond">\endcond</a>, and <a href="/web-doxygen/docs/pages/config/#cfg_enabled_sections">ENABLED_SECTIONS</a>.</p></dd>
</dl>


<hr/>


## \\ifnot (section-label) {#cmdifnot}


<p>Starts a conditional documentation section. The section ends with a matching <a href="#cmdendif">\endif</a> command. This conditional section is enabled by default. To disable it you must put the section-label after the <a href="/web-doxygen/docs/pages/config/#cfg_enabled_sections">ENABLED_SECTIONS</a> tag in the configuration file. The section label can be a logical expression build of section names, round brackets, &amp;&amp; (AND), || (OR) and ! (NOT).</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>sections <a href="#cmdendif">\endif</a>, <a href="#cmdif">\if</a>, <a href="#cmdelse">\else</a>, and <a href="#cmdelseif">\elseif</a>, <a href="#cmdcond">\cond</a>, <a href="#cmdendcond">\endcond</a>, and <a href="/web-doxygen/docs/pages/config/#cfg_enabled_sections">ENABLED_SECTIONS</a>.</p></dd>
</dl>


<hr/>


## \\important { important text } {#cmdimportant}


<p>Starts a paragraph where a message that needs important may be entered. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <span class="doxyComputerOutput">\important</span> commands will be joined into a single paragraph. The <span class="doxyComputerOutput">\important</span> command ends when a blank line or some other sectioning command is encountered.</p>


<hr/>


## \\invariant { description of invariant } {#cmdinvariant}


<p>Starts a paragraph where the invariant of an entity can be described. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <span class="doxyComputerOutput">\invariant</span> commands will be joined into a single paragraph. Each invariant description will start on a new line. Alternatively, one <span class="doxyComputerOutput">\invariant</span> command may mention several invariants. The <span class="doxyComputerOutput">\invariant</span> command ends when a blank line or some other sectioning command is encountered.</p>


<hr/>


## \\note { text } {#cmdnote}


<p>Starts a paragraph where a note can be entered. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <span class="doxyComputerOutput">\note</span> commands will be joined into a single paragraph. Each note description will start on a new line. Alternatively, one <span class="doxyComputerOutput">\note</span> command may mention several notes. The <span class="doxyComputerOutput">\note</span> command ends when a blank line or some other sectioning command is encountered. See section <a href="#cmdpar">\par</a> for an example.</p>


<hr/>


## \\par \[(paragraph title)\] { paragraph } {#cmdpar}


<p>If a paragraph title is given this command starts a paragraph with a user defined heading. The heading extends until the end of the line. The paragraph following the command will be indented.</p>


<p>If no paragraph title is given this command will start a new paragraph. This will also work inside other paragraph commands (like <a href="#cmdparam">\param</a> or <a href="#cmdwarning">\warning</a>) without ending that command.</p>


<p>The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. The <span class="doxyComputerOutput">\par</span> command ends when a blank line or some other sectioning command is encountered.</p>


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


<p>Starts a parameter description for a function parameter with name &lt;parameter-name&gt;, followed by a description of the parameter. The existence of the parameter is checked and a warning is given if the documentation of this (or any other) parameter is missing or not present in the function declaration or definition.</p>


<p>The <span class="doxyComputerOutput">\param</span> command has an optional attribute, &lt;dir&gt;, specifying the direction of the parameter. Possible values are "[in]", "[out]", and "[in,out]"; note the [square] brackets in this description. For the bidirecional values, directions "in" and "out" can be specified in any order, and they can either be written altogether, or separated with a comma (<span class="doxyComputerOutput">,</span>) or a space. That means that for example values "[outin]" or "[in out]" are also valid. Note that it is also possible to put whitespace between the command and the &lt;dir&gt;. When a parameter is both input and output, [in,out] is used as attribute. Here is an example for the function <span class="doxyComputerOutput">memcpy:</span></p>


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


<p>The parameter description is a paragraph with no special internal structure. All visual enhancement commands may be used inside the paragraph.</p>


<p>Multiple adjacent <span class="doxyComputerOutput">\param</span> commands will be joined into a single paragraph. Each parameter description will start on a new line. The <span class="doxyComputerOutput">\param</span> description ends when a blank line or some other sectioning command is encountered. See section <a href="#cmdfn">\fn</a> for an example.</p>


<p>Note that you can also document multiple parameters with a single <span class="doxyComputerOutput">\param</span> command using a comma separated list. Here is an example:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** Sets the position.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> *  @param x,y,z Coordinates of the position in 3D space.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"> */</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> setPosition(</span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> x,</span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> y,</span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> z,</span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Note that for PHP one can also specify the type (or types if you separate them with a pipe symbol) which are allowed for a parameter (as this is not part of the definition). The syntax is the same as for the <span class="doxyComputerOutput">phpDocumentor</span>, i.e.</p>



<pre><code>@param  datatype1|datatype2 $paramname description
</code></pre>


<hr/>


## \\parblock {#cmdparblock}


<p>For commands that expect a single paragraph as argument (such as <a href="#cmdpar">\par</a>, <a href="#cmdparam">\param</a> and <a href="#cmdwarning">\warning</a>), the <a href="#cmdparblock">\parblock</a> command allows to start a description that covers multiple paragraphs, which then ends with <a href="#cmdendparblock">\endparblock</a>.</p>


<p>Example:</p>



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


<p>Note that the <span class="doxyComputerOutput">\parblock</span> command may also appear directly after <a href="#cmdparam">\param</a>'s first argument.</p>


<hr/>


## \\endparblock {#cmdendparblock}


<p>This ends a block of paragraphs started with <a href="#cmdparblock">\parblock</a>.</p>


<hr/>


## \\tparam &lt;template-parameter-name&gt; { description } {#cmdtparam}


<p>Starts a template parameter for a class or function template parameter with name &lt;template-parameter-name&gt;, followed by a description of the template parameter.</p>


<p>Otherwise similar to <a href="#cmdparam">\param</a>.</p>


<hr/>


## \\post { description of the postcondition } {#cmdpost}


<p>Starts a paragraph where the postcondition of an entity can be described. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <span class="doxyComputerOutput">\post</span> commands will be joined into a single paragraph. Each postcondition will start on a new line. Alternatively, one <span class="doxyComputerOutput">\post</span> command may mention several postconditions. The <span class="doxyComputerOutput">\post</span> command ends when a blank line or some other sectioning command is encountered.</p>


<hr/>


## \\pre { description of the precondition } {#cmdpre}


<p>Starts a paragraph where the precondition of an entity can be described. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <span class="doxyComputerOutput">\pre</span> commands will be joined into a single paragraph. Each precondition will start on a new line. Alternatively, one <span class="doxyComputerOutput">\pre</span> command may mention several preconditions. The <span class="doxyComputerOutput">\pre</span> command ends when a blank line or some other sectioning command is encountered.</p>


<hr/>


## \\remark { remark text } {#cmdremark}


<p>Starts a paragraph where one or more remarks may be entered. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <span class="doxyComputerOutput">\remark</span> commands will be joined into a single paragraph. Each remark will start on a new line. Alternatively, one <span class="doxyComputerOutput">\remark</span> command may mention several remarks. The <span class="doxyComputerOutput">\remark</span> command ends when a blank line or some other sectioning command is encountered.</p>


<hr/>


## \\remarks { remark text } {#cmdremarks}


<p>Equivalent to <a href="#cmdremark">\remark</a>.</p>


<hr/>


## \\result { description of the result value } {#cmdresult}


<p>Equivalent to <a href="#cmdreturn">\return</a>.</p>


<hr/>


## \\return { description of the return value } {#cmdreturn}


<p>Starts a return value description for a function. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <span class="doxyComputerOutput">\return</span> commands will be joined into a single paragraph. The <span class="doxyComputerOutput">\return</span> description ends when a blank line or some other sectioning command is encountered. See section <a href="#cmdfn">\fn</a> for an example.</p>


<hr/>


## \\returns { description of the return value } {#cmdreturns}


<p>Equivalent to <a href="#cmdreturn">\return</a>.</p>


<hr/>


## \\retval &lt;return value&gt; { description } {#cmdretval}


<p>Starts a description for a function's return value with name &lt;return value&gt;, followed by a description of the return value. The text of the paragraph that forms the description has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <span class="doxyComputerOutput">\retval</span> commands will be joined into a single paragraph. Each return value description will start on a new line. The <span class="doxyComputerOutput">\retval</span> description ends when a blank line or some other sectioning command is encountered.</p>


<hr/>


## \\sa { references } {#cmdsa}


<p>Starts a paragraph where one or more cross-references to classes, functions, methods, variables, files or URL may be specified. Two names joined by either <span class="doxyComputerOutput">::</span> or <span class="doxyComputerOutput">#</span> are understood as referring to a class and one of its members. One of several overloaded methods or constructors may be selected by including a parenthesized list of argument types after the method name.</p>


<p>Synonymous to <a href="#cmdsee">\see</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="/web-doxygen/docs/pages/autolink">autolink</a> for information on how to create links to objects.</p></dd>
</dl>


<hr/>


## \\see { references } {#cmdsee}


<p>Equivalent to <a href="#cmdsa">\sa</a>. Introduced for compatibility with Javadoc.</p>


<hr/>


## \\short { short description } {#cmdshort}


<p>Equivalent to <a href="#cmdbrief">\brief</a>.</p>


<hr/>


## \\since { text } {#cmdsince}


<p>This command can be used to specify since when (version or time) an entity is available. The paragraph that follows <span class="doxyComputerOutput">\since</span> does not have any special internal structure. All visual enhancement commands may be used inside the paragraph. The <span class="doxyComputerOutput">\since</span> description ends when a blank line or some other sectioning command is encountered.</p>


<hr/>


## \\test { paragraph describing a test case } {#cmdtest}


<p>Starts a paragraph where one or more test cases can be described. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <span class="doxyComputerOutput">\test</span> commands will be joined into a single paragraph. Each test case description will start on a new line. Alternatively, one <span class="doxyComputerOutput">\test</span> command may mention several test cases. The <span class="doxyComputerOutput">\test</span> command ends when a blank line or some other sectioning command is encountered.</p>


<p>The description will also add an item to a separate Test list and the two instances of the description will be cross-referenced. Each item in the Test list will be preceded by a header that indicates the origin of the item.</p>


<p>The Test list and the corresponding entries can be disabled by setting the <a href="/web-doxygen/docs/pages/config/#cfg_generate_testlist">GENERATE_TESTLIST</a> to <span class="doxyComputerOutput">NO</span>.</p>


<hr/>


## \\throw &lt;exception-object&gt; { exception description } {#cmdthrow}


<p>Synonymous <a href="#cmdexception">\exception</a>.</p>


<dl class="doxySectionUser">
<dt>Note:</dt>
<dd><p>the command <a href="#cmdthrows">\throws</a> is a synonym for this command.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdexception">\exception</a></p></dd>
</dl>


<hr/>


## \\throws &lt;exception-object&gt; { exception description } {#cmdthrows}


<p>Equivalent to <a href="#cmdthrow">\throw</a>.</p>


<hr/>


## \\todo { paragraph describing what is to be done } {#cmdtodo}


<p>Starts a paragraph where one or more todo items are described. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <span class="doxyComputerOutput">\todo</span> commands will be joined into a single paragraph. Each todo description will start on a new line. Alternatively, one <span class="doxyComputerOutput">\todo</span> command may mention several todo descriptions. The <span class="doxyComputerOutput">\todo</span> command ends when a blank line or some other sectioning command is encountered.</p>


<p>The description will also add an item to a separate Todo list and the two instances of the description will be cross-referenced. Each item in the Todo list will be preceded by a header that indicates the origin of the item.</p>


<p>The Todo list and the corresponding entries can be disabled by setting the <a href="/web-doxygen/docs/pages/config/#cfg_generate_todolist">GENERATE_TODOLIST</a> to <span class="doxyComputerOutput">NO</span>.</p>


<hr/>


## \\version { version number } {#cmdversion}


<p>Starts a paragraph where one or more version strings may be entered. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <span class="doxyComputerOutput">\version</span> commands will be joined into a single paragraph. Each version description will start on a new line. Alternatively, one <span class="doxyComputerOutput">\version</span> command may mention several version strings. The \version command ends when a blank line or some other sectioning command is encountered. See section <a href="#cmdauthor">\author</a> for an example.</p>


<hr/>


## \\warning { warning message } {#cmdwarning}


<p>Starts a paragraph where one or more warning messages may be entered. The paragraph will be indented. The text of the paragraph has no special internal structure. All visual enhancement commands may be used inside the paragraph. Multiple adjacent <span class="doxyComputerOutput">\warning</span> commands will be joined into a single paragraph. Each warning description will start on a new line. Alternatively, one <span class="doxyComputerOutput">\warning</span> command may mention several warnings. The <span class="doxyComputerOutput">\warning</span> command ends when a blank line or some other sectioning command is encountered. See section <a href="#cmdauthor">\author</a> for an example.</p>


<hr/>


## \\xrefitem &lt;key&gt; "heading" "list title" { text } {#cmdxrefitem}


<p>This command is a generalization of commands such as <a href="#cmdtodo">\todo</a> and <a href="#cmdbug">\bug</a>. It can be used to create user-defined text sections which are automatically cross-referenced between the place of occurrence and a related page, which will be generated. On the related page all sections of the same type will be collected.</p>


<p>The first argument &lt;key&gt; is an identifier uniquely representing the type of the section. The second argument is a quoted string representing the heading of the section under which text passed as the fourth argument is put. The third argument (list title) is used as the title for the related page containing all items with the same key. The second and third string argument cannot contain a newline. The keys <span class="doxyComputerOutput">"todo"</span>, <span class="doxyComputerOutput">"test"</span>, <span class="doxyComputerOutput">"bug"</span> and <span class="doxyComputerOutput">"deprecated"</span> are predefined.</p>


<p>To get an idea on how to use the <span class="doxyComputerOutput">\xrefitem</span> command and what its effect is, consider the todo list, which (for English output) can be seen an alias for the command</p>



<pre><code>\xrefitem todo "Todo" "Todo List"
</code></pre>


<p>Since it is very tedious and error-prone to repeat the first three parameters of the command for each section, the command is meant to be used in combination with the <a href="/web-doxygen/docs/pages/config/#cfg_aliases">ALIASES</a> option in the configuration file. To define a new command <span class="doxyComputerOutput">\reminder</span>, for instance, one should add the following line to the configuration file:</p>



<pre><code>ALIASES += "reminder=\xrefitem reminders \"Reminder\" \"Reminders\""
</code></pre>


<p>Note the use of escaped quotes for the second and third argument of the <span class="doxyComputerOutput">\xrefitem</span> command.</p>


<p>In case parameter "(heading)" is the empty string no heading is generated. This can be useful when used in combination with the <a href="#cmdpage">\page</a> command e.g.</p>



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


<p>with <span class="doxyComputerOutput">\error</span> defined as</p>



<pre><code>ALIASES += "error=\xrefitem my_errors \"\" \"\""
</code></pre>


<hr/>

 <center>

##  ---  Commands to create links  ---  
 </center>

<hr/>


## \\addindex (text) {#cmdaddindex}


<p>This command adds (text) to the <code>{\LaTeX}</code> , DocBook and RTF index.</p>


<hr/>


## \\anchor &lt;word&gt; {#cmdanchor}


<p>This command places an invisible, named anchor into the documentation to which you can refer with the <a href="#cmdref">\ref</a> command.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdref">\ref</a>.</p></dd>
</dl>


<hr/>


## \\cite\['{'\[option\]'}'\] &lt;label&gt; {#cmdcite}


<p>Adds a bibliographic reference in the text and in the list of bibliographic references. The &lt;label&gt; must be a valid BibTeX label that can be found in one of the .bib files listed in <a href="/web-doxygen/docs/pages/config/#cfg_cite_bib_files">CITE_BIB_FILES</a>. For the <code>{\LaTeX}</code> output the formatting of the reference in the text can be configured with <a href="/web-doxygen/docs/pages/config/#cfg_latex_bib_style">LATEX_BIB_STYLE</a>. For other output formats a fixed representation is used. Note that using this command requires the <span class="doxyComputerOutput">bibtex</span> tool to be present in the search path.</p>


<p>There are a number of options possible:</p>


<ul class="doxyList ">
<li><span class="doxyComputerOutput">number</span>, <span class="doxyComputerOutput">shortauthor</span>, <span class="doxyComputerOutput">year</span>, these options are mutually exclusive, in case none of these is specified <span class="doxyComputerOutput">number</span> is assumed.

<ul class="doxyList ">
<li><span class="doxyComputerOutput">number</span> create a numerical reference</li>
<li><span class="doxyComputerOutput">shortauthor</span> just the surname of the first author is given, and in case multiple authors are present the text "et al." is added</li>
<li><span class="doxyComputerOutput">year</span>, the year of publication is mentioned (when specified in the bibtex file.</li>
</ul></li>
<li><span class="doxyComputerOutput">nopar</span>, no (square) brackets are added</li>
<li><span class="doxyComputerOutput">nocite</span>, no link to a citation in the bibliography is made (and the reference is not added to the bibliography based on this item)</li>
</ul>

<hr/>


## \\endlink {#cmdendlink}


<p>This command ends a link that is started with the <a href="#cmdlink">\link</a> command.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdlink">\link</a>.</p></dd>
</dl>


<hr/>


## \\link &lt;link-object&gt; {#cmdlink}


<p>The links that are automatically generated by Doxygen always have the name of the object they point to as link-text.</p>


<p>The <span class="doxyComputerOutput">\link</span> command can be used to create a link to an object (a file, class, or member) with a user specified link-text. The link command should end with an <a href="#cmdendlink">\endlink</a> command. All text between the <span class="doxyComputerOutput">\link</span> and <a href="#cmdendlink">\endlink</a> commands serves as text for a link to the &lt;link-object&gt; specified as the first argument of <span class="doxyComputerOutput">\link</span>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>Section <a href="/web-doxygen/docs/pages/autolink">autolink</a> for more information on automatically generated links and valid link-objects.</p></dd>
</dl>


<hr/>


## \\ref &lt;name&gt; \["(text)"\] {#cmdref}


<p>Creates a reference to a named symbol, file, section, subsection, page or anchor.</p>


<p>For HTML documentation the reference command will generate a link to the section. For a section or subsection the title of the section will be used as the text of the link. For an anchor the optional text between quotes will be used or &lt;name&gt; if no text is specified.</p>


<p>In case &lt;name&gt; has spaces (for instance if it refers a file name containing spaces) you need to add double quotes around the &lt;name&gt;, e.g. "my file.md".</p>


<p>For <code>{\LaTeX}</code> documentation the reference command will be the same unless the <a href="/web-doxygen/docs/pages/config/#cfg_pdf_hyperlinks">PDF_HYPERLINKS</a> option has been set to <span class="doxyComputerOutput">NO</span>, in this case it generates the section title for sections or the text if &lt;name&gt; refers to an anchor followed by a page number.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>Section <a href="#cmdpage">\page</a> for an example of the <span class="doxyComputerOutput">\ref</span> command.</p></dd>
</dl>


<hr/>


## \\refitem &lt;name&gt; {#cmdrefitem}


<p>Just like the <a href="#cmdref">\ref</a> command, this command creates a reference to a named section, but this reference appears in a list that is started by <a href="#cmdsecreflist">\secreflist</a> and ends with <a href="#cmdendsecreflist">\endsecreflist</a>. An example of such a list can be seen <a href="#showsecreflist">at the top of the page</a>.</p>


<hr/>


## \\secreflist {#cmdsecreflist}


<p>Starts an index list of item, created with <a href="#cmdrefitem">\refitem</a> that each link to a named section.</p>


<hr/>


## \\endsecreflist {#cmdendsecreflist}


<p>End an index list started with <a href="#cmdsecreflist">\secreflist</a>.</p>


<hr/>


## \\subpage &lt;name&gt; \["(text)"\] {#cmdsubpage}


<p>This command can be used to create a hierarchy of pages. The same structure can be made using the <a href="#cmddefgroup">\defgroup</a> and <a href="#cmdingroup">\ingroup</a> commands, but for pages the <span class="doxyComputerOutput">\subpage</span> command is often more convenient. The main page (see <a href="#cmdmainpage">\mainpage</a>) is typically the root of hierarchy.</p>


<p>This command behaves similar as <a href="#cmdref">\ref</a> in the sense that it creates a reference to a page labeled &lt;name&gt; with the optional link text as specified in the second argument.</p>


<p>It differs from the <a href="#cmdref">\ref</a> command in that it only works for pages, and creates a parent-child relation between pages, where the child page (or sub page) is identified by label &lt;name&gt;.</p>


<p>See the <a href="#cmdsection">\section</a> and <a href="#cmdsubsection">\subsection</a> commands if you want to add structure without creating multiple pages.</p>



:::info
<p>Each page can be the sub page of only one other page and no cyclic relations are allowed, i.e. the page hierarchy must have a tree structure.</p>
:::


<p>Here is an example:</p>



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


<p>Creates a table of contents at the top of a page, listing all sections and subsections in the page. The <span class="doxyComputerOutput">option</span> can be <span class="doxyComputerOutput">HTML</span> or <span class="doxyComputerOutput">LaTeX</span> or <span class="doxyComputerOutput">XML</span> or <span class="doxyComputerOutput">DocBook</span>. When a <span class="doxyComputerOutput">level</span> is specified this means the maximum nesting level that is shown. The value of <span class="doxyComputerOutput">level</span> should be in the range 1..6, values outside this range are considered to be 6. In case no <span class="doxyComputerOutput">level</span> is specified <span class="doxyComputerOutput">level</span> is set to 6 (show all) In case no <span class="doxyComputerOutput">option</span>. is specified <span class="doxyComputerOutput">\tableofcontents</span> acts as if just the <span class="doxyComputerOutput">option</span> <span class="doxyComputerOutput">HTML</span> and <span class="doxyComputerOutput">XML</span> was specified. In case of multiple <span class="doxyComputerOutput">\tableofcontents</span> commands in a page the <span class="doxyComputerOutput">option</span>(s) will be used additional to the already specified <span class="doxyComputerOutput">option</span>(s), but only the last <span class="doxyComputerOutput">level</span> of an <span class="doxyComputerOutput">option</span> is valid.</p>



:::warning
<p>This command only works inside related page documentation and <em>not</em> in other documentation blocks and only has effect in the specified output!</p>
:::


<hr/>


## \\section &lt;section-name&gt; (section title) {#cmdsection}


<p>Creates a section with name &lt;section-name&gt;. The title of the section should be specified as the second argument of the <span class="doxyComputerOutput">\section</span> command.</p>



:::warning
<p>This command only works inside related page documentation and <em>not</em> in other documentation blocks!</p>
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>Section <a href="#cmdpage">\page</a> for an example of the <span class="doxyComputerOutput">\section</span> command.</p></dd>
</dl>


<hr/>


## \\subsection &lt;subsection-name&gt; (subsection title) {#cmdsubsection}


<p>Creates a subsection with name &lt;subsection-name&gt;. The title of the subsection should be specified as the second argument of the <span class="doxyComputerOutput">\subsection</span> command.</p>



:::warning
<p>This command only works inside a section of a related page documentation block and <em>not</em> in other documentation blocks!</p>
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>Section <a href="#cmdpage">\page</a> for an example of the <span class="doxyComputerOutput">\subsection</span> command.</p></dd>
</dl>


<hr/>


## \\subsubsection &lt;subsubsection-name&gt; (subsubsection title) {#cmdsubsubsection}


<p>Creates a subsubsection with name &lt;subsubsection-name&gt;. The title of the subsubsection should be specified as the second argument of the <span class="doxyComputerOutput">\subsubsection</span> command.</p>



:::warning
<p>This command only works inside a subsection of a related page documentation block and <em>not</em> in other documentation blocks!</p>
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>Section <a href="#cmdpage">\page</a> for an example of the <a href="#cmdsection">\section</a> command and <a href="#cmdsubsection">\subsection</a> command.</p></dd>
</dl>


<hr/>


## \\paragraph &lt;paragraph-name&gt; (paragraph title) {#cmdparagraph}


<p>Creates a named paragraph with name &lt;paragraph-name&gt;. The title of the paragraph should be specified as the second argument of the <span class="doxyComputerOutput">\paragraph</span> command.</p>



:::warning
<p>This command only works inside a subsubsection of a related page documentation block and <em>not</em> in other documentation blocks!</p>
:::


<hr/>


## \\subparagraph &lt;subparagraph-name&gt; (subparagraph title) {#cmdsubparagraph}


<p>Creates a named subparagraph with name &lt;subparagraph-name&gt;. The title of the subparagraph should be specified as the second argument of the <span class="doxyComputerOutput">\subparagraph</span> command.</p>



:::warning
<p>This command only works inside a paragraph of a related page documentation block and <em>not</em> in other documentation blocks!</p>
:::


<hr/>


## \\subsubparagraph &lt;subsubparagraph-name&gt; (subsubparagraph title) {#cmdsubsubparagraph}


<p>Creates a named subsubparagraph with name &lt;subsubparagraph-name&gt;. The title of the subsubparagraph should be specified as the second argument of the <span class="doxyComputerOutput">\subsubparagraph</span> command.</p>



:::warning
<p>This command only works inside a subparagraph of a related page documentation block and <em>not</em> in other documentation blocks!</p>
:::


<hr/>

 <center>

##  ---  Commands for displaying examples  ---  
 </center>

<hr/>


## \\dontinclude\['{lineno}'\] &lt;file-name&gt; {#cmddontinclude}


<p>This command can be used to parse a source file without actually verbatim including it in the documentation (as the <a href="#cmdinclude">\include</a> command does). This is useful if you want to divide the source file into smaller pieces and add documentation between the pieces. Source files or directories can be specified using the <a href="/web-doxygen/docs/pages/config/#cfg_example_path">EXAMPLE_PATH</a> tag of Doxygen's configuration file.</p>


<p>You can add the option <span class="doxyComputerOutput">lineno</span> to enable line numbers for the included code if desired.</p>


<p>You can add the option <span class="doxyComputerOutput">strip</span> that will always hide any special comments from the included code, overruling the <a href="/web-doxygen/docs/pages/config/#cfg_strip_code_comments">STRIP_CODE_COMMENTS</a> setting, or add the option <span class="doxyComputerOutput">nostrip</span> to always show the special comments.</p>


<p>The class and member declarations and definitions inside the code fragment are 'remembered' during the parsing of the comment block that contained the <span class="doxyComputerOutput">\dontinclude</span> command.</p>


<p>For line by line descriptions of source files, one or more lines of the example can be displayed using the <a href="#cmdline">\line</a>, <a href="#cmdskip">\skip</a>, <a href="#cmdskipline">\skipline</a>, and <a href="#cmduntil">\until</a> commands. An internal pointer is used for these commands. The <span class="doxyComputerOutput">\dontinclude</span> command sets the pointer to the first line of the example.</p>


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


<p>Where the example file <span class="doxyComputerOutput">include_test.cpp</span> looks as follows:</p>


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
<dd><p>sections <a href="#cmdline">\line</a>, <a href="#cmdskip">\skip</a>, <a href="#cmdskipline">\skipline</a>, <a href="#cmduntil">\until</a>, and <a href="#cmdinclude">\include</a>.</p></dd>
</dl>


<hr/>


## \\include\['{'option'}'\] &lt;file-name&gt; {#cmdinclude}


<p>This command can be used to include a source file as a block of code. The command takes the name of an include file as an argument. Source files or directories can be specified using the <a href="/web-doxygen/docs/pages/config/#cfg_example_path">EXAMPLE_PATH</a> tag of Doxygen's configuration file.</p>


<p>If &lt;file-name&gt; itself is not unique for the set of example files specified by the <a href="/web-doxygen/docs/pages/config/#cfg_example_path">EXAMPLE_PATH</a> tag, you can include part of the absolute path to disambiguate it.</p>


<p>Using the <span class="doxyComputerOutput">\include</span> command is equivalent to inserting the file into the documentation block and surrounding it with <a href="#cmdcode">\code</a> and <a href="#cmdendcode">\endcode</a> commands.</p>


<p>The main purpose of the <span class="doxyComputerOutput">\include</span> command is to avoid code duplication in case of example blocks that consist of multiple source and header files.</p>


<p>For a line by line description of a source files use the <a href="#cmddontinclude">\dontinclude</a> command in combination with the <a href="#cmdline">\line</a>, <a href="#cmdskip">\skip</a>, <a href="#cmdskipline">\skipline</a>, and <a href="#cmduntil">\until</a> commands.</p>


<p>Alternatively, the <a href="#cmdsnippet">\snippet</a> command can be used to include only a fragment of a source file. For this to work the fragment has to be marked.</p>



:::info
<p>Doxygen's special commands do not work inside blocks of code. It is allowed to nest C-style comments inside a code block though.</p>
:::


<p>The <span class="doxyComputerOutput">option</span> can either be <span class="doxyComputerOutput">lineno</span>, or <span class="doxyComputerOutput">doc</span>, and additionally <span class="doxyComputerOutput">local</span> can be specified.</p>


<ul class="doxyList ">
<li>The <span class="doxyComputerOutput">option</span> <span class="doxyComputerOutput">lineno</span> can be used to enable line numbers for the included code if desired.</li>
<li>The <span class="doxyComputerOutput">option</span> <span class="doxyComputerOutput">doc</span> can be used to treat the file as documentation rather than code.</li>
<li>The <span class="doxyComputerOutput">option</span> <span class="doxyComputerOutput">local</span> can be used make Doxygen interpret the code as if it was in the class or namespace in which the include command appears, rather than the global namespace.</li>
<li>The <span class="doxyComputerOutput">option</span> <span class="doxyComputerOutput">strip</span> can be used to always hide any special comments from the included code, overruling the <a href="/web-doxygen/docs/pages/config/#cfg_strip_code_comments">STRIP_CODE_COMMENTS</a> setting, and option <span class="doxyComputerOutput">nostrip</span> can be used to always show the special comments. These options have no effect in combination with the <span class="doxyComputerOutput">option</span> <span class="doxyComputerOutput">doc</span>.</li>
</ul>

<p>When using option <span class="doxyComputerOutput">doc</span>, there is also the option <span class="doxyComputerOutput">raise</span> that can be specified to raise all sections found in the referenced file by a certain amount. For example</p>



<pre><code>  \include{doc,raise=1} file.dox
</code></pre>


<p>will treat any level 1 <span class="doxyComputerOutput">\section</span> found in <span class="doxyComputerOutput">file.dox</span> as a level 2 <span class="doxyComputerOutput">\subsection</span>, and any level 2 <span class="doxyComputerOutput">\subsection</span> into a level 3 <span class="doxyComputerOutput">\subsubsection</span>, etc. Similarly, for Markdown a <span class="doxyComputerOutput">#</span> section will be treated as a <span class="doxyComputerOutput">##</span> section.</p>


<p>Furthermore, there is the option <span class="doxyComputerOutput">prefix</span> that can be used to add a prefix to each label of the included sections, so that they remain unique. For example:</p>



<pre><code>  \include{doc,prefix=fn_} file.dox
</code></pre>


<p>will treat e.g. <span class="doxyComputerOutput">\section s1</span> found in <span class="doxyComputerOutput">file.dox</span> as if it was specified as <span class="doxyComputerOutput">\section fn_s1</span>.</p>



:::info
<p>The included documentation should not have comment signs in it as they will appear in the documentation as well.</p>
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>sections <a href="#cmdexample">\example</a>, <a href="#cmddontinclude">\dontinclude</a>, <a href="#cmdverbatim">\verbatim</a>, <a href="#cmdincludedoc">\includedoc</a>, and <a href="#cmdsnippet">\snippet</a>.</p></dd>
</dl>


<hr/>


## \\includelineno &lt;file-name&gt; {#cmdincludelineno}


<p>This command is obsolete and is still supported for backward compatibility reasons, it works the same way as <a href="#cmdinclude">\include{lineno}</a></p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>sections <a href="#cmdinclude">\include{lineno}</a>.</p></dd>
</dl>


<hr/>


## \\includedoc\['{'option'}'\] &lt;file-name&gt; {#cmdincludedoc}


<p>This command is obsolete and is still supported for backward compatibility reasons, it works the same way as <a href="#cmdinclude">\include{doc}</a></p>


<p>The <span class="doxyComputerOutput">option</span>s are the same <span class="doxyComputerOutput">option</span>s that can be used with the <span class="doxyComputerOutput">\include</span> when using there the option <span class="doxyComputerOutput">doc</span>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdinclude">\include{doc}</a>.</p></dd>
</dl>


<hr/>


## \\line ( pattern ) {#cmdline}


<p>This command searches line by line through the example that was last included using <a href="#cmdinclude">\include</a> or <a href="#cmddontinclude">\dontinclude</a> until it finds a non-blank line. If that line contains the specified pattern, it is written to the output.</p>


<p>The internal pointer that is used to keep track of the current line in the example, is set to the start of the line following the non-blank line that was found (or to the end of the example if no such line could be found).</p>


<p>See section <a href="#cmddontinclude">\dontinclude</a> for an example.</p>


<hr/>


## \\skip ( pattern ) {#cmdskip}


<p>This command searches line by line through the example that was last included using <a href="#cmdinclude">\include</a> or <a href="#cmddontinclude">\dontinclude</a> until it finds a line that contains the specified pattern.</p>


<p>The internal pointer that is used to keep track of the current line in the example, is set to the start of the line that contains the specified pattern (or to the end of the example if the pattern could not be found).</p>


<p>See section <a href="#cmddontinclude">\dontinclude</a> for an example.</p>


<hr/>


## \\skipline ( pattern ) {#cmdskipline}


<p>This command searches line by line through the example that was last included using <a href="#cmdinclude">\include</a> or <a href="#cmddontinclude">\dontinclude</a> until it finds a line that contains the specified pattern. It then writes the line to the output.</p>


<p>The internal pointer that is used to keep track of the current line in the example, is set to the start of the line following the line that is written (or to the end of the example if the pattern could not be found).</p>


<dl class="doxySectionUser">
<dt>Note:</dt>
<dd>
<p>The command:</p>



<pre><code>\skipline pattern
</code></pre>


<p>is equivalent to:</p>



<pre><code>\skip pattern
\line pattern
</code></pre>
</dd>
</dl>


<p>See section <a href="#cmddontinclude">\dontinclude</a> for an example.</p>


<hr/>


## \\snippet\['{'option'}'\] &lt;file-name&gt; ( block\_id ) {#cmdsnippet}


<p>Where the <a href="#cmdinclude">\include</a> command can be used to include a complete file as source code, this command can be used to quote only a fragment of a source file. In case <span class="doxyComputerOutput">this</span> is used as &lt;file-name&gt; the current file is taken as file to take the snippet from.</p>


<p>For example, the putting the following command in the documentation, references a snippet in file <span class="doxyComputerOutput">example.cpp</span> residing in a subdirectory which should be pointed to by <a href="/web-doxygen/docs/pages/config/#cfg_example_path">EXAMPLE_PATH</a>.</p>



<pre><code>  \snippet snippets/example.cpp Adding a resource
</code></pre>


<p>The text following the file name is the unique identifier for the snippet. This is used to delimit the quoted code in the relevant snippet file as shown in the following example that corresponds to the above <span class="doxyComputerOutput">\snippet</span> command:</p>


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


<p>Note that the lines containing the block markers will not be included, so the output will be:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">document-&gt;addResource(QTextDocument::ImageResource,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    QUrl(</span><span class="doxyHighlightStringLiteral">"mydata://image.png"</span><span class="doxyHighlight">), QVariant(image));</span></span></div>

</div>


<p>Note also that the [block_id] markers should appear exactly twice in the source file.</p>


<p>The <span class="doxyComputerOutput">option</span> can either be <span class="doxyComputerOutput">lineno</span>, <span class="doxyComputerOutput">trimleft</span> or <span class="doxyComputerOutput">doc</span>, and additionally <span class="doxyComputerOutput">local</span> can be specified.</p>


<ul class="doxyList ">
<li>The <span class="doxyComputerOutput">option</span> <span class="doxyComputerOutput">lineno</span> can be used to enable line numbers for the included code if desired.</li>
<li>The <span class="doxyComputerOutput">option</span> <span class="doxyComputerOutput">trimleft</span> can be used to remove the common spacing in front of all lines (also taking in account the setting of the <a href="/web-doxygen/docs/pages/config/#cfg_tab_size">TAB_SIZE</a> tag).</li>
<li>The <span class="doxyComputerOutput">option</span> <span class="doxyComputerOutput">doc</span> can be used to treat the file as documentation rather than code.</li>
<li>The <span class="doxyComputerOutput">option</span> <span class="doxyComputerOutput">local</span> can be used make Doxygen interpret the code as if it was in the class or namespace in which the include command appears, rather than the global namespace.</li>
<li>The <span class="doxyComputerOutput">option</span> <span class="doxyComputerOutput">strip</span> can be used to always hide any special comments from the included code, overruling the <a href="/web-doxygen/docs/pages/config/#cfg_strip_code_comments">STRIP_CODE_COMMENTS</a> setting, and option <span class="doxyComputerOutput">nostrip</span> can be used to always show the special comments. These options have no effect in combination with the <span class="doxyComputerOutput">option</span> <span class="doxyComputerOutput">doc</span>.</li>
</ul>

<p>When using option <span class="doxyComputerOutput">doc</span>, there is also the option <span class="doxyComputerOutput">raise</span> that can be specified to raise all sections found in the referenced file by a certain amount. For example</p>



<pre><code> \snippet{doc,raise=1} file.dox XXX
</code></pre>


<p>will treat any level 1 <span class="doxyComputerOutput">\section</span> found the snippet as a level 2 <span class="doxyComputerOutput">\subsection</span>, and any level 2 <span class="doxyComputerOutput">\subsection</span> into a level 3 <span class="doxyComputerOutput">\subsubsection</span>, etc. Similarly, for Markdown a <span class="doxyComputerOutput">#</span> section will be treated as a <span class="doxyComputerOutput">##</span> section.</p>


<p>Furthermore, there is the option <span class="doxyComputerOutput">prefix</span> that can be used to add a prefix to each label of the included sections, so that they remain unique. For example:</p>



<pre><code> \include{doc,prefix=fn_} file.dox
</code></pre>


<p>will treat e.g. <span class="doxyComputerOutput">\section s1</span> found in <span class="doxyComputerOutput">file.dox</span> as if it was specified as <span class="doxyComputerOutput">\section fn_s1</span>.</p>



:::info
<p>The included documentation should not have comment signs in it as they will appear in the documentation as well.</p>
:::


<p>see section <a href="#cmddontinclude">\dontinclude</a> for an alternative way to include fragments of a source file that does not require markers.</p>


<hr/>


## \\snippetlineno &lt;file-name&gt; ( block\_id ) {#cmdsnippetlineno}


<p>This command is obsolete and is still supported for backward compatibility reasons, it works the same way as <a href="#cmdsnippet">\snippet{lineno}</a></p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>sections <a href="#cmdsnippet">\snippet{lineno}</a></p></dd>
</dl>


<hr/>


## \\snippetdoc\['{'option'}'\] &lt;file-name&gt; ( block\_id ) {#cmdsnippetdoc}


<p>This command is obsolete and is still supported for backward compatibility reasons, it works the same way as <a href="#cmdsnippet">\snippet{doc}</a></p>


<p>The <span class="doxyComputerOutput">option</span>s are the same <span class="doxyComputerOutput">option</span>s that can be used with the <span class="doxyComputerOutput">\snippet</span> when using there the option <span class="doxyComputerOutput">doc</span>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdsnippet">\snippet{doc}</a> and <a href="#cmdinclude">\include{doc}</a>.</p></dd>
</dl>


<hr/>


## \\until ( pattern ) {#cmduntil}


<p>This command writes all lines of the example that was last included using <a href="#cmdinclude">\include</a> or <a href="#cmddontinclude">\dontinclude</a> to the output, until it finds a line containing the specified pattern. The line containing the pattern will be written as well.</p>


<p>The internal pointer that is used to keep track of the current line in the example, is set to the start of the line following last written line (or to the end of the example if the pattern could not be found).</p>


<p>See section <a href="#cmddontinclude">\dontinclude</a> for an example.</p>


<hr/>


## \\verbinclude &lt;file-name&gt; {#cmdverbinclude}


<p>This command includes the contents of the file &lt;file-name&gt; verbatim in the documentation. The command is equivalent to pasting the contents of the file in the documentation and placing <a href="#cmdverbatim">\verbatim</a> and <a href="#cmdendverbatim">\endverbatim</a> commands around it.</p>


<p>Files or directories that Doxygen should look for can be specified using the <a href="/web-doxygen/docs/pages/config/#cfg_example_path">EXAMPLE_PATH</a> tag of Doxygen's configuration file.</p>


<hr/>


## \\htmlinclude\['\[block\]'\] &lt;file-name&gt; {#cmdhtmlinclude}


<p>This command includes the contents of the file &lt;file-name&gt; as is in the HTML documentation and tagged with <span class="doxyComputerOutput">&lt;htmlonly&gt;</span> in the generated XML output. The command is equivalent to pasting the contents of the file in the documentation and placing <a href="#cmdhtmlonly">\htmlonly</a> and <a href="#cmdendhtmlonly">\endhtmlonly</a> commands around it.</p>


<p>Normally the contents of the file indicated by <a href="#cmdhtmlinclude">\htmlinclude</a> is inserted as-is. When you want to insert a HTML fragment that has block scope like a table or list which should appear outside &lt;p&gt;..&lt;/p&gt;, this can lead to invalid HTML. You can use <span class="doxyComputerOutput">\htmlinclude[block]</span> to make Doxygen end the current paragraph and restart after the file is included.</p>


<p>Files or directories that Doxygen should look for can be specified using the <a href="/web-doxygen/docs/pages/config/#cfg_example_path">EXAMPLE_PATH</a> tag of Doxygen's configuration file.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdhtmlonly">\htmlonly</a>, <a href="#cmdlatexinclude">\latexinclude</a>, <a href="#cmdrtfinclude">\rtfinclude</a>, <a href="#cmdmaninclude">\maninclude</a>, <a href="#cmddocbookinclude">\docbookinclude</a> and <a href="#cmdxmlinclude">\xmlinclude</a>.</p></dd>
</dl>


<hr/>


## \\latexinclude &lt;file-name&gt; {#cmdlatexinclude}


<p>This command includes the contents of the file &lt;file-name&gt; as is in the <code>{\LaTeX}</code> documentation and tagged with <span class="doxyComputerOutput">&lt;latexonly&gt;</span> in the generated XML output. The command is equivalent to pasting the contents of the file in the documentation and placing <a href="#cmdlatexonly">\latexonly</a> and <a href="#cmdendlatexonly">\endlatexonly</a> commands around it.</p>


<p>Files or directories that Doxygen should look for can be specified using the <a href="/web-doxygen/docs/pages/config/#cfg_example_path">EXAMPLE_PATH</a> tag of Doxygen's configuration file.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdlatexonly">\latexonly</a>, <a href="#cmdhtmlinclude">\htmlinclude</a>, <a href="#cmdrtfinclude">\rtfinclude</a>, <a href="#cmdmaninclude">\maninclude</a>, <a href="#cmddocbookinclude">\docbookinclude</a> and <a href="#cmdxmlinclude">\xmlinclude</a>.</p></dd>
</dl>


<hr/>


## \\rtfinclude &lt;file-name&gt; {#cmdrtfinclude}


<p>This command includes the contents of the file &lt;file-name&gt; as is in the RTF documentation and tagged with <span class="doxyComputerOutput">&lt;rtfonly&gt;</span> in the generated XML output. The command is equivalent to pasting the contents of the file in the documentation and placing <a href="#cmdrtfonly">\rtfonly</a> and <a href="#cmdendrtfonly">\endrtfonly</a> commands around it.</p>


<p>Files or directories that Doxygen should look for can be specified using the <a href="/web-doxygen/docs/pages/config/#cfg_example_path">EXAMPLE_PATH</a> tag of Doxygen's configuration file.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdrtfonly">\rtfonly</a>, <a href="#cmdhtmlinclude">\htmlinclude</a>, <a href="#cmdlatexinclude">\latexinclude</a>, <a href="#cmdmaninclude">\maninclude</a>, <a href="#cmddocbookinclude">\docbookinclude</a> and <a href="#cmdxmlinclude">\xmlinclude</a>.</p></dd>
</dl>


<hr/>


## \\maninclude &lt;file-name&gt; {#cmdmaninclude}


<p>This command includes the contents of the file &lt;file-name&gt; as is in the MAN documentation and tagged with <span class="doxyComputerOutput">&lt;manonly&gt;</span> in the generated XML output. The command is equivalent to pasting the contents of the file in the documentation and placing <a href="#cmdmanonly">\manonly</a> and <a href="#cmdendmanonly">\endmanonly</a> commands around it.</p>


<p>Files or directories that Doxygen should look for can be specified using the <a href="/web-doxygen/docs/pages/config/#cfg_example_path">EXAMPLE_PATH</a> tag of Doxygen's configuration file.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdmanonly">\manonly</a>, <a href="#cmdhtmlinclude">\htmlinclude</a>, <a href="#cmdlatexinclude">\latexinclude</a>, <a href="#cmdrtfinclude">\rtfinclude</a>, <a href="#cmddocbookinclude">\docbookinclude</a> and <a href="#cmdxmlinclude">\xmlinclude</a>.</p></dd>
</dl>


<hr/>


## \\docbookinclude &lt;file-name&gt; {#cmddocbookinclude}


<p>This command includes the contents of the file &lt;file-name&gt; as is in the DocBook documentation and tagged with <span class="doxyComputerOutput">&lt;docbookonly&gt;</span> in the generated XML output. The command is equivalent to pasting the contents of the file in the documentation and placing <a href="#cmddocbookonly">\docbookonly</a> and <a href="#cmdenddocbookonly">\enddocbookonly</a> commands around it.</p>


<p>Files or directories that Doxygen should look for can be specified using the <a href="/web-doxygen/docs/pages/config/#cfg_example_path">EXAMPLE_PATH</a> tag of Doxygen's configuration file.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmddocbookonly">\docbookonly</a>, <a href="#cmdhtmlinclude">\htmlinclude</a>, <a href="#cmdlatexinclude">\latexinclude</a>, <a href="#cmdrtfinclude">\rtfinclude</a>, <a href="#cmdmaninclude">\maninclude</a> and <a href="#cmdxmlinclude">\xmlinclude</a>.</p></dd>
</dl>


<hr/>


## \\xmlinclude &lt;file-name&gt; {#cmdxmlinclude}


<p>This command includes contents of the file &lt;file-name&gt; as is in the XML documentation. The command is equivalent to pasting the contents of the file in the documentation and placing <a href="#cmdxmlonly">\xmlonly</a> and <a href="#cmdendxmlonly">\endxmlonly</a> commands around it.</p>


<p>Files or directories that Doxygen should look for can be specified using the <a href="/web-doxygen/docs/pages/config/#cfg_example_path">EXAMPLE_PATH</a> tag of Doxygen's configuration file.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdxmlonly">\xmlonly</a>, <a href="#cmdhtmlinclude">\htmlinclude</a>, <a href="#cmdlatexinclude">\latexinclude</a>, <a href="#cmdrtfinclude">\rtfinclude</a>, <a href="#cmdmaninclude">\maninclude</a> and <a href="#cmddocbookinclude">\docbookinclude</a>.</p></dd>
</dl>


<hr/>

 <center>

##  ---  Commands for visual enhancements  ---  
 </center>

## \\a &lt;word&gt; {#cmda}


<p>Displays the argument &lt;word&gt; in italics. Use this command to emphasize words. Use this command to refer to member arguments in the running text.</p>


<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<pre><code>  ... the \a x and \a y coordinates are used to ...
</code></pre>


<p>This will result in the following text:
<br/>

<br/>
 ... the <em>x</em> and <em>y</em> coordinates are used to ...</p>
</dd>
</dl>


<p>Equivalent to <a href="#cmde">\e</a> and <a href="#cmdem">\em</a>. To emphasize multiple words use <a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_EM">&lt;em&gt;</a>multiple words<a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_endEM">&lt;/em&gt;</a>.</p>


<hr/>


## \\arg { item-description } {#cmdarg}


<p>This command has one argument that continues until the first blank line or until another <span class="doxyComputerOutput">\arg</span> is encountered. The command can be used to generate a simple, not nested list of arguments. Each argument should start with a <span class="doxyComputerOutput">\arg</span> command.</p>


<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<p>Typing:</p>



<pre><code>  \arg \c AlignLeft left alignment.
  \arg \c AlignCenter center alignment.
  \arg \c AlignRight right alignment

  No other types of alignment are supported.
</code></pre>


<p>will result in the following text:
<br/>

<br/></p>


<ul class="doxyList ">
<li><span class="doxyComputerOutput">AlignLeft</span> left alignment.</li>
<li><span class="doxyComputerOutput">AlignCenter</span> center alignment.</li>
<li><span class="doxyComputerOutput">AlignRight</span> right alignment</li>
</ul>

<p><br/>
 No other types of alignment are supported.</p>
</dd>
</dl>


<dl class="doxySectionUser">
<dt>Note:</dt>
<dd><p>For nested lists, HTML commands should be used.</p></dd>
</dl>


<p>Equivalent to <a href="#cmdli">\li</a></p>


<hr/>


## \\b &lt;word&gt; {#cmdb}


<p>Displays the argument &lt;word&gt; using a bold font. Equivalent to <a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_B">&lt;b&gt;</a>word<a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_endB">&lt;/b&gt;</a>. To put multiple words in bold use <a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_B">&lt;b&gt;</a>multiple words<a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_endB">&lt;/b&gt;</a>.</p>


<hr/>


## \\c &lt;word&gt; {#cmdc}


<p>Displays the argument &lt;word&gt; using a typewriter font. Use this to refer to a word of code. Equivalent to <a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_TT">&lt;tt&gt;</a>word<a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_endTT">&lt;/tt&gt;</a>.</p>


<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<p>Typing:</p>



<pre><code>     ... This function returns \c void and not \c int ...
</code></pre>


<p>will result in the following text:
<br/>

<br/>
 ... This function returns <span class="doxyComputerOutput">void</span> and not <span class="doxyComputerOutput">int</span> ...</p>
</dd>
</dl>


<p>Equivalent to <a href="#cmdp">\p</a>. To have multiple words in typewriter font use <a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_TT">&lt;tt&gt;</a>multiple words<a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_endTT">&lt;/tt&gt;</a>.</p>


<hr/>


## \\code\['{'&lt;word&gt;'}'\] {#cmdcode}


<p>Starts a block of code. A code block is treated differently from ordinary text. It is interpreted as source code. The names of classes and members and other documented entities are automatically replaced by links to the documentation.</p>


<p>By default the language that is assumed for syntax highlighting is based on the location where the <span class="doxyComputerOutput">\code</span> block was found. If this part of a Python file for instance, the syntax highlight will be done according to the Python syntax.</p>


<p>If it is unclear from the context which language is meant (for instance the comment is in a <span class="doxyComputerOutput">.txt</span> or <span class="doxyComputerOutput">.markdown</span> file) then you can also explicitly indicate the language, by putting the file extension typically that Doxygen associated with the language in curly brackets after the code block. Here is an example:</p>



<pre><code>  \code{.py}
  class Python:
     pass
  \endcode

  \code{.cpp}
  class Cpp {};
  \endcode
</code></pre>


<p>If the contents of the code block are in a language that Doxygen cannot parse, Doxygen will just show the output as-is. You can make this explicit using .unparsed, or by giving some other extension that Doxygen doesn't support, e.g.</p>



<pre><code>  \code{.unparsed}
  Show this as-is please
  \endcode

  \code{.sh}
  echo "This is a shell script"
  \endcode
</code></pre>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdendcode">\endcode</a> and section <a href="#cmdverbatim">\verbatim</a>.</p></dd>
</dl>


<hr/>


## \\copydoc &lt;link-object&gt; {#cmdcopydoc}


<p>Copies a documentation block from the object specified by &lt;link-object&gt; and pastes it at the location of the command. This command can be useful to avoid cases where a documentation block would otherwise have to be duplicated or it can be used to extend the documentation of an inherited member.</p>


<p>The link object can point to a member (of a class, file or group), a class, a namespace, a group, a page, or a file (checked in that order). Note that if the object pointed to is a member (function, variable, typedef, etc), the compound (class, file, or group) containing it should also be documented for the copying to work.</p>


<p>To copy the documentation for a member of a class one can, for instance, put the following in the documentation:</p>



<pre><code>  /*! @copydoc MyClass::myfunction()
   *  More documentation.
   */
</code></pre>


<p>if the member is overloaded, you should specify the argument types explicitly (without spaces!), like in the following:</p>



<pre><code>  //! @copydoc MyClass::myfunction(type1,type2)
</code></pre>


<p>Qualified names are only needed if the context in which the documentation block is found requires them.</p>


<p>The <span class="doxyComputerOutput">\copydoc</span> command can be used recursively, but cycles in the <span class="doxyComputerOutput">\copydoc</span> relation will be broken and flagged as an error.</p>


<p>Note that <span class="doxyComputerOutput">\copydoc foo()</span> is roughly equivalent to doing:</p>



<pre><code>  \brief \copybrief foo()
  \details \copydetails foo()
</code></pre>


<p>See <a href="#cmdcopybrief">\copybrief</a> and <a href="#cmdcopydetails">\copydetails</a> for copying only the brief or detailed part of the comment block.</p>


<hr/>


## \\copybrief &lt;link-object&gt; {#cmdcopybrief}


<p>Works in a similar way as <a href="#cmdcopydoc">\copydoc</a> but will only copy the brief description, not the detailed documentation.</p>


<hr/>


## \\copydetails &lt;link-object&gt; {#cmdcopydetails}


<p>Works in a similar way as <a href="#cmdcopydoc">\copydoc</a> but will only copy the detailed documentation, not the brief description.</p>


<hr/>


## \\docbookonly {#cmddocbookonly}


<p>Starts a block of text that only will be verbatim included in the generated DocBook documentation and tagged with <span class="doxyComputerOutput">&lt;docbookonly&gt;</span> in the generated XML output. The block ends with a <a href="#cmdenddocbookonly">\enddocbookonly</a> command.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdmanonly">\manonly</a>, <a href="#cmdlatexonly">\latexonly</a>, <a href="#cmdrtfonly">\rtfonly</a>, <a href="#cmdxmlonly">\xmlonly</a>, <a href="#cmdhtmlonly">\htmlonly</a> and <a href="#cmddocbookinclude">\docbookinclude</a>.</p></dd>
</dl>


<hr/>


## \\dot \["caption"\] \[&lt;sizeindication&gt;=&lt;size&gt;\] {#cmddot}


<p>Starts a text fragment which should contain a valid description of a dot graph. The text fragment ends with <a href="#cmdenddot">\enddot</a>. Doxygen will pass the text on to dot and include the resulting image (and image map) into the output.</p>


<p>The first argument is optional and can be used to specify the caption that is displayed below the image. This argument has to be specified between quotes even if it does not contain any spaces. The quotes are stripped before the caption is displayed.</p>


<p>The second argument is also optional and can be used to specify the width or height of the image. For a description of the possibilities see the paragraph <a href="#image_sizeindicator">Size indication</a> with the <a href="#cmdimage">\image</a> command.</p>


<p>The nodes of a graph can be made clickable by using the URL attribute. By using the command <a href="#cmdref">\ref</a> inside the URL value you can conveniently link to an item inside Doxygen. Here is an example:</p>



:::info
<p>usage of this command requires that <a href="/web-doxygen/docs/pages/config/#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span></p>
:::



:::info
<p>Doxygen creates a temporary file that is automatically removed unless the <a href="/web-doxygen/docs/pages/config/#cfg_dot_cleanup">DOT_CLEANUP</a> tag is set to <span class="doxyComputerOutput">NO</span>.</p>
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


<p>This command will produce an emoji character given its name.</p>


<p>The supported names are the ones also supported by GitHub and listed here <a href="https://gist.github.com/rxaviers/7360908">https://gist.github.com/rxaviers/7360908</a></p>


<p>You can use the name with or without colons, i.e. <span class="doxyComputerOutput">\emoji smile</span> is the same as writing <span class="doxyComputerOutput">\emoji :smile:</span>. When an emoji is not supported the name with by places in the text with in between colons, i.e. <span class="doxyComputerOutput">\emoji unsupported</span> will produce <span class="doxyComputerOutput">:unsupported:</span> in the output. Doxygen will also give a warning message.</p>


<p>See also the <a href="/web-doxygen/docs/pages/emojisup">emoji support page</a> for details.</p>


<hr/>


## \\msc \["caption"\] \[&lt;sizeindication&gt;=&lt;size&gt;\] {#cmdmsc}


<p>Starts a text fragment which should contain a valid description of a message sequence chart. See <a href="https://www.mcternan.me.uk/mscgen/">https://www.mcternan.me.uk/mscgen/</a> for examples. The text fragment ends with <a href="#cmdendmsc">\endmsc</a>.</p>


<p>The first argument is optional and can be used to specify the caption that is displayed below the image. This argument has to be specified between quotes even if it does not contain any spaces. The quotes are stripped before the caption is displayed.</p>


<p>The second argument is also optional and can be used to specify the width or height of the image. For a description of the possibilities see the paragraph <a href="#image_sizeindicator">Size indication</a> with the <a href="#cmdimage">\image</a> command.</p>



:::info
<p>The text fragment should only include the part of the message sequence chart that is within the <span class="doxyComputerOutput">msc {...}</span> block (this is different from <a href="#cmdmscfile">\mscfile</a>).</p>
:::



:::info
<p>mscgen is now built in into Doxygen</p>
:::



:::info
<p>Doxygen creates a temporary file that is automatically removed unless the <a href="/web-doxygen/docs/pages/config/#cfg_dot_cleanup">DOT_CLEANUP</a> tag is set to <span class="doxyComputerOutput">NO</span>.</p>
:::


<p>Here is an example of the use of the <span class="doxyComputerOutput">\msc</span> command.</p>


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
<dd><p>section <a href="#cmdmscfile">\mscfile</a>.</p></dd>
</dl>


<hr/>


## \\startuml \['{'option\[,option\]'}'\] \["caption"\] \[&lt;sizeindication&gt;=&lt;size&gt;\] {#cmdstartuml}


<p>Starts a text fragment which should contain a valid description of a PlantUML diagram. See <a href="https://plantuml.com/">https://plantuml.com/</a> for examples. The text fragment ends with <a href="#cmdenduml">\enduml</a>.</p>



:::info
<p>You need to install Java and the PlantUML's jar file, if you want to use this command. When using PlantUML in <code>{\LaTeX}</code> you have to download some more <span class="doxyComputerOutput">jar</span> files, for details see the PlantUML documentation. This also is valid for the <span class="doxyComputerOutput">&lt;engine&gt;</span>s <span class="doxyComputerOutput">latex</span> and <span class="doxyComputerOutput">math</span>. The location of the PlantUML file should be specified using <a href="/web-doxygen/docs/pages/config/#cfg_plantuml_jar_path">PLANTUML_JAR_PATH</a>. The other jar files should also reside in this directory.</p>
:::



:::info
<p>The use of the <span class="doxyComputerOutput">&lt;engine&gt;</span> <span class="doxyComputerOutput">ditaa</span> is not possible in <code>{\LaTeX}</code> as PlantUML only supports the <span class="doxyComputerOutput">png</span> format and Doxygen requires, temporary, <span class="doxyComputerOutput">eps</span> output.</p>
:::


<p>Not all diagrams can be created with the PlantUML <span class="doxyComputerOutput">@startuml</span> command but need another PlantUML <span class="doxyComputerOutput">@start...</span> command. This will look like <span class="doxyComputerOutput">@start&lt;engine&gt;</span> where currently supported are the following <span class="doxyComputerOutput">&lt;engine&gt;</span>s: <span class="doxyComputerOutput">uml</span>, <span class="doxyComputerOutput">bpm</span>, <span class="doxyComputerOutput">wire</span>, <span class="doxyComputerOutput">dot</span>, <span class="doxyComputerOutput">ditaa</span>, <span class="doxyComputerOutput">salt</span>, <span class="doxyComputerOutput">math</span>, <span class="doxyComputerOutput">latex</span>, <span class="doxyComputerOutput">gantt</span>, <span class="doxyComputerOutput">mindmap</span>, <span class="doxyComputerOutput">wbs</span>, <span class="doxyComputerOutput">yaml</span>, <span class="doxyComputerOutput">creole</span>, <span class="doxyComputerOutput">json</span>, <span class="doxyComputerOutput">flow</span>, <span class="doxyComputerOutput">board</span>, <span class="doxyComputerOutput">git</span>, <span class="doxyComputerOutput">hcl</span>, <span class="doxyComputerOutput">regex</span>, <span class="doxyComputerOutput">ebnf</span>, <span class="doxyComputerOutput">files</span>, <span class="doxyComputerOutput">chen</span> and <span class="doxyComputerOutput">chronology</span>. By default the <span class="doxyComputerOutput">&lt;engine&gt;</span> is <span class="doxyComputerOutput">uml</span>. The <span class="doxyComputerOutput">&lt;engine&gt;</span> can be specified as an option. Also the file to write the resulting image to can be specified by means of an option, see the description of the first (optional) argument for details. Of course only one <span class="doxyComputerOutput">&lt;engine&gt;</span> can be specified and also the filename can only be specified once.</p>


<p>The first argument is optional and is for compatibility with running PlantUML as a preprocessing step before running Doxygen, you can also add the name of the image file after <span class="doxyComputerOutput">\startuml</span> and inside curly brackets as option, i.e.</p>



<pre><code>  @startuml{myimage.png} "Image Caption" width=5cm
  Alice -&gt; Bob : Hello
  @enduml
</code></pre>


<p>When the name of the image is specified, Doxygen will generate an image with that name. Without the name Doxygen will choose a name automatically.</p>


<p>The second argument is optional and can be used to specify the caption that is displayed below the image. This argument has to be specified between quotes even if it does not contain any spaces. The quotes are stripped before the caption is displayed.</p>


<p>The third argument is also optional and can be used to specify the width or height of the image. For a description of the possibilities see the paragraph <a href="#image_sizeindicator">Size indication</a> with the <a href="#cmdimage">\image</a> command.</p>



:::info
<p>Doxygen does not support the Plantuml commands like <span class="doxyComputerOutput">@startjson</span>, by design, directly but the support can be accomplished, by the user, by adding to the Doxygen settings file:</p>



<pre><code>  ALIASES += startjson=@startuml{json}
  ALIASES += endjson=@enduml
</code></pre>
:::



:::info
<p>Doxygen creates a temporary file that is automatically removed unless the <a href="/web-doxygen/docs/pages/config/#cfg_dot_cleanup">DOT_CLEANUP</a> tag is set to <span class="doxyComputerOutput">NO</span>.</p>
:::


<p>Here is an example of the use of the <span class="doxyComputerOutput">\startuml</span> command.</p>


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


<p>Inserts an image generated by dot from &lt;file&gt; into the documentation.</p>


<p>The first argument specifies the file name of the image. Doxygen will look for files in the paths (or files) that you specified after the <a href="/web-doxygen/docs/pages/config/#cfg_dotfile_dirs">DOTFILE_DIRS</a> tag. If the dot file is found it will be used as an input file to the dot tool. The resulting image will be put into the correct output directory. If the dot file name contains spaces you'll have to put quotes ("...") around it.</p>


<p>The second argument is optional and can be used to specify the caption that is displayed below the image. This argument has to be specified between quotes even if it does not contain any spaces. The quotes are stripped before the caption is displayed.</p>


<p>The third argument is also optional and can be used to specify the width or height of the image. For a description of the possibilities see the paragraph <a href="#image_sizeindicator">Size indication</a> with the <a href="#cmdimage">\image</a> command.</p>



:::info
<p>usage of this command requires that <a href="/web-doxygen/docs/pages/config/#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span></p>
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmddot">\dot</a>.</p></dd>
</dl>


<hr/>


## \\mscfile &lt;file&gt; \["caption"\] \[&lt;sizeindication&gt;=&lt;size&gt;\] {#cmdmscfile}


<p>Inserts an image generated by mscgen from &lt;file&gt; into the documentation. See <a href="https://www.mcternan.me.uk/mscgen/">https://www.mcternan.me.uk/mscgen/</a> for examples.</p>


<p>The first argument specifies the file name of the image. Doxygen will look for files in the paths (or files) that you specified after the <a href="/web-doxygen/docs/pages/config/#cfg_mscfile_dirs">MSCFILE_DIRS</a> tag. If the msc file is found it will be used as an input file to the built in mscgen tool. The resulting image will be put into the correct output directory. If the msc file name contains spaces you'll have to put quotes ("...") around it.</p>


<p>The second argument is optional and can be used to specify the caption that is displayed below the image. This argument has to be specified between quotes even if it does not contain any spaces. The quotes are stripped before the caption is displayed.</p>


<p>The third argument is also optional and can be used to specify the width or height of the image. For a description of the possibilities see the paragraph <a href="#image_sizeindicator">Size indication</a> with the <a href="#cmdimage">\image</a> command.</p>



:::info
<p>The text fragment should include the part message of the sequence chart as well as the starting <span class="doxyComputerOutput">msc {</span> and ending <span class="doxyComputerOutput">}</span> (this is different from <a href="#cmdmsc">\msc</a>).</p>
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdmsc">\msc</a>.</p></dd>
</dl>


<hr/>


## \\diafile &lt;file&gt; \["caption"\] \[&lt;sizeindication&gt;=&lt;size&gt;\] {#cmddiafile}


<p>Inserts an image made in dia from &lt;file&gt; into the documentation.</p>


<p>The first argument specifies the file name of the image. Doxygen will look for files in the paths (or files) that you specified after the <a href="/web-doxygen/docs/pages/config/#cfg_diafile_dirs">DIAFILE_DIRS</a> tag. If the dia file is found it will be used as an input file dia. The resulting image will be put into the correct output directory. If the dia file name contains spaces you'll have to put quotes ("...") around it.</p>


<p>The second argument is optional and can be used to specify the caption that is displayed below the image. This argument has to be specified between quotes even if it does not contain any spaces. The quotes are stripped before the caption is displayed.</p>


<p>The third argument is also optional and can be used to specify the width or height of the image. For a description of the possibilities see the paragraph <a href="#image_sizeindicator">Size indication</a> with the <a href="#cmdimage">\image</a> command.</p>


<hr/>


## \\doxyconfig &lt;config\_option&gt; {#cmddoxyconfig}


<p>Displays the value of the configuration option <span class="doxyComputerOutput">&lt;config_option&gt;</span> as used in Doxygen's configuration file that is in use when this command is processed.</p>


<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<p>When creating this manual the following:</p>



<pre><code>  ... Project name = \doxyconfig PROJECT_NAME ...
</code></pre>


<p>gives:
<br/>
 ... Project name = Manual ...</p>
</dd>
</dl>


<hr/>


## \\e &lt;word&gt; {#cmde}


<p>Displays the argument &lt;word&gt; in italics. Use this command to emphasize words.</p>


<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<p>Typing:</p>



<pre><code>  ... this is a \e really good example ...
</code></pre>


<p>will result in the following text:
<br/>

<br/>
 ... this is a <em>really</em> good example ...</p>
</dd>
</dl>


<p>Equivalent to <a href="#cmda">\a</a> and <a href="#cmdem">\em</a>. To emphasize multiple words use <a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_EM">&lt;em&gt;</a>multiple words<a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_endEM">&lt;/em&gt;</a>.</p>


<hr/>


## \\em &lt;word&gt; {#cmdem}


<p>Displays the argument &lt;word&gt; in italics. Use this command to emphasize words.</p>


<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<p>Typing:</p>



<pre><code>  ... this is a \em really good example ...
</code></pre>


<p>will result in the following text:
<br/>

<br/>
 ... this is a <em>really</em> good example ...</p>
</dd>
</dl>


<p>Equivalent to <a href="#cmda">\a</a> and <a href="#cmde">\e</a>. To emphasize multiple words use <a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_EM">&lt;em&gt;</a>multiple words<a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_endEM">&lt;/em&gt;</a>.</p>


<hr/>


## \\endcode {#cmdendcode}


<p>Ends a block of code.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdcode">\code</a></p></dd>
</dl>


<hr/>


## \\enddocbookonly {#cmdenddocbookonly}


<p>Ends a block of text that was started with a <a href="#cmddocbookonly">\docbookonly</a> command.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmddocbookonly">\docbookonly</a>.</p></dd>
</dl>


<hr/>


## \\enddot {#cmdenddot}


<p>Ends a block that was started with <a href="#cmddot">\dot</a>.</p>


<hr/>


## \\endmsc {#cmdendmsc}


<p>Ends a block that was started with <a href="#cmdmsc">\msc</a>.</p>


<hr/>


## \\enduml {#cmdenduml}


<p>Ends a block that was started with <a href="#cmdstartuml">\startuml</a>.</p>


<hr/>


## \\plantumlfile &lt;file&gt; \["caption"\] \[&lt;sizeindication&gt;=&lt;size&gt;\] {#cmdplantumlfile}


<p>Inserts an image made in PlantUml from &lt;file&gt; into the documentation.</p>


<p>The first argument specifies the file name of the image. Doxygen will look for files in the paths (or files) that you specified after the <a href="/web-doxygen/docs/pages/config/#cfg_plantumlfile_dirs">PLANTUMLFILE_DIRS</a> tag. If the plantuml file is found it will be used as an input file for the plantuml program. The resulting image will be put into the correct output directory. If the plantuml file name contains spaces you'll have to put quotes ("...") around it.</p>


<p>The second argument is optional and can be used to specify the caption that is displayed below the image. This argument has to be specified between quotes even if it does not contain any spaces. The quotes are stripped before the caption is displayed.</p>


<p>The third argument is also optional and can be used to specify the width or height of the image. For a description of the possibilities see the paragraph <a href="#image_sizeindicator">Size indication</a> with the <a href="#cmdimage">\image</a> command.</p>


<hr/>


## \\endhtmlonly {#cmdendhtmlonly}


<p>Ends a block of text that was started with a <a href="#cmdhtmlonly">\htmlonly</a> command.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdhtmlonly">\htmlonly</a>.</p></dd>
</dl>


<hr/>


## \\endlatexonly {#cmdendlatexonly}


<p>Ends a block of text that was started with a <a href="#cmdlatexonly">\latexonly</a> command.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdlatexonly">\latexonly</a>.</p></dd>
</dl>


<hr/>


## \\endmanonly {#cmdendmanonly}


<p>Ends a block of text that was started with a <a href="#cmdmanonly">\manonly</a> command.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdmanonly">\manonly</a>.</p></dd>
</dl>


<hr/>


## \\endrtfonly {#cmdendrtfonly}


<p>Ends a block of text that was started with a <a href="#cmdrtfonly">\rtfonly</a> command.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdrtfonly">\rtfonly</a>.</p></dd>
</dl>


<hr/>


## \\endverbatim {#cmdendverbatim}


<p>Ends a block of text that was started with a <a href="#cmdverbatim">\verbatim</a> command.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdverbatim">\verbatim</a>.</p></dd>
</dl>


<hr/>


## \\endxmlonly {#cmdendxmlonly}


<p>Ends a block of text that was started with a <a href="#cmdxmlonly">\xmlonly</a> command.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdxmlonly">\xmlonly</a>.</p></dd>
</dl>


<hr/>


## \\f$ {#cmdfdollar}


<p>Marks the start and end of an in-text formula.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="/web-doxygen/docs/pages/formulas">formulas</a> for an example.</p></dd>
</dl>


<hr/>


## \\f( {#cmdfrndopen}


<p>Marks the start of an in-text formula, but contrary to <a href="#cmdfdollar">\f$</a> it will not explicitly open the math-mode in <code>{\LaTeX}</code>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdfrndclose">\f)</a> and section <a href="/web-doxygen/docs/pages/formulas">formulas</a>.</p></dd>
</dl>


<hr/>


## \\f) {#cmdfrndclose}


<p>Marks the end of an in-text formula started with <a href="#cmdfrndopen">\f(</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdfrndopen">\f(</a> and section <a href="/web-doxygen/docs/pages/formulas">formulas</a>.</p></dd>
</dl>


<hr/>


## \\f\[ {#cmdfbropen}


<p>Marks the start of a long formula that is displayed centered on a separate line.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdfbrclose">\f]</a> and section <a href="/web-doxygen/docs/pages/formulas">formulas</a>.</p></dd>
</dl>


<hr/>


## \\f\] {#cmdfbrclose}


<p>Marks the end of a long formula that is displayed centered on a separate line.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdfbropen">\f[</a> and section <a href="/web-doxygen/docs/pages/formulas">formulas</a>.</p></dd>
</dl>


<hr/>


## \\f{environment}{ {#cmdfcurlyopen}


<p>Marks the start of a formula that is in a specific environment.</p>



:::info
<p>The second <span class="doxyComputerOutput">{</span> is optional and is only to help editors (such as <span class="doxyComputerOutput">Vim</span>) to do proper syntax highlighting by making the number of opening and closing braces the same.</p>
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdfcurlyclose">\f}</a> and section <a href="/web-doxygen/docs/pages/formulas">formulas</a>.</p></dd>
</dl>


<hr/>


## \\f} {#cmdfcurlyclose}


<p>Marks the end of a formula that is in a specific environment.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdfcurlyopen">\f{</a> and section <a href="/web-doxygen/docs/pages/formulas">formulas</a>.</p></dd>
</dl>


<hr/>


## \\htmlonly\['\[block\]'\] {#cmdhtmlonly}


<p>Starts a block of text that only will be verbatim included in the generated HTML documentation and tagged with <span class="doxyComputerOutput">&lt;htmlonly&gt;</span> in the generated XML output. The block ends with a <a href="#cmdendhtmlonly">\endhtmlonly</a> command.</p>


<p>This command can be used to include HTML code that is too complex for Doxygen (i.e. applets, java-scripts, and HTML tags that require specific attributes).</p>


<p>Normally the contents between <a href="#cmdhtmlonly">\htmlonly</a> and <a href="#cmdendhtmlonly">\endhtmlonly</a> is inserted as-is. When you want to insert a HTML fragment that has block scope like a table or list which should appear outside &lt;p&gt;..&lt;/p&gt;, this can lead to invalid HTML. You can use <span class="doxyComputerOutput">\htmlonly[block]</span> to make Doxygen end the current paragraph and restart it after <span class="doxyComputerOutput">\endhtmlonly</span>.</p>



:::info
<p>environment variables (like $(HOME) ) are resolved inside a HTML-only block.</p>
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>section <a href="#cmdmanonly">\manonly</a>, <a href="#cmdlatexonly">\latexonly</a>, <a href="#cmdrtfonly">\rtfonly</a>, <a href="#cmdxmlonly">\xmlonly</a>, <a href="#cmddocbookonly">\docbookonly</a>, and <a href="#cmdhtmlinclude">\htmlinclude</a>.</p></dd>
</dl>


<hr/>


## \\image\['{'option\[,option\]'}'\] &lt;format&gt; &lt;file&gt; \["caption"\] \[&lt;sizeindication&gt;=&lt;size&gt;\] {#cmdimage}


<p>Inserts an image into the documentation. This command is format specific, so if you want to insert an image for more than one format you'll have to repeat this command for each format.</p>


<p>The first argument specifies the output format in which the image should be embedded. Currently, the following values are supported: <span class="doxyComputerOutput">html</span>, <span class="doxyComputerOutput">latex</span>, <span class="doxyComputerOutput">docbook</span>, <span class="doxyComputerOutput">rtf</span> and <span class="doxyComputerOutput">xml</span>.</p>


<p>The second argument specifies the file name of the image. Doxygen will look for files in the paths (or files) that you specified after the <a href="/web-doxygen/docs/pages/config/#cfg_image_path">IMAGE_PATH</a> tag. If the image is found it will be copied to the correct output directory. If the image name contains spaces you'll have to put quotes ("...") around the name. You can also specify an absolute URL instead of a file name, but then Doxygen does not copy the image nor check its existence.</p>


<p>The third argument is optional and can be used to specify the caption that is displayed below the image. This argument has to be specified on a single line and between quotes even if it does not contain any spaces. The quotes are stripped before the caption is displayed.</p>


<p>The fourth argument is also optional and can be used to specify the width or height of the image. This can be useful for <code>{\LaTeX}</code> or DocBook output (i.e. format=<span class="doxyComputerOutput">latex</span> or format=<span class="doxyComputerOutput">docbook</span>). <a id="image_sizeindicator"></a></p>


<dl class="doxySectionUser">
<dt>Size indication</dt>
<dd><p>The <span class="doxyComputerOutput">sizeindication</span> can specify the width or height to be used (or a combination). The size specifier in <code>{\LaTeX}</code> (for example <span class="doxyComputerOutput">10cm</span> or <span class="doxyComputerOutput">4in</span> or a symbolic width like <span class="doxyComputerOutput">\textwidth</span>).</p></dd>
</dl>


<p>Currently only the options <span class="doxyComputerOutput">inline</span> and <span class="doxyComputerOutput">anchor</span> are supported. In case the option <span class="doxyComputerOutput">inline</span> is specified the image is placed "in the line", when a caption is present it is shown in HTML as tooltip (ignored for the other formats). For the <span class="doxyComputerOutput">anchor</span> option the syntax is: <span class="doxyComputerOutput">anchor:&lt;anchorId&gt;</span>.</p>


<p>Here is example of a comment block:</p>



<pre><code>  /*! Here is a snapshot of my new application:
   *  \image html application.jpg
   *  \image latex application.eps "My application" width=10cm
   */
</code></pre>


<p>And this is an example of how the relevant part of the configuration file may look:</p>



<pre><code>  IMAGE_PATH     = my_image_dir
</code></pre>



:::warning
<p>The image format for HTML is limited to what your browser supports.
<br/>
For <code>{\LaTeX}</code>, the image format must be supported by the <code>{\LaTeX}</code> <span class="doxyComputerOutput">\includegraphics</span> command i.e. Encapsulated PostScript (eps), Portable network graphics (png), Joint photographic experts group (jpg / jpeg). 
<br/>

<br/>
 Doxygen does not check if the image is in the correct format. So <em>you</em> have to make sure this is the case!</p>
:::


<hr/>


## \\latexonly {#cmdlatexonly}


<p>Starts a block of text that only will be verbatim included in the generated <code>{\LaTeX}</code> documentation and tagged with <span class="doxyComputerOutput">&lt;latexonly&gt;</span> in the generated XML output. The block ends with a <a href="#cmdendlatexonly">\endlatexonly</a> command.</p>


<p>This command can be used to include <code>{\LaTeX}</code> code that is too complex for Doxygen (i.e. images, formulas, special characters). You can use the <a href="#cmdhtmlonly">\htmlonly</a> and <a href="#cmdendhtmlonly">\endhtmlonly</a> pair to provide a proper HTML alternative.</p>


<p><b>Note:</b> environment variables (like $(HOME) ) are resolved inside a <code>{\LaTeX}</code>-only block.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>sections <a href="#cmdrtfonly">\rtfonly</a>, <a href="#cmdxmlonly">\xmlonly</a>, <a href="#cmdmanonly">\manonly</a>, <a href="#cmdhtmlonly">\htmlonly</a>, <a href="#cmddocbookonly">\docbookonly</a>, and <a href="#cmdlatexinclude">\latexinclude</a>.</p></dd>
</dl>


<hr/>


## \\manonly {#cmdmanonly}


<p>Starts a block of text that only will be verbatim included in the generated MAN documentation and tagged with <span class="doxyComputerOutput">&lt;manonly&gt;</span> in the generated XML output. The block ends with a <a href="#cmdendmanonly">\endmanonly</a> command.</p>


<p>This command can be used to include groff code directly into MAN pages. You can use the <a href="#cmdhtmlonly">\htmlonly</a> and <a href="#cmdendhtmlonly">\endhtmlonly</a> and <a href="#cmdlatexonly">\latexonly</a> and <a href="#cmdendlatexonly">\endlatexonly</a> pairs to provide proper HTML and <code>{\LaTeX}</code> alternatives.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>sections <a href="#cmdhtmlonly">\htmlonly</a>, <a href="#cmdxmlonly">\xmlonly</a>, <a href="#cmdrtfonly">\rtfonly</a>, <a href="#cmdlatexonly">\latexonly</a>, <a href="#cmddocbookonly">\docbookonly</a> and <a href="#cmdmaninclude">\maninclude</a>.</p></dd>
</dl>


<hr/>


## \\li { item-description } {#cmdli}


<p>This command has one argument that continues until the first blank line or until another <span class="doxyComputerOutput">\li</span> is encountered. The command can be used to generate a simple, not nested list of arguments. Each argument should start with a <span class="doxyComputerOutput">\li</span> command.</p>


<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<p>Typing:</p>



<pre><code>  \li \c AlignLeft left alignment.
  \li \c AlignCenter center alignment.
  \li \c AlignRight right alignment

  No other types of alignment are supported.
</code></pre>


<p>will result in the following text:
<br/>

<br/></p>


<ul class="doxyList ">
<li><span class="doxyComputerOutput">AlignLeft</span> left alignment.</li>
<li><span class="doxyComputerOutput">AlignCenter</span> center alignment.</li>
<li><span class="doxyComputerOutput">AlignRight</span> right alignment</li>
</ul>

<p><br/>
 No other types of alignment are supported.</p>
</dd>
</dl>


<dl class="doxySectionUser">
<dt>Note:</dt>
<dd><p>For nested lists, HTML commands should be used.</p></dd>
</dl>


<p>Equivalent to <a href="#cmdarg">\arg</a></p>


<hr/>


## \\n {#cmdn}


<p>Forces a new line. Equivalent to <a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_BR">&lt;br&gt;</a> and inspired by the <span class="doxyComputerOutput">printf</span> function.</p>


<hr/>


## \\p &lt;word&gt; {#cmdp}


<p>Displays the parameter &lt;word&gt; using a typewriter font. You can use this command to refer to member function parameters in the running text.</p>


<dl class="doxySectionUser">
<dt>Example:</dt>
<dd>
<pre><code>  ... the \p x and \p y coordinates are used to ...
</code></pre>


<p>This will result in the following text:
<br/>

<br/>
 ... the <span class="doxyComputerOutput">x</span> and <span class="doxyComputerOutput">y</span> coordinates are used to ...</p>
</dd>
</dl>


<p>Equivalent to <a href="#cmdc">\c</a>. To have multiple words in typewriter font use <a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_TT">&lt;tt&gt;</a>multiple words<a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_endTT">&lt;/tt&gt;</a>.</p>


<hr/>


## \\rtfonly {#cmdrtfonly}


<p>Starts a block of text that only will be verbatim included in the generated RTF documentation and tagged with <span class="doxyComputerOutput">&lt;rtfonly&gt;</span> in the generated XML output. The block ends with a <a href="#cmdendrtfonly">\endrtfonly</a> command.</p>


<p>This command can be used to include RTF code that is too complex for Doxygen.</p>


<p><b>Note:</b> environment variables (like $(HOME) ) are resolved inside a RTF-only block.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>sections <a href="#cmdmanonly">\manonly</a>, <a href="#cmdxmlonly">\xmlonly</a>, <a href="#cmdlatexonly">\latexonly</a>, <a href="#cmdhtmlonly">\htmlonly</a>, <a href="#cmddocbookonly">\docbookonly</a> and <a href="#cmdrtfinclude">\rtfinclude</a>.</p></dd>
</dl>


<hr/>


## \\verbatim {#cmdverbatim}


<p>Starts a block of text that will be verbatim included in the documentation. The block should end with a <a href="#cmdendverbatim">\endverbatim</a> command. All commands are disabled in a verbatim block.</p>



:::warning
<p>Make sure you include a <a href="#cmdendverbatim">\endverbatim</a> command for each <span class="doxyComputerOutput">\verbatim</span> command or the parser will get confused!</p>
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>sections <a href="#cmdcode">\code</a>, <a href="#cmdendverbatim">\endverbatim</a> and <a href="#cmdverbinclude">\verbinclude</a>.</p></dd>
</dl>


<hr/>


## \\xmlonly {#cmdxmlonly}


<p>Starts a block of text that only will be verbatim included in the generated XML output. The block ends with a <a href="#cmdendxmlonly">\endxmlonly</a> command.</p>


<p>This command can be used to include custom XML tags.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>sections <a href="#cmdmanonly">\manonly</a>, <a href="#cmdrtfonly">\rtfonly</a>, <a href="#cmdlatexonly">\latexonly</a>, <a href="#cmdhtmlonly">\htmlonly</a>, and <a href="#cmddocbookonly">\docbookonly</a>.</p></dd>
</dl>


<hr/>


## \\\\ {#cmdbackslash}


<p>This command writes a backslash character (<span class="doxyComputerOutput">\</span>) to the output. The backslash has to be escaped in some cases because Doxygen uses it to detect commands.</p>


<hr/>


## \\@ {#cmdat}


<p>This command writes an at-sign (<span class="doxyComputerOutput">@</span>) to the output. The at-sign has to be escaped in some cases because Doxygen uses it to detect Javadoc commands.</p>


<hr/>


## \\\~\[LanguageId\] {#cmdtilde}


<p>This command enables/disables a language specific filter. This can be used to put documentation for different language into one comment block and use the <a href="/web-doxygen/docs/pages/config/#cfg_output_language">OUTPUT_LANGUAGE</a> tag to filter out only a specific language. Use <span class="doxyComputerOutput">\~language_id</span> to enable output for a specific language only and <span class="doxyComputerOutput">\~</span> to enable output for all languages (this is also the default mode).</p>


<p>Example:</p>



<pre><code>/*! \~english This is English \~dutch Dit is Nederlands \~german Dies ist
    Deutsch. \~ output for all languages.
 */
</code></pre>


<hr/>


## \\&amp; {#cmdamp}


<p>This command writes the <span class="doxyComputerOutput">&amp;</span> character to the output. This character has to be escaped because it has a special meaning in HTML.</p>


<hr/>


## \\$ {#cmddollar}


<p>This command writes the <span class="doxyComputerOutput">$</span> character to the output. This character has to be escaped in some cases, because it is used to expand environment variables.</p>


<hr/>


## \\# {#cmdhash}


<p>This command writes the <span class="doxyComputerOutput">#</span> character to the output. This character has to be escaped in some cases, because it is used to refer to documented entities.</p>


<hr/>


## \\&lt; {#cmdlt}


<p>This command writes the <span class="doxyComputerOutput">&lt;</span> character to the output. This character has to be escaped because it has a special meaning in HTML.</p>


<hr/>


## \\&gt; {#cmdgt}


<p>This command writes the <span class="doxyComputerOutput">&gt;</span> character to the output. This character has to be escaped because it has a special meaning in HTML.</p>


<hr/>


## \\% {#cmdperc}


<p>This command writes the <span class="doxyComputerOutput">%</span> character to the output. This character has to be escaped in some cases, because it is used to prevent auto-linking to a word that is also a documented class or struct.</p>


<hr/>


## \\" {#cmdquot}


<p>This command writes the <span class="doxyComputerOutput">"</span> character to the output. This character has to be escaped in some cases, because it is used in pairs to indicate an unformatted text fragment.</p>


<hr/>


## \\ {#cmdchardot}


<p>This command writes a dot (<span class="doxyComputerOutput">.</span>) to the output. This can be useful to prevent ending a brief description when <a href="/web-doxygen/docs/pages/config/#cfg_javadoc_autobrief">JAVADOC_AUTOBRIEF</a> or <a href="/web-doxygen/docs/pages/config/#cfg_qt_autobrief">QT_AUTOBRIEF</a> is enabled or to prevent starting a numbered list when the dot follows a number at the start of a line.</p>


<hr/>


## \\? {#cmdquest}


<p>This command writes a question mark (<span class="doxyComputerOutput">?</span>) to the output. This can be useful to prevent ending a brief description when <a href="/web-doxygen/docs/pages/config/#cfg_javadoc_autobrief">JAVADOC_AUTOBRIEF</a> or <a href="/web-doxygen/docs/pages/config/#cfg_qt_autobrief">QT_AUTOBRIEF</a> is enabled.</p>


<hr/>


## \\! {#cmdexclam}


<p>This command writes a exclamation mark (<span class="doxyComputerOutput">!</span>) to the output. This can be useful to prevent ending a brief description when <a href="/web-doxygen/docs/pages/config/#cfg_javadoc_autobrief">JAVADOC_AUTOBRIEF</a> or <a href="/web-doxygen/docs/pages/config/#cfg_qt_autobrief">QT_AUTOBRIEF</a> is enabled.</p>


<hr/>


## \\= {#cmdeq}


<p>This command writes an equal sign (<span class="doxyComputerOutput">=</span>) to the output. This character sequence has to be escaped in some cases, because it is used in Markdown header processing.</p>


<hr/>


## \\:: {#cmddcolon}


<p>This command writes a double colon (<span class="doxyComputerOutput">::</span>) to the output. This character sequence has to be escaped in some cases, because it is used to reference to documented entities.</p>


<hr/>


## \\| {#cmdpipe}


<p>This command writes a pipe symbol (|) to the output. This character has to be escaped in some cases, because it is used for Markdown tables.</p>


<hr/>


## \\-- {#cmdndash}


<p>This command writes two dashes (--) to the output. This allows writing two consecutive dashes to the output instead of one n-dash character (–).</p>


<hr/>


## \\--- {#cmdmdash}


<p>This command writes three dashes (---) to the output. This allows writing three consecutive dashes to the output instead of one m-dash character (—).</p>


<hr/>

 
Go to the <a href="/docs/pages/htmlcmds/">next</a> section or return to the
 <a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
