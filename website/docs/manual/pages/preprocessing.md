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




Source files that are used as input to Doxygen can be parsed by Doxygen's built-in C-preprocessor.

By default Doxygen does only partial preprocessing. That is, it evaluates conditional compilation statements (like <code>#if</code>) and evaluates macro definitions, but it does not perform macro expansion.

So if you have the following code fragment


<pre><code>#define VERSION 200
#define CONST_STRING const char *

#if VERSION &gt;= 200
  static CONST_STRING version = "2.xx";
#else
  static CONST_STRING version = "1.xx";
#endif
</code></pre>


Then by default Doxygen will feed the following to its parser:


<pre><code>#define VERSION
#define CONST_STRING

  static CONST_STRING version = "2.xx";
</code></pre>


You can disable all preprocessing by setting <a href="/web-doxygen/docs/pages/config/#cfg_enable_preprocessing">ENABLE\_PREPROCESSING</a> to <code>NO</code> in the configuration file. In the case above Doxygen will then read both statements, i.e.:


<pre><code>  static CONST_STRING version = "2.xx";
  static CONST_STRING version = "1.xx";
</code></pre>


In case you want to expand the <code>CONST\_STRING</code> macro, you should set the <a href="/web-doxygen/docs/pages/config/#cfg_macro_expansion">MACRO\_EXPANSION</a> tag in the configuration file to <code>YES</code>. Then the result after preprocessing becomes:


<pre><code>#define VERSION
#define CONST_STRING

  static const char * version = "2.xx";
</code></pre>


Note that Doxygen will now expand <em>all</em> macro definitions (recursively if needed). This is often too much. Therefore, Doxygen also allows you to expand only those defines that you explicitly specify. For this you have to set the <a href="/web-doxygen/docs/pages/config/#cfg_expand_only_predef">EXPAND\_ONLY\_PREDEF</a> tag to <code>YES</code> and specify the macro definitions after the <a href="/web-doxygen/docs/pages/config/#cfg_predefined">PREDEFINED</a> or <a href="/web-doxygen/docs/pages/config/#cfg_expand_as_defined">EXPAND\_AS\_DEFINED</a> tag.

A typically example where some help from the preprocessor is needed is when dealing with the language extension from Microsoft: <code>\_\_declspec</code>. The same goes for GNU's <code>\_\_attribute\_\_</code> extension. Here is an example function.


<pre><code>extern "C" void __declspec(dllexport) ErrorMsg( String aMessage,...);
</code></pre>


When nothing is done, Doxygen will be confused and see <code>\_\_declspec</code> as some sort of function. To help Doxygen one typically uses the following preprocessor settings:


<pre><code>ENABLE_PREPROCESSING   = YES
MACRO_EXPANSION        = YES
EXPAND_ONLY_PREDEF     = YES
PREDEFINED             = __declspec(x)=
</code></pre>


This will make sure the <code>\_\_declspec(dllexport)</code> is removed before Doxygen parses the source code.

Similar settings can be used for removing <code>\_\_attribute\_\_</code> expressions from the input:


<pre><code>ENABLE_PREPROCESSING   = YES
MACRO_EXPANSION        = YES
EXPAND_ONLY_PREDEF     = YES
PREDEFINED             = __attribute__(x)=
</code></pre>


For a more complex example, suppose you have the following obfuscated code fragment of an abstract base class called <code>IUnknown:</code>


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


without macro expansion Doxygen will get confused, but we may not want to expand the <code>REFIID</code> macro, because it is documented and the user that reads the documentation should use it when implementing the interface.

By setting the following in the configuration file:


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


we can make sure that the proper result is fed to Doxygen's parser:


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


Note that the <a href="/web-doxygen/docs/pages/config/#cfg_predefined">PREDEFINED</a> tag accepts function like macro definitions (like <code>DECLARE\_INTERFACE</code> ), normal macro substitutions (like <code>PURE</code> and <code>THIS</code>) and plain defines (like <code>\_\_cplusplus</code>).

Note also that preprocessor definitions that are normally defined automatically by the preprocessor (like <code>\_\_cplusplus</code>), have to be defined by hand with Doxygen's parser (this is done because these defines are often platform/compiler specific).

In some cases you may want to substitute a macro name or function by something else without exposing the result to further macro substitution. You can do this but using the <code>:=</code> operator instead of <code>=</code>

As an example suppose we have the following piece of code:


<pre><code>#define QList QListT
class QListT
{
};
</code></pre>


Then the only way to get Doxygen interpret this as a class definition for class <code>QList</code> is to define:


<pre><code>PREDEFINED = QListT:=QList
</code></pre>


Here is an example provided by Valter Minute and Reyes Ponce that helps Doxygen to wade through the boilerplate code in Microsoft's ATL &amp; MFC libraries:


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


As you can see Doxygen's preprocessor is quite powerful, but if you want even more flexibility you can always write an input filter and specify it after the <a href="/web-doxygen/docs/pages/config/#cfg_input_filter">INPUT\_FILTER</a> tag or the <a href="/web-doxygen/docs/pages/config/#cfg_filter_patterns">FILTER\_PATTERNS</a> tag (or the <a href="/web-doxygen/docs/pages/config/#cfg_filter_source_patterns">FILTER\_SOURCE\_PATTERNS</a> tag).
<br/>
 If you are unsure what the effect of the filter will be you can run Doxygen as follows: <code>doxygen -d filteroutput</code>.

If you are unsure what the effect of Doxygen's preprocessing will be you can run Doxygen as follows:


<pre><code>  doxygen -d Preprocessor
</code></pre>


or when the line numbers are not wanted:


<pre><code>  doxygen -d Preprocessor -d NoLineno
</code></pre>


This will instruct Doxygen to dump the input sources to standard output after preprocessing has been done (Hint: set <code>QUIET = YES</code> and <code>WARNINGS = NO</code> in the configuration file to disable any other output).

Note preprocessing is not done for all languages. Preprocessing is enabled for files that use the "C" scanner (with the exception of 'java', 'd' and 'php'), Fortran files (only in case the extension contains at least one upper case character) and vhdl files.
 
Go to the <a href="/docs/pages/autolink/">next</a> section or return to the
 <a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
