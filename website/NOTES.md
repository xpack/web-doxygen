# Notes

## Doxygen questions

Is the html code is transformed into the correct xml?

- `build/doxygen_docs/xml/da/de1/pg_cmds.xml`

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

- `doxygen/doc_internal/commands_history.md`

```
\page pg_cmds Overview of introduction of special commands

The following table gives an overview of the doxygen special commands and the version in which they were introduced.

<dl class="multicol">
<dt>New in 1.0.0</dt> <dd>\\\\</dd>
<dt></dt>             <dd>\\#</dd>
...
</dl>
```
