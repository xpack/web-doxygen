---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/threadpool
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ThreadPool` Class Reference

<p>Class managing a pool of worker threads. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class ThreadPool { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/threadpool-h">src/threadpool.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a786db3b3e0aac5ca3e43c37025ab22b0">ThreadPool</a> (std::size_t N=1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>start N threads in the thread pool. <a href="#a786db3b3e0aac5ca3e43c37025ab22b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8af7ebd9779dcab6e0a48f80e8962d08">ThreadPool</a> (const ThreadPool &amp;)=delete</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1bbb23b57e3ae24cdc7df015c49fba1">ThreadPool</a> (ThreadPool &amp;&amp;)=delete</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44d3d2ab618970605e684efc216655eb">~ThreadPool</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>deletes the thread pool by finishing all threads <a href="#a44d3d2ab618970605e684efc216655eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/threadpool">ThreadPool</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afec5f97d2b512da75aa10897ef12a2a8">operator=</a> (const ThreadPool &amp;)=delete</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/threadpool">ThreadPool</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad979aa170c8c04f5fb5f1d941ef9d5a2">operator=</a> (ThreadPool &amp;&amp;)=delete</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class F, typename ... Args&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a90398abffcd9d81901195160315b1bc9">queue</a> (F &amp;&amp;f, Args &amp;&amp;... args) -&gt; std::future&lt; decltype(f(args...))&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Queue the callable function <em>f</em> for the threads to execute. <a href="#a90398abffcd9d81901195160315b1bc9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fc76489de6e11c259ccf8f072fe135d">finish</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>finish enques a "stop the thread" message for every thread, then waits for them to finish <a href="#a1fc76489de6e11c259ccf8f072fe135d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a630a5230a8d6a8ba5c11b88ccc91c32b">threadTask</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8111098c66bef75793ca4f954c46b7c2">m_mutex</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::condition_variable</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea3e5ca7e471639fdd30c8bde0670616">m_cond</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::deque&lt; std::function&lt; void()&gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7779e4d1698359b2057d696a7d162f57">m_work</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::future&lt; void &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa297cb723c1d6d8ac4fad073fd9ccfa0">m_finished</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Class managing a pool of worker threads.</p>


<p>Work can be queued by passing a function to <a href="#a90398abffcd9d81901195160315b1bc9">queue()</a>. A future will be returned that can be used to obtain the result of the function after execution.</p>


<p>Usage example:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a786db3b3e0aac5ca3e43c37025ab22b0">ThreadPool</a> pool(10);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">std::vector&lt; std::future&lt; int &gt; &gt; results;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0;i&lt;10;i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> run = [](</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> i*i; };</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  results.emplace_back(pool.queue(std::bind(run,i)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;f : results)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  printf(</span><span class="doxyHighlightStringLiteral">"Result %d:\n"</span><span class="doxyHighlight">, f.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Definition at line 47 of file <a href="/web-doxygen/docs/api/files/src/threadpool-h">threadpool.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ThreadPool() {#a786db3b3e0aac5ca3e43c37025ab22b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadPool::ThreadPool (std::size_t N=1)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>start N threads in the thread pool.</p>

<p>Definition at line 51 of file <a href="/web-doxygen/docs/api/files/src/threadpool-h">threadpool.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a786db3b3e0aac5ca3e43c37025ab22b0">51</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a786db3b3e0aac5ca3e43c37025ab22b0">ThreadPool</a>(std::size_t N=1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (std::size_t i = 0; i &lt; N; ++i)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// each thread is a std::async running thread_task():</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aa297cb723c1d6d8ac4fad073fd9ccfa0">m_finished</a>.push_back(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">            std::async(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">              std::launch::async,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">              [</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">]{ <a href="#a630a5230a8d6a8ba5c11b88ccc91c32b">threadTask</a>(); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">              )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">            );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#aa297cb723c1d6d8ac4fad073fd9ccfa0">m_finished</a> and <a href="#a630a5230a8d6a8ba5c11b88ccc91c32b">threadTask</a>.</p>


<p>Referenced by <a href="#afec5f97d2b512da75aa10897ef12a2a8">operator=</a>, <a href="#ad979aa170c8c04f5fb5f1d941ef9d5a2">operator=</a>, <a href="#a8af7ebd9779dcab6e0a48f80e8962d08">ThreadPool</a> and <a href="#ad1bbb23b57e3ae24cdc7df015c49fba1">ThreadPool</a>.</p>

</div>
</div>

### ThreadPool() {#a8af7ebd9779dcab6e0a48f80e8962d08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadPool::ThreadPool (const <a href="/web-doxygen/docs/api/classes/threadpool">ThreadPool</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-doxygen/docs/api/files/src/threadpool-h">threadpool.h</a>.</p>


<p>Reference <a href="#a786db3b3e0aac5ca3e43c37025ab22b0">ThreadPool</a>.</p>

</div>
</div>

### ThreadPool() {#ad1bbb23b57e3ae24cdc7df015c49fba1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadPool::ThreadPool (<a href="/web-doxygen/docs/api/classes/threadpool">ThreadPool</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-doxygen/docs/api/files/src/threadpool-h">threadpool.h</a>.</p>


<p>Reference <a href="#a786db3b3e0aac5ca3e43c37025ab22b0">ThreadPool</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ThreadPool() {#a44d3d2ab618970605e684efc216655eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadPool::~ThreadPool ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>deletes the thread pool by finishing all threads</p>

<p>Definition at line 65 of file <a href="/web-doxygen/docs/api/files/src/threadpool-h">threadpool.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a44d3d2ab618970605e684efc216655eb">65</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a44d3d2ab618970605e684efc216655eb">~ThreadPool</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1fc76489de6e11c259ccf8f072fe135d">finish</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a1fc76489de6e11c259ccf8f072fe135d">finish</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#afec5f97d2b512da75aa10897ef12a2a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadPool &amp; ThreadPool::operator= (const <a href="/web-doxygen/docs/api/classes/threadpool">ThreadPool</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-doxygen/docs/api/files/src/threadpool-h">threadpool.h</a>.</p>


<p>Reference <a href="#a786db3b3e0aac5ca3e43c37025ab22b0">ThreadPool</a>.</p>

</div>
</div>

### operator=() {#ad979aa170c8c04f5fb5f1d941ef9d5a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadPool &amp; ThreadPool::operator= (<a href="/web-doxygen/docs/api/classes/threadpool">ThreadPool</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-doxygen/docs/api/files/src/threadpool-h">threadpool.h</a>.</p>


<p>Reference <a href="#a786db3b3e0aac5ca3e43c37025ab22b0">ThreadPool</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### finish() {#a1fc76489de6e11c259ccf8f072fe135d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ThreadPool::finish ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>finish enques a "stop the thread" message for every thread, then waits for them to finish</p>

<p>Definition at line 100 of file <a href="/web-doxygen/docs/api/files/src/threadpool-h">threadpool.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1fc76489de6e11c259ccf8f072fe135d">100</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1fc76489de6e11c259ccf8f072fe135d">finish</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">        std::unique_lock&lt;std::mutex&gt; l(<a href="#a8111098c66bef75793ca4f954c46b7c2">m_mutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight">&amp;&amp; u : <a href="#aa297cb723c1d6d8ac4fad073fd9ccfa0">m_finished</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">          (void)u; </span><span class="doxyHighlightComment">//unused_variable, to silence the compiler warning about unused variables</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a7779e4d1698359b2057d696a7d162f57">m_work</a>.emplace_back(); </span><span class="doxyHighlightComment">// insert empty function object to signal abort</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aea3e5ca7e471639fdd30c8bde0670616">m_cond</a>.notify_all();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aa297cb723c1d6d8ac4fad073fd9ccfa0">m_finished</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#aea3e5ca7e471639fdd30c8bde0670616">m_cond</a>, <a href="#aa297cb723c1d6d8ac4fad073fd9ccfa0">m_finished</a>, <a href="#a8111098c66bef75793ca4f954c46b7c2">m_mutex</a> and <a href="#a7779e4d1698359b2057d696a7d162f57">m_work</a>.</p>


<p>Referenced by <a href="#a44d3d2ab618970605e684efc216655eb">~ThreadPool</a>.</p>

</div>
</div>

### queue() {#a90398abffcd9d81901195160315b1bc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class F, typename ... Args&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::future&lt; decltype(f(args...))&gt; ThreadPool::queue (F &amp;&amp; f, Args &amp;&amp;... args)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Queue the callable function <em>f</em> for the threads to execute.</p>


<p>A future of the return type of the function is returned to capture the result.</p>


<p>Definition at line 77 of file <a href="/web-doxygen/docs/api/files/src/threadpool-h">threadpool.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a90398abffcd9d81901195160315b1bc9">77</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> <a href="#a90398abffcd9d81901195160315b1bc9">queue</a>(F&amp;&amp; f, Args&amp;&amp;... args) -&gt; std::future&lt;</span><span class="doxyHighlightKeyword">decltype</span><span class="doxyHighlight">(f(args...))&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// We wrap the function object into a packaged task, splitting</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// execution from the return value.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// Since the packaged_task object is not copyable, we create it on the heap</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// and capture it via a shared pointer in a lambda and then assign that lambda</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// to a std::function.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight">RetType = </span><span class="doxyHighlightKeyword">decltype</span><span class="doxyHighlight">(f(args...));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ptr = std::make_shared&lt; std::packaged_task&lt;RetType()&gt; &gt;(std::forward&lt;F&gt;(f), std::forward&lt;Args&gt;(args)...);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> taskFunc = [ptr]() { </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ptr-&gt;valid()) (*ptr)(); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> r=ptr-&gt;get_future(); </span><span class="doxyHighlightComment">// get the return value before we hand off the task</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">        std::unique_lock&lt;std::mutex&gt; l(<a href="#a8111098c66bef75793ca4f954c46b7c2">m_mutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a7779e4d1698359b2057d696a7d162f57">m_work</a>.emplace_back(taskFunc);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aea3e5ca7e471639fdd30c8bde0670616">m_cond</a>.notify_one(); </span><span class="doxyHighlightComment">// wake a thread to work on the task</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> r; </span><span class="doxyHighlightComment">// return the future result of the task</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#aea3e5ca7e471639fdd30c8bde0670616">m_cond</a>, <a href="#a8111098c66bef75793ca4f954c46b7c2">m_mutex</a> and <a href="#a7779e4d1698359b2057d696a7d162f57">m_work</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#adc2cc0c0248747e3608de552a9947cfb">computeTooltipTexts</a>, <a href="/web-doxygen/docs/api/classes/formulamanager/#ab24723d7cedd2c780f895fea971fb484">FormulaManager::createFormulasTexFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0cb7d6c9c783e1376142dbe33d01f821">generateDocsForClassList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a57a6bc5421d2bc55208fa100ee7d4a0b">generateFileDocs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a6d0fb628b1fc96844bb2836317a3ce5a">generateFileSources</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#adb4a42f193668dfef2c26197a3b3dd59">generateJSTreeFiles</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a61b713e61e238a458b7a64ef221973a4">generateNamespaceClassDocs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#af69cff788100ddb682f88658018d3969">parseFilesMultiThreading</a> and <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#ae8e105816d60cf56b75c2d13f9d85048">writeJavaScriptSearchIndex</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### threadTask() {#a630a5230a8d6a8ba5c11b88ccc91c32b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ThreadPool::threadTask ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-doxygen/docs/api/files/src/threadpool-h">threadpool.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a630a5230a8d6a8ba5c11b88ccc91c32b">116</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a630a5230a8d6a8ba5c11b88ccc91c32b">threadTask</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// pop a task off the queue:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">        std::function&lt;void()&gt; f;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// usual thread-safe queue code:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">          std::unique_lock&lt;std::mutex&gt; l(<a href="#a8111098c66bef75793ca4f954c46b7c2">m_mutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a7779e4d1698359b2057d696a7d162f57">m_work</a>.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#aea3e5ca7e471639fdd30c8bde0670616">m_cond</a>.wait(l,[&amp;]{</span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> !<a href="#a7779e4d1698359b2057d696a7d162f57">m_work</a>.empty();});</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">          f = std::move(<a href="#a7779e4d1698359b2057d696a7d162f57">m_work</a>.front());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a7779e4d1698359b2057d696a7d162f57">m_work</a>.pop_front();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// if the function is empty, it means we are asked to abort</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!f) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// run the task</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">        f();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#aea3e5ca7e471639fdd30c8bde0670616">m_cond</a>, <a href="#a8111098c66bef75793ca4f954c46b7c2">m_mutex</a> and <a href="#a7779e4d1698359b2057d696a7d162f57">m_work</a>.</p>


<p>Referenced by <a href="#a786db3b3e0aac5ca3e43c37025ab22b0">ThreadPool</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_cond {#aea3e5ca7e471639fdd30c8bde0670616}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::condition_variable ThreadPool::m_cond</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-doxygen/docs/api/files/src/threadpool-h">threadpool.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aea3e5ca7e471639fdd30c8bde0670616">142</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::condition_variable <a href="#aea3e5ca7e471639fdd30c8bde0670616">m_cond</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a1fc76489de6e11c259ccf8f072fe135d">finish</a>, <a href="#a90398abffcd9d81901195160315b1bc9">queue</a> and <a href="#a630a5230a8d6a8ba5c11b88ccc91c32b">threadTask</a>.</p>

</div>
</div>

### m\_finished {#aa297cb723c1d6d8ac4fad073fd9ccfa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::future&lt;void&gt; &gt; ThreadPool::m_finished</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-doxygen/docs/api/files/src/threadpool-h">threadpool.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa297cb723c1d6d8ac4fad073fd9ccfa0">148</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::vector&lt; std::future&lt;void&gt; &gt; <a href="#aa297cb723c1d6d8ac4fad073fd9ccfa0">m_finished</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a1fc76489de6e11c259ccf8f072fe135d">finish</a> and <a href="#a786db3b3e0aac5ca3e43c37025ab22b0">ThreadPool</a>.</p>

</div>
</div>

### m\_mutex {#a8111098c66bef75793ca4f954c46b7c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex ThreadPool::m_mutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-doxygen/docs/api/files/src/threadpool-h">threadpool.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8111098c66bef75793ca4f954c46b7c2">141</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::mutex <a href="#a8111098c66bef75793ca4f954c46b7c2">m_mutex</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a1fc76489de6e11c259ccf8f072fe135d">finish</a>, <a href="#a90398abffcd9d81901195160315b1bc9">queue</a> and <a href="#a630a5230a8d6a8ba5c11b88ccc91c32b">threadTask</a>.</p>

</div>
</div>

### m\_work {#a7779e4d1698359b2057d696a7d162f57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::deque&lt; std::function&lt;void()&gt; &gt; ThreadPool::m_work</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-doxygen/docs/api/files/src/threadpool-h">threadpool.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7779e4d1698359b2057d696a7d162f57">145</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::deque&lt; std::function&lt;void()&gt; &gt; <a href="#a7779e4d1698359b2057d696a7d162f57">m_work</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a1fc76489de6e11c259ccf8f072fe135d">finish</a>, <a href="#a90398abffcd9d81901195160315b1bc9">queue</a> and <a href="#a630a5230a8d6a8ba5c11b88ccc91c32b">threadTask</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/threadpool-h">threadpool.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
