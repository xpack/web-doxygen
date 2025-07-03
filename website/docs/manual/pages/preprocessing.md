---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /pages/preprocessing
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - page
toc_max_heading_level: 4

---

<div class="doxyPage">

# Preprocessing




<p>Source files that are used as input to Doxygen can be parsed by Doxygen's built-in C-preprocessor.</p>


<p>By default Doxygen does only partial preprocessing. That is, it evaluates conditional compilation statements (like <span class="doxyComputerOutput">#if</span>) and evaluates macro definitions, but it does not perform macro expansion.</p>


<p>So if you have the following code fragment</p>



<pre><code>#define VERSION 200
#define CONST_STRING const char *

#if VERSION &gt;= 200
  static CONST_STRING version = "2.xx";
#else
  static CONST_STRING version = "1.xx";
#endif
</code></pre>


<p>Then by default Doxygen will feed the following to its parser:</p>



<pre><code>#define VERSION
#define CONST_STRING

  static CONST_STRING version = "2.xx";
</code></pre>


<p>You can disable all preprocessing by setting <a href="/web-doxygen/docs/pages/config/#cfg_enable_preprocessing">ENABLE_PREPROCESSING</a> to <span class="doxyComputerOutput">NO</span> in the configuration file. In the case above Doxygen will then read both statements, i.e.:</p>



<pre><code>  static CONST_STRING version = "2.xx";
  static CONST_STRING version = "1.xx";
</code></pre>


<p>In case you want to expand the <span class="doxyComputerOutput">CONST_STRING</span> macro, you should set the <a href="/web-doxygen/docs/pages/config/#cfg_macro_expansion">MACRO_EXPANSION</a> tag in the configuration file to <span class="doxyComputerOutput">YES</span>. Then the result after preprocessing becomes:</p>



<pre><code>#define VERSION
#define CONST_STRING

  static const char * version = "2.xx";
</code></pre>


<p>Note that Doxygen will now expand <em>all</em> macro definitions (recursively if needed). This is often too much. Therefore, Doxygen also allows you to expand only those defines that you explicitly specify. For this you have to set the <a href="/web-doxygen/docs/pages/config/#cfg_expand_only_predef">EXPAND_ONLY_PREDEF</a> tag to <span class="doxyComputerOutput">YES</span> and specify the macro definitions after the <a href="/web-doxygen/docs/pages/config/#cfg_predefined">PREDEFINED</a> or <a href="/web-doxygen/docs/pages/config/#cfg_expand_as_defined">EXPAND_AS_DEFINED</a> tag.</p>


<p>A typically example where some help from the preprocessor is needed is when dealing with the language extension from Microsoft: <span class="doxyComputerOutput">__declspec</span>. The same goes for GNU's <span class="doxyComputerOutput">__attribute__</span> extension. Here is an example function.</p>



<pre><code>extern "C" void __declspec(dllexport) ErrorMsg( String aMessage,...);
</code></pre>


<p>When nothing is done, Doxygen will be confused and see <span class="doxyComputerOutput">__declspec</span> as some sort of function. To help Doxygen one typically uses the following preprocessor settings:</p>



<pre><code>ENABLE_PREPROCESSING   = YES
MACRO_EXPANSION        = YES
EXPAND_ONLY_PREDEF     = YES
PREDEFINED             = __declspec(x)=
</code></pre>


<p>This will make sure the <span class="doxyComputerOutput">__declspec(dllexport)</span> is removed before Doxygen parses the source code.</p>


<p>Similar settings can be used for removing <span class="doxyComputerOutput">__attribute__</span> expressions from the input:</p>



<pre><code>ENABLE_PREPROCESSING   = YES
MACRO_EXPANSION        = YES
EXPAND_ONLY_PREDEF     = YES
PREDEFINED             = __attribute__(x)=
</code></pre>


<p>For a more complex example, suppose you have the following obfuscated code fragment of an abstract base class called <span class="doxyComputerOutput">IUnknown:</span></p>



<pre><code>/*! A reference to an IID */
#ifdef __cplusplus
#define REFIID const IID &amp;
#else
#define REFIID const IID *
#endif


/*! The IUnknown interface */
DECLARE_INTERFACE(IUnknown)
{
  STDMETHOD(HRESULT,QueryInterface) (THIS_ REFIID iid, void **ppv) PURE;
  STDMETHOD(ULONG,AddRef) (THIS) PURE;
  STDMETHOD(ULONG,Release) (THIS) PURE;
};
</code></pre>


<p>without macro expansion Doxygen will get confused, but we may not want to expand the <span class="doxyComputerOutput">REFIID</span> macro, because it is documented and the user that reads the documentation should use it when implementing the interface.</p>


<p>By setting the following in the configuration file:</p>



<pre><code>ENABLE_PREPROCESSING = YES
MACRO_EXPANSION      = YES
EXPAND_ONLY_PREDEF   = YES
PREDEFINED           = "DECLARE_INTERFACE(name)=class name" \
                       "STDMETHOD(result,name)=virtual result name" \
                       "PURE= = 0" \
                       THIS_= \
                       THIS= \
               __cplusplus
</code></pre>


<p>we can make sure that the proper result is fed to Doxygen's parser:</p>



<pre><code>/*! A reference to an IID */
#define REFIID

/*! The IUnknown interface */
class  IUnknown
{
  virtual  HRESULT   QueryInterface ( REFIID iid, void **ppv) = 0;
  virtual  ULONG   AddRef () = 0;
  virtual  ULONG   Release () = 0;
};
</code></pre>


<p>Note that the <a href="/web-doxygen/docs/pages/config/#cfg_predefined">PREDEFINED</a> tag accepts function like macro definitions (like <span class="doxyComputerOutput">DECLARE_INTERFACE</span> ), normal macro substitutions (like <span class="doxyComputerOutput">PURE</span> and <span class="doxyComputerOutput">THIS</span>) and plain defines (like <span class="doxyComputerOutput">__cplusplus</span>).</p>


<p>Note also that preprocessor definitions that are normally defined automatically by the preprocessor (like <span class="doxyComputerOutput">__cplusplus</span>), have to be defined by hand with Doxygen's parser (this is done because these defines are often platform/compiler specific).</p>


<p>In some cases you may want to substitute a macro name or function by something else without exposing the result to further macro substitution. You can do this but using the <span class="doxyComputerOutput">:=</span> operator instead of <span class="doxyComputerOutput">=</span></p>


<p>As an example suppose we have the following piece of code:</p>



<pre><code>#define QList QListT
class QListT
{
};
</code></pre>


<p>Then the only way to get Doxygen interpret this as a class definition for class <span class="doxyComputerOutput">QList</span> is to define:</p>



<pre><code>PREDEFINED = QListT:=QList
</code></pre>


<p>Here is an example provided by Valter Minute and Reyes Ponce that helps Doxygen to wade through the boilerplate code in Microsoft's ATL &amp; MFC libraries:</p>



<pre><code>PREDEFINED           = "DECLARE_INTERFACE(name)=class name" \
                       "STDMETHOD(result,name)=virtual result name" \
                       "PURE= = 0" \
                       THIS_= \
                       THIS= \
                       DECLARE_REGISTRY_RESOURCEID=// \
                       DECLARE_PROTECT_FINAL_CONSTRUCT=// \
                       "DECLARE_AGGREGATABLE(Class)= " \
                       "DECLARE_REGISTRY_RESOURCEID(Id)= " \
                       DECLARE_MESSAGE_MAP= \
                       BEGIN_MESSAGE_MAP=/* \
                       END_MESSAGE_MAP=*/// \
                       BEGIN_COM_MAP=/* \
                       END_COM_MAP=*/// \
                       BEGIN_PROP_MAP=/* \
                       END_PROP_MAP=*/// \
                       BEGIN_MSG_MAP=/* \
                       END_MSG_MAP=*/// \
                       BEGIN_PROPERTY_MAP=/* \
                       END_PROPERTY_MAP=*/// \
                       BEGIN_OBJECT_MAP=/* \
                       END_OBJECT_MAP()=*/// \
                       DECLARE_VIEW_STATUS=// \
                       "STDMETHOD(a)=HRESULT a" \
                       "ATL_NO_VTABLE= " \
                       "__declspec(a)= " \
                       BEGIN_CONNECTION_POINT_MAP=/* \
                       END_CONNECTION_POINT_MAP=*/// \
                       "DECLARE_DYNAMIC(class)= " \
                       "IMPLEMENT_DYNAMIC(class1, class2)= " \
                       "DECLARE_DYNCREATE(class)= " \
                       "IMPLEMENT_DYNCREATE(class1, class2)= " \
                       "IMPLEMENT_SERIAL(class1, class2, class3)= " \
                       "DECLARE_MESSAGE_MAP()= " \
                       TRY=try \
                       "CATCH_ALL(e)= catch(...)" \
                       END_CATCH_ALL= \
                       "THROW_LAST()= throw"\
                       "RUNTIME_CLASS(class)=class" \
                       "MAKEINTRESOURCE(nId)=nId" \
                       "IMPLEMENT_REGISTER(v, w, x, y, z)= " \
                       "ASSERT(x)=assert(x)" \
                       "ASSERT_VALID(x)=assert(x)" \
                       "TRACE0(x)=printf(x)" \
                       "OS_ERR(A,B)={ #A, B }" \
                       __cplusplus \
                       "DECLARE_OLECREATE(class)= " \
                       "BEGIN_DISPATCH_MAP(class1, class2)= " \
                       "BEGIN_INTERFACE_MAP(class1, class2)= " \
                       "INTERFACE_PART(class, id, name)= " \
                       "END_INTERFACE_MAP()=" \
                       "DISP_FUNCTION(class, name, function, result, id)=" \
                       "END_DISPATCH_MAP()=" \
                       "IMPLEMENT_OLECREATE2(class, name, id1, id2, id3, id4,\
                        id5, id6, id7, id8, id9, id10, id11)="
</code></pre>


<p>As you can see Doxygen's preprocessor is quite powerful, but if you want even more flexibility you can always write an input filter and specify it after the <a href="/web-doxygen/docs/pages/config/#cfg_input_filter">INPUT_FILTER</a> tag or the <a href="/web-doxygen/docs/pages/config/#cfg_filter_patterns">FILTER_PATTERNS</a> tag (or the <a href="/web-doxygen/docs/pages/config/#cfg_filter_source_patterns">FILTER_SOURCE_PATTERNS</a> tag).
<br/>
 If you are unsure what the effect of the filter will be you can run Doxygen as follows: <span class="doxyComputerOutput">doxygen -d filteroutput</span>.</p>


<p>If you are unsure what the effect of Doxygen's preprocessing will be you can run Doxygen as follows:</p>



<pre><code>  doxygen -d Preprocessor
</code></pre>


<p>or when the line numbers are not wanted:</p>



<pre><code>  doxygen -d Preprocessor -d NoLineno
</code></pre>


<p>This will instruct Doxygen to dump the input sources to standard output after preprocessing has been done (Hint: set <span class="doxyComputerOutput">QUIET = YES</span> and <span class="doxyComputerOutput">WARNINGS = NO</span> in the configuration file to disable any other output).</p>


<p>Note preprocessing is not done for all languages. Preprocessing is enabled for files that use the "C" scanner (with the exception of 'java', 'd' and 'php'), Fortran files (only in case the extension contains at least one upper case character) and vhdl files.</p>

 
Go to the <a href="/docs/pages/autolink/">next</a> section or return to the
 <a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
