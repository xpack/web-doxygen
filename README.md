# web-doxygen

This project is a test to build the Doxygen web site with Docusaurus.

- https://www.doxygen.org/
- https://github.com/doxygen/doxygen
- https://github.com/doxygen/doxygen/archive/refs/tags/Release_1_14_0.tar.gz

## Doxygen

### Download

```sh
cd web-doxygen.git
version="1_14_0"
curl -L https://github.com/doxygen/doxygen/archive/refs/tags/Release_${version}.tar.gz | tar x
mv doxygen-Release_${version} doxygen
```

### Patch

```sh
cd web-doxygen.git

sed -i.bak \
-e 's|GENERATE_XML      = NO|GENERATE_XML      = YES|' \
doxygen/doc/Doxyfile

sed -i.bak \
-e 's|GENERATE_XML           = NO|GENERATE_XML           = YES|' \
-e 's|CASE_SENSE_NAMES       = NO|CASE_SENSE_NAMES       = SYSTEM|' \
-e 's|HAVE_DOT               = YES|HAVE_DOT               = NO|' \
-e 's|EXTRACT_ANON_NSPACES   = NO|EXTRACT_ANON_NSPACES   = YES|' \
doxygen/doc_internal/Doxyfile.in
```

Same for examples, but does not work properly, so use the original .html files:

```sh
cd doxygen/examples
ls -1 *.cfg | sed -e 's|\([a-z-]*\).cfg|echo "XML_OUTPUT = xml/examples/\1/xml" >> \1.cfg|'
ls -1 *.cfg | sed -e 's|\([a-z-]*\).cfg|echo "GENERATE_XML = YES" >> \1.cfg|'
```

```
style=&quot;display: block; margin-left: 0; margin-right: auto;&quot;
```

### Prerequisites

On macOS, install the dependencies:

```sh
brew install bison cmake texlive
```

```sh
export PATH="${HOME}/.local/homebrew/hb/bin:${HOME}/.local/homebrew/hb/opt/bison/bin:${PATH}"
```

### Build

```sh
cd web-doxygen.git

rm -rf build

mkdir build && cd build
cmake -Dbuild_doc=ON ../doxygen
make docs examples docs_internal
```

### Patch XMLs

```sh
cd web-doxygen.git

sed -i.bak \
-e 's|\&lt;center\&gt;||' \
-e 's|\&lt;/center\&gt;||' \
-e 's|src=\&quot;doxygen_logo.svg\&quot;|src=\&quot;/web-doxygen/img/doxygen_logo.svg\&quot;|' \
build/xml/indexpage.xml

sed -i.bak -e s'|href=\&quot;index.html\&quot;|href=\&quot;/docs/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;install.html\&quot;|href=\&quot;/docs/pages/install/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;starting.html\&quot;|href=\&quot;/docs/pages/starting/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;docblocks.html\&quot;|href=\&quot;/docs/pages/docblocks/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;additional.html\&quot;|href=\&quot;/docs/pages/additional/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;markdown.html\&quot;|href=\&quot;/docs/pages/markdown/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;lists.html\&quot;|href=\&quot;/docs/pages/lists/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;grouping.html\&quot;|href=\&quot;/docs/pages/grouping/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;formulas.html\&quot;|href=\&quot;/docs/pages/formulas/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;tables.html\&quot;|href=\&quot;/docs/pages/tables/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;diagrams.html\&quot;|href=\&quot;/docs/pages/diagrams/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;preprocessing.html\&quot;|href=\&quot;/docs/pages/preprocessing/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;autolink.html\&quot;|href=\&quot;/docs/pages/autolink/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;output.html\&quot;|href=\&quot;/docs/pages/output/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;searching.html\&quot;|href=\&quot;/docs/pages/searching/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;extsearch.html\&quot;|href=\&quot;/docs/pages/extsearch/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;customize.html\&quot;|href=\&quot;/docs/pages/customize/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;custcmd.html\&quot;|href=\&quot;/docs/pages/custcmd/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;external.html\&quot;|href=\&quot;/docs/pages/external/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;faq.html\&quot;|href=\&quot;/docs/pages/faq/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;trouble.html\&quot;|href=\&quot;/docs/pages/trouble/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;features.html\&quot;|href=\&quot;/docs/pages/features/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;doxygen_usage.html\&quot;|href=\&quot;/docs/pages/doxygen-usage/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;doxywizard_usage.html\&quot;|href=\&quot;/docs/pages/doxywizard-usage/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;config.html\&quot;|href=\&quot;/docs/pages/config/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;commands.html\&quot;|href=\&quot;/docs/pages/commands/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;htmlcmds.html\&quot;|href=\&quot;/docs/pages/htmlcmds/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;xmlcmds.html\&quot;|href=\&quot;/docs/pages/xmlcmds/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;emojisup.html\&quot;|href=\&quot;/docs/pages/emojisup/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;langhowto.html\&quot;|href=\&quot;/docs/pages/langhowto/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;perlmod.html\&quot;|href=\&quot;/docs/pages/perlmod/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;arch.html\&quot;|href=\&quot;/docs/pages/arch/\&quot;|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;changelog.html\&quot;|href=\&quot;/docs/pages/changelog/\&quot;|' build/xml/*.xml

sed -i.bak -e s'|href=\&quot;commands.html\#|href=\&quot;/docs/pages/commands/\#|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;searching.html\#|href=\&quot;/docs/pages/searching/\#|' build/xml/*.xml
sed -i.bak -e s'|url="searching.html"|url="/docs/pages/searching/"|' build/xml/*.xml
sed -i.bak -e s'|href=\&quot;translator_report.txt\&quot;|href=\&quot;pathname:///translator_report.txt\&quot;|' build/xml/*.xml

sed -i.bak \
-e s'|<htmlonly> \&lt;/p\&gt;\&lt;center\&gt;\&lt;p\&gt;</htmlonly>|<htmlonly> \&lt;center\&gt;</htmlonly>|g' \
-e s'|<htmlonly> \&lt;/p\&gt;\&lt;/center\&gt;\&lt;p\&gt;</htmlonly>|<htmlonly> \&lt;/center\&gt;</htmlonly>|g' \
build/xml/*.xml

find build/xml -name '*.xml' -print -exec sed -i.bak -e 's|href=\&quot;examples/|href=\&quot;pathname:///examples/|g' '{}' ';'

```

### Copy examples

```sh
cd web-doxygen.git

cp -r build/html/examples website/static
```

### Copy logo

```sh
cp build/html/doxygen_logo.svg website/static/img
```

## Docusaurus

```sh
npx create-docusaurus@3.8.1 website classic --typescript

cd website
npm install @docusaurus/faster
```

### docusaurus.config.ts

```ts
  markdown: {
    format: 'detect'
  },

  // Future flags, see https://docusaurus.io/docs/api/docusaurus-config#future
  future: {
    v4: {
      removeLegacyPostBuildHeadAttribute: true
    },
    experimental_faster: true,
  },

  trailingSlash: true,

  plugins: [
    [
      '@xpack/docusaurus-plugin-doxygen',
      {
        id: 'manual',
        doxygenXmlInputFolderPath: '../build/xml',
        apiFolderPath: 'manual',
        apiBaseUrl: '',
        sidebarCategoryLabel: 'Manual',
        menuDropdownLabel: 'Manual',
        mainPageTitle: 'The Documentation Generator',
        verbose: true,
        debug: false
      },
    ],
    [
      '@xpack/docusaurus-plugin-doxygen',
      {
        id: 'api',
        doxygenXmlInputFolderPath: '../build/doxygen_docs/xml',
        apiFolderPath: 'api',
        apiBaseUrl: 'api',
        sidebarCategoryLabel: 'Doxygen Internals',
        menuDropdownLabel: 'Internals',
        mainPageTitle: 'Doxygen Internals',
        verbose: true,
        debug: false
      },
    ],
    function disableExpensiveBundlerOptimizationPlugin() {
      return {
        name: "disable-expensive-bundler-optimizations",
        configureWebpack(_config, isServer) {
          return {
            optimization: {
              concatenateModules: false,
            },
          };
        },
      };
    },
  ],

```

### package.json

```
    "start": "node --max-old-space-size=20480 --stack-size=2048 ./node_modules/.bin/docusaurus start",
    "build": "node --max-old-space-size=20480 --stack-size=2048 ./node_modules/.bin/docusaurus build",

    "generate-doxygen-manual": "node --max-old-space-size=4096 --stack-size=2048 ./node_modules/.bin/docusaurus generate-doxygen --id manual",
    "generate-doxygen-api": "node --max-old-space-size=4096 --stack-size=2048 ./node_modules/.bin/docusaurus generate-doxygen --id api",
```

### Memory issue

```console
#
# Fatal error in , line 0
# Fatal JavaScript invalid size error 184102346 (see crbug.com/1201626)
#
#
#
#FailureMessage Object: 0x7ff7b4ac7e70
----- Native stack trace -----

 1: 0x10b596122 node::NodePlatform::GetStackTracePrinter()::$_3::__invoke() [/Users/ilg/.nvm/versions/node/v20.18.0/bin/node]
 2: 0x10c8b2ae3 V8_Fatal(char const*, ...) [/Users/ilg/.nvm/versions/node/v20.18.0/bin/node]
 3: 0x10b89c2f6 v8::internal::FactoryBase<v8::internal::Factory>::NewFixedArray(int, v8::internal::AllocationType) [/Users/ilg/.nvm/versions/node/v20.18.0/bin/node]
 4: 0x10ba894e3 v8::internal::(anonymous namespace)::ElementsAccessorBase<v8::internal::(anonymous namespace)::FastPackedObjectElementsAccessor, v8::internal::(anonymous namespace)::ElementsKindTraits<(v8::internal::ElementsKind)2>>::GrowCapacity(v8::internal::Handle<v8::internal::JSObject>, unsigned int) [/Users/ilg/.nvm/versions/node/v20.18.0/bin/node]
 5: 0x10bd18aec v8::internal::Runtime_GrowArrayElements(int, unsigned long*, v8::internal::Isolate*) [/Users/ilg/.nvm/versions/node/v20.18.0/bin/node]
 6: 0x10c0f8376 Builtins_CEntry_Return1_ArgvOnStack_NoBuiltinExit [/Users/ilg/.nvm/versions/node/v20.18.0/bin/node]
 *  Terminal will be reused by tasks, press any key to close it.
```

## Questions

- `doxygen/doc_internal/commands_history.md`

The html code is transformed into wrong xml?

```
\page pg_cmds Overview of introduction of special commands

The following table gives an overview of the doxygen special commands and the version in which they were introduced.

<dl class="multicol">
<dt>New in 1.0.0</dt> <dd>\\\\</dd>
<dt></dt>             <dd>\\#</dd>
...
</dl>
```

- build/doxygen_docs/xml/da/de1/pg_cmds.xml

```
<para>The following table gives an overview of the doxygen special commands and the version in which they were introduced.</para>
<para><variablelist>
<varlistentry><term>New in 1.0.0 </term></varlistentry>
<listitem><para>\\ </para>
</listitem>
<varlistentry><term></term></varlistentry>
<listitem><para>\# </para>
</listitem>
<varlistentry><term></term></varlistentry>
<listitem><para>\$ </para>
...
```
