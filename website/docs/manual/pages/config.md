---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /pages/config
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - page
toc_max_heading_level: 4

---

<div class="doxyPage">

# Configuration




## Format {#config_format}


<p>A configuration file is a free-form ASCII text file with a structure that is similar to that of a <span class="doxyComputerOutput">Makefile</span>, with the default name <span class="doxyComputerOutput">Doxyfile</span>. It is parsed by <span class="doxyComputerOutput">doxygen</span>. The file may contain tabs and newlines for formatting purposes. The statements in the file are case-sensitive.</p>


<p>The configuration file essentially consists of a list of assignment statements. Each statement consists of a <span class="doxyComputerOutput">TAG_NAME</span> written in capitals, followed by the equal sign (<span class="doxyComputerOutput">=</span>) and one or more values. If the same tag is assigned more than once, the last assignment overwrites any earlier assignment. For tags that take a list as their argument, the <span class="doxyComputerOutput">+=</span> operator can be used instead of <span class="doxyComputerOutput">=</span> to append new values to the list. Values are sequences of non-blanks. If the value should contain one or more blanks it must be surrounded by quotes (<span class="doxyComputerOutput">"..."</span>). Multiple lines can be concatenated by inserting a backslash (<span class="doxyComputerOutput">\</span>) as the last non-whitespace character of a line.</p>


<p>Comments begin with the hash character (<span class="doxyComputerOutput">#</span>) and end at the end of the line. Comments may be placed anywhere within the file (except within quotes). Comments beginning with two hash characters (<span class="doxyComputerOutput">##</span>) are kept while updating the configuration file when they are placed in front of a <span class="doxyComputerOutput">TAG_NAME</span>, or at the beginning or end of the configuration file.</p>


<p>Environment variables can be expanded using the pattern <span class="doxyComputerOutput">$(ENV_VARIABLE_NAME)</span>. A small example:</p>



<pre><code>DOT_PATH      = $(YOUR_DOT_PATH)
</code></pre>


<p>You can also include part of a configuration file from another configuration file using a <span class="doxyComputerOutput">@INCLUDE</span> tag as follows:</p>



<pre><code>@INCLUDE = config_file_name
</code></pre>


<p>The include file is searched in the current working directory. You can also specify a list of directories that should be searched before looking in the current working directory. Do this by putting a <span class="doxyComputerOutput">@INCLUDE_PATH</span> tag with these paths before the <span class="doxyComputerOutput">@INCLUDE</span> tag, e.g.:</p>



<pre><code>@INCLUDE_PATH = my_config_dir
</code></pre>


<p>The configuration options can be divided into several categories. Below is an alphabetical index of the tags that are recognized followed by the descriptions of the tags grouped by category.</p>



<ul class="doxyTocList">
<li><a class="doxyTocListItem" href="#cfg_abbreviate_brief">ABBREVIATE_BRIEF</a></li>
<li><a class="doxyTocListItem" href="#cfg_aliases">ALIASES</a></li>
<li><a class="doxyTocListItem" href="#cfg_allexternals">ALLEXTERNALS</a></li>
<li><a class="doxyTocListItem" href="#cfg_allow_unicode_names">ALLOW_UNICODE_NAMES</a></li>
<li><a class="doxyTocListItem" href="#cfg_alphabetical_index">ALPHABETICAL_INDEX</a></li>
<li><a class="doxyTocListItem" href="#cfg_always_detailed_sec">ALWAYS_DETAILED_SEC</a></li>
<li><a class="doxyTocListItem" href="#cfg_autolink_ignore_words">AUTOLINK_IGNORE_WORDS</a></li>
<li><a class="doxyTocListItem" href="#cfg_autolink_support">AUTOLINK_SUPPORT</a></li>
<li><a class="doxyTocListItem" href="#cfg_binary_toc">BINARY_TOC</a></li>
<li><a class="doxyTocListItem" href="#cfg_brief_member_desc">BRIEF_MEMBER_DESC</a></li>
<li><a class="doxyTocListItem" href="#cfg_builtin_stl_support">BUILTIN_STL_SUPPORT</a></li>
<li><a class="doxyTocListItem" href="#cfg_caller_graph">CALLER_GRAPH</a></li>
<li><a class="doxyTocListItem" href="#cfg_call_graph">CALL_GRAPH</a></li>
<li><a class="doxyTocListItem" href="#cfg_case_sense_names">CASE_SENSE_NAMES</a></li>
<li><a class="doxyTocListItem" href="#cfg_chm_file">CHM_FILE</a></li>
<li><a class="doxyTocListItem" href="#cfg_chm_index_encoding">CHM_INDEX_ENCODING</a></li>
<li><a class="doxyTocListItem" href="#cfg_cite_bib_files">CITE_BIB_FILES</a></li>
<li><a class="doxyTocListItem" href="#cfg_clang_add_inc_paths">CLANG_ADD_INC_PATHS</a></li>
<li><a class="doxyTocListItem" href="#cfg_clang_assisted_parsing">CLANG_ASSISTED_PARSING</a></li>
<li><a class="doxyTocListItem" href="#cfg_clang_database_path">CLANG_DATABASE_PATH</a></li>
<li><a class="doxyTocListItem" href="#cfg_clang_options">CLANG_OPTIONS</a></li>
<li><a class="doxyTocListItem" href="#cfg_class_graph">CLASS_GRAPH</a></li>
<li><a class="doxyTocListItem" href="#cfg_collaboration_graph">COLLABORATION_GRAPH</a></li>
<li><a class="doxyTocListItem" href="#cfg_compact_latex">COMPACT_LATEX</a></li>
<li><a class="doxyTocListItem" href="#cfg_compact_rtf">COMPACT_RTF</a></li>
<li><a class="doxyTocListItem" href="#cfg_cpp_cli_support">CPP_CLI_SUPPORT</a></li>
<li><a class="doxyTocListItem" href="#cfg_create_subdirs">CREATE_SUBDIRS</a></li>
<li><a class="doxyTocListItem" href="#cfg_create_subdirs_level">CREATE_SUBDIRS_LEVEL</a></li>
<li><a class="doxyTocListItem" href="#cfg_diafile_dirs">DIAFILE_DIRS</a></li>
<li><a class="doxyTocListItem" href="#cfg_dia_path">DIA_PATH</a></li>
<li><a class="doxyTocListItem" href="#cfg_directory_graph">DIRECTORY_GRAPH</a></li>
<li><a class="doxyTocListItem" href="#cfg_dir_graph_max_depth">DIR_GRAPH_MAX_DEPTH</a></li>
<li><a class="doxyTocListItem" href="#cfg_disable_index">DISABLE_INDEX</a></li>
<li><a class="doxyTocListItem" href="#cfg_distribute_group_doc">DISTRIBUTE_GROUP_DOC</a></li>
<li><a class="doxyTocListItem" href="#cfg_docbook_output">DOCBOOK_OUTPUT</a></li>
<li><a class="doxyTocListItem" href="#cfg_docset_bundle_id">DOCSET_BUNDLE_ID</a></li>
<li><a class="doxyTocListItem" href="#cfg_docset_feedname">DOCSET_FEEDNAME</a></li>
<li><a class="doxyTocListItem" href="#cfg_docset_feedurl">DOCSET_FEEDURL</a></li>
<li><a class="doxyTocListItem" href="#cfg_docset_publisher_id">DOCSET_PUBLISHER_ID</a></li>
<li><a class="doxyTocListItem" href="#cfg_docset_publisher_name">DOCSET_PUBLISHER_NAME</a></li>
<li><a class="doxyTocListItem" href="#cfg_dotfile_dirs">DOTFILE_DIRS</a></li>
<li><a class="doxyTocListItem" href="#cfg_dot_cleanup">DOT_CLEANUP</a></li>
<li><a class="doxyTocListItem" href="#cfg_dot_common_attr">DOT_COMMON_ATTR</a></li>
<li><a class="doxyTocListItem" href="#cfg_dot_edge_attr">DOT_EDGE_ATTR</a></li>
<li><a class="doxyTocListItem" href="#cfg_dot_fontpath">DOT_FONTPATH</a></li>
<li><a class="doxyTocListItem" href="#cfg_dot_graph_max_nodes">DOT_GRAPH_MAX_NODES</a></li>
<li><a class="doxyTocListItem" href="#cfg_dot_image_format">DOT_IMAGE_FORMAT</a></li>
<li><a class="doxyTocListItem" href="#cfg_dot_multi_targets">DOT_MULTI_TARGETS</a></li>
<li><a class="doxyTocListItem" href="#cfg_dot_node_attr">DOT_NODE_ATTR</a></li>
<li><a class="doxyTocListItem" href="#cfg_dot_num_threads">DOT_NUM_THREADS</a></li>
<li><a class="doxyTocListItem" href="#cfg_dot_path">DOT_PATH</a></li>
<li><a class="doxyTocListItem" href="#cfg_dot_uml_details">DOT_UML_DETAILS</a></li>
<li><a class="doxyTocListItem" href="#cfg_dot_wrap_threshold">DOT_WRAP_THRESHOLD</a></li>
<li><a class="doxyTocListItem" href="#cfg_doxyfile_encoding">DOXYFILE_ENCODING</a></li>
<li><a class="doxyTocListItem" href="#cfg_eclipse_doc_id">ECLIPSE_DOC_ID</a></li>
<li><a class="doxyTocListItem" href="#cfg_enabled_sections">ENABLED_SECTIONS</a></li>
<li><a class="doxyTocListItem" href="#cfg_enable_preprocessing">ENABLE_PREPROCESSING</a></li>
<li><a class="doxyTocListItem" href="#cfg_enum_values_per_line">ENUM_VALUES_PER_LINE</a></li>
<li><a class="doxyTocListItem" href="#cfg_example_path">EXAMPLE_PATH</a></li>
<li><a class="doxyTocListItem" href="#cfg_example_patterns">EXAMPLE_PATTERNS</a></li>
<li><a class="doxyTocListItem" href="#cfg_example_recursive">EXAMPLE_RECURSIVE</a></li>
<li><a class="doxyTocListItem" href="#cfg_exclude">EXCLUDE</a></li>
<li><a class="doxyTocListItem" href="#cfg_exclude_patterns">EXCLUDE_PATTERNS</a></li>
<li><a class="doxyTocListItem" href="#cfg_exclude_symbols">EXCLUDE_SYMBOLS</a></li>
<li><a class="doxyTocListItem" href="#cfg_exclude_symlinks">EXCLUDE_SYMLINKS</a></li>
<li><a class="doxyTocListItem" href="#cfg_expand_as_defined">EXPAND_AS_DEFINED</a></li>
<li><a class="doxyTocListItem" href="#cfg_expand_only_predef">EXPAND_ONLY_PREDEF</a></li>
<li><a class="doxyTocListItem" href="#cfg_extension_mapping">EXTENSION_MAPPING</a></li>
<li><a class="doxyTocListItem" href="#cfg_external_groups">EXTERNAL_GROUPS</a></li>
<li><a class="doxyTocListItem" href="#cfg_external_pages">EXTERNAL_PAGES</a></li>
<li><a class="doxyTocListItem" href="#cfg_external_search">EXTERNAL_SEARCH</a></li>
<li><a class="doxyTocListItem" href="#cfg_external_search_id">EXTERNAL_SEARCH_ID</a></li>
<li><a class="doxyTocListItem" href="#cfg_external_tool_path">EXTERNAL_TOOL_PATH</a></li>
<li><a class="doxyTocListItem" href="#cfg_extract_all">EXTRACT_ALL</a></li>
<li><a class="doxyTocListItem" href="#cfg_extract_anon_nspaces">EXTRACT_ANON_NSPACES</a></li>
<li><a class="doxyTocListItem" href="#cfg_extract_local_classes">EXTRACT_LOCAL_CLASSES</a></li>
<li><a class="doxyTocListItem" href="#cfg_extract_local_methods">EXTRACT_LOCAL_METHODS</a></li>
<li><a class="doxyTocListItem" href="#cfg_extract_package">EXTRACT_PACKAGE</a></li>
<li><a class="doxyTocListItem" href="#cfg_extract_private">EXTRACT_PRIVATE</a></li>
<li><a class="doxyTocListItem" href="#cfg_extract_priv_virtual">EXTRACT_PRIV_VIRTUAL</a></li>
<li><a class="doxyTocListItem" href="#cfg_extract_static">EXTRACT_STATIC</a></li>
<li><a class="doxyTocListItem" href="#cfg_extra_packages">EXTRA_PACKAGES</a></li>
<li><a class="doxyTocListItem" href="#cfg_extra_search_mappings">EXTRA_SEARCH_MAPPINGS</a></li>
<li><a class="doxyTocListItem" href="#cfg_ext_links_in_window">EXT_LINKS_IN_WINDOW</a></li>
<li><a class="doxyTocListItem" href="#cfg_file_patterns">FILE_PATTERNS</a></li>
<li><a class="doxyTocListItem" href="#cfg_file_version_filter">FILE_VERSION_FILTER</a></li>
<li><a class="doxyTocListItem" href="#cfg_filter_patterns">FILTER_PATTERNS</a></li>
<li><a class="doxyTocListItem" href="#cfg_filter_source_files">FILTER_SOURCE_FILES</a></li>
<li><a class="doxyTocListItem" href="#cfg_filter_source_patterns">FILTER_SOURCE_PATTERNS</a></li>
<li><a class="doxyTocListItem" href="#cfg_force_local_includes">FORCE_LOCAL_INCLUDES</a></li>
<li><a class="doxyTocListItem" href="#cfg_formula_fontsize">FORMULA_FONTSIZE</a></li>
<li><a class="doxyTocListItem" href="#cfg_formula_macrofile">FORMULA_MACROFILE</a></li>
<li><a class="doxyTocListItem" href="#cfg_fortran_comment_after">FORTRAN_COMMENT_AFTER</a></li>
<li><a class="doxyTocListItem" href="#cfg_full_path_names">FULL_PATH_NAMES</a></li>
<li><a class="doxyTocListItem" href="#cfg_full_sidebar">FULL_SIDEBAR</a></li>
<li><a class="doxyTocListItem" href="#cfg_generate_autogen_def">GENERATE_AUTOGEN_DEF</a></li>
<li><a class="doxyTocListItem" href="#cfg_generate_buglist">GENERATE_BUGLIST</a></li>
<li><a class="doxyTocListItem" href="#cfg_generate_chi">GENERATE_CHI</a></li>
<li><a class="doxyTocListItem" href="#cfg_generate_deprecatedlist">GENERATE_DEPRECATEDLIST</a></li>
<li><a class="doxyTocListItem" href="#cfg_generate_docbook">GENERATE_DOCBOOK</a></li>
<li><a class="doxyTocListItem" href="#cfg_generate_docset">GENERATE_DOCSET</a></li>
<li><a class="doxyTocListItem" href="#cfg_generate_eclipsehelp">GENERATE_ECLIPSEHELP</a></li>
<li><a class="doxyTocListItem" href="#cfg_generate_html">GENERATE_HTML</a></li>
<li><a class="doxyTocListItem" href="#cfg_generate_htmlhelp">GENERATE_HTMLHELP</a></li>
<li><a class="doxyTocListItem" href="#cfg_generate_latex">GENERATE_LATEX</a></li>
<li><a class="doxyTocListItem" href="#cfg_generate_legend">GENERATE_LEGEND</a></li>
<li><a class="doxyTocListItem" href="#cfg_generate_man">GENERATE_MAN</a></li>
<li><a class="doxyTocListItem" href="#cfg_generate_perlmod">GENERATE_PERLMOD</a></li>
<li><a class="doxyTocListItem" href="#cfg_generate_qhp">GENERATE_QHP</a></li>
<li><a class="doxyTocListItem" href="#cfg_generate_rtf">GENERATE_RTF</a></li>
<li><a class="doxyTocListItem" href="#cfg_generate_sqlite3">GENERATE_SQLITE3</a></li>
<li><a class="doxyTocListItem" href="#cfg_generate_tagfile">GENERATE_TAGFILE</a></li>
<li><a class="doxyTocListItem" href="#cfg_generate_testlist">GENERATE_TESTLIST</a></li>
<li><a class="doxyTocListItem" href="#cfg_generate_todolist">GENERATE_TODOLIST</a></li>
<li><a class="doxyTocListItem" href="#cfg_generate_treeview">GENERATE_TREEVIEW</a></li>
<li><a class="doxyTocListItem" href="#cfg_generate_xml">GENERATE_XML</a></li>
<li><a class="doxyTocListItem" href="#cfg_graphical_hierarchy">GRAPHICAL_HIERARCHY</a></li>
<li><a class="doxyTocListItem" href="#cfg_group_graphs">GROUP_GRAPHS</a></li>
<li><a class="doxyTocListItem" href="#cfg_group_nested_compounds">GROUP_NESTED_COMPOUNDS</a></li>
<li><a class="doxyTocListItem" href="#cfg_have_dot">HAVE_DOT</a></li>
<li><a class="doxyTocListItem" href="#cfg_hhc_location">HHC_LOCATION</a></li>
<li><a class="doxyTocListItem" href="#cfg_hide_compound_reference">HIDE_COMPOUND_REFERENCE</a></li>
<li><a class="doxyTocListItem" href="#cfg_hide_friend_compounds">HIDE_FRIEND_COMPOUNDS</a></li>
<li><a class="doxyTocListItem" href="#cfg_hide_in_body_docs">HIDE_IN_BODY_DOCS</a></li>
<li><a class="doxyTocListItem" href="#cfg_hide_scope_names">HIDE_SCOPE_NAMES</a></li>
<li><a class="doxyTocListItem" href="#cfg_hide_undoc_classes">HIDE_UNDOC_CLASSES</a></li>
<li><a class="doxyTocListItem" href="#cfg_hide_undoc_members">HIDE_UNDOC_MEMBERS</a></li>
<li><a class="doxyTocListItem" href="#cfg_hide_undoc_namespaces">HIDE_UNDOC_NAMESPACES</a></li>
<li><a class="doxyTocListItem" href="#cfg_hide_undoc_relations">HIDE_UNDOC_RELATIONS</a></li>
<li><a class="doxyTocListItem" href="#cfg_html_code_folding">HTML_CODE_FOLDING</a></li>
<li><a class="doxyTocListItem" href="#cfg_html_colorstyle">HTML_COLORSTYLE</a></li>
<li><a class="doxyTocListItem" href="#cfg_html_colorstyle_gamma">HTML_COLORSTYLE_GAMMA</a></li>
<li><a class="doxyTocListItem" href="#cfg_html_colorstyle_hue">HTML_COLORSTYLE_HUE</a></li>
<li><a class="doxyTocListItem" href="#cfg_html_colorstyle_sat">HTML_COLORSTYLE_SAT</a></li>
<li><a class="doxyTocListItem" href="#cfg_html_copy_clipboard">HTML_COPY_CLIPBOARD</a></li>
<li><a class="doxyTocListItem" href="#cfg_html_dynamic_menus">HTML_DYNAMIC_MENUS</a></li>
<li><a class="doxyTocListItem" href="#cfg_html_dynamic_sections">HTML_DYNAMIC_SECTIONS</a></li>
<li><a class="doxyTocListItem" href="#cfg_html_extra_files">HTML_EXTRA_FILES</a></li>
<li><a class="doxyTocListItem" href="#cfg_html_extra_stylesheet">HTML_EXTRA_STYLESHEET</a></li>
<li><a class="doxyTocListItem" href="#cfg_html_file_extension">HTML_FILE_EXTENSION</a></li>
<li><a class="doxyTocListItem" href="#cfg_html_footer">HTML_FOOTER</a></li>
<li><a class="doxyTocListItem" href="#cfg_html_formula_format">HTML_FORMULA_FORMAT</a></li>
<li><a class="doxyTocListItem" href="#cfg_html_header">HTML_HEADER</a></li>
<li><a class="doxyTocListItem" href="#cfg_html_index_num_entries">HTML_INDEX_NUM_ENTRIES</a></li>
<li><a class="doxyTocListItem" href="#cfg_html_output">HTML_OUTPUT</a></li>
<li><a class="doxyTocListItem" href="#cfg_html_project_cookie">HTML_PROJECT_COOKIE</a></li>
<li><a class="doxyTocListItem" href="#cfg_html_stylesheet">HTML_STYLESHEET</a></li>
<li><a class="doxyTocListItem" href="#cfg_idl_property_support">IDL_PROPERTY_SUPPORT</a></li>
<li><a class="doxyTocListItem" href="#cfg_ignore_prefix">IGNORE_PREFIX</a></li>
<li><a class="doxyTocListItem" href="#cfg_image_path">IMAGE_PATH</a></li>
<li><a class="doxyTocListItem" href="#cfg_implicit_dir_docs">IMPLICIT_DIR_DOCS</a></li>
<li><a class="doxyTocListItem" href="#cfg_included_by_graph">INCLUDED_BY_GRAPH</a></li>
<li><a class="doxyTocListItem" href="#cfg_include_file_patterns">INCLUDE_FILE_PATTERNS</a></li>
<li><a class="doxyTocListItem" href="#cfg_include_graph">INCLUDE_GRAPH</a></li>
<li><a class="doxyTocListItem" href="#cfg_include_path">INCLUDE_PATH</a></li>
<li><a class="doxyTocListItem" href="#cfg_inherit_docs">INHERIT_DOCS</a></li>
<li><a class="doxyTocListItem" href="#cfg_inline_grouped_classes">INLINE_GROUPED_CLASSES</a></li>
<li><a class="doxyTocListItem" href="#cfg_inline_info">INLINE_INFO</a></li>
<li><a class="doxyTocListItem" href="#cfg_inline_inherited_memb">INLINE_INHERITED_MEMB</a></li>
<li><a class="doxyTocListItem" href="#cfg_inline_simple_structs">INLINE_SIMPLE_STRUCTS</a></li>
<li><a class="doxyTocListItem" href="#cfg_inline_sources">INLINE_SOURCES</a></li>
<li><a class="doxyTocListItem" href="#cfg_input">INPUT</a></li>
<li><a class="doxyTocListItem" href="#cfg_input_encoding">INPUT_ENCODING</a></li>
<li><a class="doxyTocListItem" href="#cfg_input_file_encoding">INPUT_FILE_ENCODING</a></li>
<li><a class="doxyTocListItem" href="#cfg_input_filter">INPUT_FILTER</a></li>
<li><a class="doxyTocListItem" href="#cfg_interactive_svg">INTERACTIVE_SVG</a></li>
<li><a class="doxyTocListItem" href="#cfg_internal_docs">INTERNAL_DOCS</a></li>
<li><a class="doxyTocListItem" href="#cfg_javadoc_autobrief">JAVADOC_AUTOBRIEF</a></li>
<li><a class="doxyTocListItem" href="#cfg_javadoc_banner">JAVADOC_BANNER</a></li>
<li><a class="doxyTocListItem" href="#cfg_latex_batchmode">LATEX_BATCHMODE</a></li>
<li><a class="doxyTocListItem" href="#cfg_latex_bib_style">LATEX_BIB_STYLE</a></li>
<li><a class="doxyTocListItem" href="#cfg_latex_cmd_name">LATEX_CMD_NAME</a></li>
<li><a class="doxyTocListItem" href="#cfg_latex_emoji_directory">LATEX_EMOJI_DIRECTORY</a></li>
<li><a class="doxyTocListItem" href="#cfg_latex_extra_files">LATEX_EXTRA_FILES</a></li>
<li><a class="doxyTocListItem" href="#cfg_latex_extra_stylesheet">LATEX_EXTRA_STYLESHEET</a></li>
<li><a class="doxyTocListItem" href="#cfg_latex_footer">LATEX_FOOTER</a></li>
<li><a class="doxyTocListItem" href="#cfg_latex_header">LATEX_HEADER</a></li>
<li><a class="doxyTocListItem" href="#cfg_latex_hide_indices">LATEX_HIDE_INDICES</a></li>
<li><a class="doxyTocListItem" href="#cfg_latex_makeindex_cmd">LATEX_MAKEINDEX_CMD</a></li>
<li><a class="doxyTocListItem" href="#cfg_latex_output">LATEX_OUTPUT</a></li>
<li><a class="doxyTocListItem" href="#cfg_layout_file">LAYOUT_FILE</a></li>
<li><a class="doxyTocListItem" href="#cfg_lookup_cache_size">LOOKUP_CACHE_SIZE</a></li>
<li><a class="doxyTocListItem" href="#cfg_macro_expansion">MACRO_EXPANSION</a></li>
<li><a class="doxyTocListItem" href="#cfg_makeindex_cmd_name">MAKEINDEX_CMD_NAME</a></li>
<li><a class="doxyTocListItem" href="#cfg_man_extension">MAN_EXTENSION</a></li>
<li><a class="doxyTocListItem" href="#cfg_man_links">MAN_LINKS</a></li>
<li><a class="doxyTocListItem" href="#cfg_man_output">MAN_OUTPUT</a></li>
<li><a class="doxyTocListItem" href="#cfg_man_subdir">MAN_SUBDIR</a></li>
<li><a class="doxyTocListItem" href="#cfg_markdown_id_style">MARKDOWN_ID_STYLE</a></li>
<li><a class="doxyTocListItem" href="#cfg_markdown_support">MARKDOWN_SUPPORT</a></li>
<li><a class="doxyTocListItem" href="#cfg_mathjax_codefile">MATHJAX_CODEFILE</a></li>
<li><a class="doxyTocListItem" href="#cfg_mathjax_extensions">MATHJAX_EXTENSIONS</a></li>
<li><a class="doxyTocListItem" href="#cfg_mathjax_format">MATHJAX_FORMAT</a></li>
<li><a class="doxyTocListItem" href="#cfg_mathjax_relpath">MATHJAX_RELPATH</a></li>
<li><a class="doxyTocListItem" href="#cfg_mathjax_version">MATHJAX_VERSION</a></li>
<li><a class="doxyTocListItem" href="#cfg_max_dot_graph_depth">MAX_DOT_GRAPH_DEPTH</a></li>
<li><a class="doxyTocListItem" href="#cfg_max_initializer_lines">MAX_INITIALIZER_LINES</a></li>
<li><a class="doxyTocListItem" href="#cfg_mscfile_dirs">MSCFILE_DIRS</a></li>
<li><a class="doxyTocListItem" href="#cfg_mscgen_tool">MSCGEN_TOOL</a></li>
<li><a class="doxyTocListItem" href="#cfg_multiline_cpp_is_brief">MULTILINE_CPP_IS_BRIEF</a></li>
<li><a class="doxyTocListItem" href="#cfg_num_proc_threads">NUM_PROC_THREADS</a></li>
<li><a class="doxyTocListItem" href="#cfg_obfuscate_emails">OBFUSCATE_EMAILS</a></li>
<li><a class="doxyTocListItem" href="#cfg_optimize_for_fortran">OPTIMIZE_FOR_FORTRAN</a></li>
<li><a class="doxyTocListItem" href="#cfg_optimize_output_for_c">OPTIMIZE_OUTPUT_FOR_C</a></li>
<li><a class="doxyTocListItem" href="#cfg_optimize_output_java">OPTIMIZE_OUTPUT_JAVA</a></li>
<li><a class="doxyTocListItem" href="#cfg_optimize_output_slice">OPTIMIZE_OUTPUT_SLICE</a></li>
<li><a class="doxyTocListItem" href="#cfg_optimize_output_vhdl">OPTIMIZE_OUTPUT_VHDL</a></li>
<li><a class="doxyTocListItem" href="#cfg_output_directory">OUTPUT_DIRECTORY</a></li>
<li><a class="doxyTocListItem" href="#cfg_output_language">OUTPUT_LANGUAGE</a></li>
<li><a class="doxyTocListItem" href="#cfg_page_outline_panel">PAGE_OUTLINE_PANEL</a></li>
<li><a class="doxyTocListItem" href="#cfg_paper_type">PAPER_TYPE</a></li>
<li><a class="doxyTocListItem" href="#cfg_pdf_hyperlinks">PDF_HYPERLINKS</a></li>
<li><a class="doxyTocListItem" href="#cfg_perlmod_latex">PERLMOD_LATEX</a></li>
<li><a class="doxyTocListItem" href="#cfg_perlmod_makevar_prefix">PERLMOD_MAKEVAR_PREFIX</a></li>
<li><a class="doxyTocListItem" href="#cfg_perlmod_pretty">PERLMOD_PRETTY</a></li>
<li><a class="doxyTocListItem" href="#cfg_plantumlfile_dirs">PLANTUMLFILE_DIRS</a></li>
<li><a class="doxyTocListItem" href="#cfg_plantuml_cfg_file">PLANTUML_CFG_FILE</a></li>
<li><a class="doxyTocListItem" href="#cfg_plantuml_include_path">PLANTUML_INCLUDE_PATH</a></li>
<li><a class="doxyTocListItem" href="#cfg_plantuml_jar_path">PLANTUML_JAR_PATH</a></li>
<li><a class="doxyTocListItem" href="#cfg_predefined">PREDEFINED</a></li>
<li><a class="doxyTocListItem" href="#cfg_project_brief">PROJECT_BRIEF</a></li>
<li><a class="doxyTocListItem" href="#cfg_project_icon">PROJECT_ICON</a></li>
<li><a class="doxyTocListItem" href="#cfg_project_logo">PROJECT_LOGO</a></li>
<li><a class="doxyTocListItem" href="#cfg_project_name">PROJECT_NAME</a></li>
<li><a class="doxyTocListItem" href="#cfg_project_number">PROJECT_NUMBER</a></li>
<li><a class="doxyTocListItem" href="#cfg_python_docstring">PYTHON_DOCSTRING</a></li>
<li><a class="doxyTocListItem" href="#cfg_qch_file">QCH_FILE</a></li>
<li><a class="doxyTocListItem" href="#cfg_qhg_location">QHG_LOCATION</a></li>
<li><a class="doxyTocListItem" href="#cfg_qhp_cust_filter_attrs">QHP_CUST_FILTER_ATTRS</a></li>
<li><a class="doxyTocListItem" href="#cfg_qhp_cust_filter_name">QHP_CUST_FILTER_NAME</a></li>
<li><a class="doxyTocListItem" href="#cfg_qhp_namespace">QHP_NAMESPACE</a></li>
<li><a class="doxyTocListItem" href="#cfg_qhp_sect_filter_attrs">QHP_SECT_FILTER_ATTRS</a></li>
<li><a class="doxyTocListItem" href="#cfg_qhp_virtual_folder">QHP_VIRTUAL_FOLDER</a></li>
<li><a class="doxyTocListItem" href="#cfg_qt_autobrief">QT_AUTOBRIEF</a></li>
<li><a class="doxyTocListItem" href="#cfg_quiet">QUIET</a></li>
<li><a class="doxyTocListItem" href="#cfg_recursive">RECURSIVE</a></li>
<li><a class="doxyTocListItem" href="#cfg_referenced_by_relation">REFERENCED_BY_RELATION</a></li>
<li><a class="doxyTocListItem" href="#cfg_references_link_source">REFERENCES_LINK_SOURCE</a></li>
<li><a class="doxyTocListItem" href="#cfg_references_relation">REFERENCES_RELATION</a></li>
<li><a class="doxyTocListItem" href="#cfg_repeat_brief">REPEAT_BRIEF</a></li>
<li><a class="doxyTocListItem" href="#cfg_resolve_unnamed_params">RESOLVE_UNNAMED_PARAMS</a></li>
<li><a class="doxyTocListItem" href="#cfg_rtf_extensions_file">RTF_EXTENSIONS_FILE</a></li>
<li><a class="doxyTocListItem" href="#cfg_rtf_extra_files">RTF_EXTRA_FILES</a></li>
<li><a class="doxyTocListItem" href="#cfg_rtf_hyperlinks">RTF_HYPERLINKS</a></li>
<li><a class="doxyTocListItem" href="#cfg_rtf_output">RTF_OUTPUT</a></li>
<li><a class="doxyTocListItem" href="#cfg_rtf_stylesheet_file">RTF_STYLESHEET_FILE</a></li>
<li><a class="doxyTocListItem" href="#cfg_searchdata_file">SEARCHDATA_FILE</a></li>
<li><a class="doxyTocListItem" href="#cfg_searchengine">SEARCHENGINE</a></li>
<li><a class="doxyTocListItem" href="#cfg_searchengine_url">SEARCHENGINE_URL</a></li>
<li><a class="doxyTocListItem" href="#cfg_search_includes">SEARCH_INCLUDES</a></li>
<li><a class="doxyTocListItem" href="#cfg_separate_member_pages">SEPARATE_MEMBER_PAGES</a></li>
<li><a class="doxyTocListItem" href="#cfg_server_based_search">SERVER_BASED_SEARCH</a></li>
<li><a class="doxyTocListItem" href="#cfg_short_names">SHORT_NAMES</a></li>
<li><a class="doxyTocListItem" href="#cfg_show_enum_values">SHOW_ENUM_VALUES</a></li>
<li><a class="doxyTocListItem" href="#cfg_show_files">SHOW_FILES</a></li>
<li><a class="doxyTocListItem" href="#cfg_show_grouped_memb_inc">SHOW_GROUPED_MEMB_INC</a></li>
<li><a class="doxyTocListItem" href="#cfg_show_headerfile">SHOW_HEADERFILE</a></li>
<li><a class="doxyTocListItem" href="#cfg_show_include_files">SHOW_INCLUDE_FILES</a></li>
<li><a class="doxyTocListItem" href="#cfg_show_namespaces">SHOW_NAMESPACES</a></li>
<li><a class="doxyTocListItem" href="#cfg_show_used_files">SHOW_USED_FILES</a></li>
<li><a class="doxyTocListItem" href="#cfg_sip_support">SIP_SUPPORT</a></li>
<li><a class="doxyTocListItem" href="#cfg_sitemap_url">SITEMAP_URL</a></li>
<li><a class="doxyTocListItem" href="#cfg_skip_function_macros">SKIP_FUNCTION_MACROS</a></li>
<li><a class="doxyTocListItem" href="#cfg_sort_brief_docs">SORT_BRIEF_DOCS</a></li>
<li><a class="doxyTocListItem" href="#cfg_sort_by_scope_name">SORT_BY_SCOPE_NAME</a></li>
<li><a class="doxyTocListItem" href="#cfg_sort_group_names">SORT_GROUP_NAMES</a></li>
<li><a class="doxyTocListItem" href="#st">SORT_MEMBERS_CTORS_1ST</a></li>
<li><a class="doxyTocListItem" href="#cfg_sort_member_docs">SORT_MEMBER_DOCS</a></li>
<li><a class="doxyTocListItem" href="#cfg_source_browser">SOURCE_BROWSER</a></li>
<li><a class="doxyTocListItem" href="#cfg_source_tooltips">SOURCE_TOOLTIPS</a></li>
<li><a class="doxyTocListItem" href="#cfg_sqlite3_output">SQLITE3_OUTPUT</a></li>
<li><a class="doxyTocListItem" href="#cfg_sqlite3_recreate_db">SQLITE3_RECREATE_DB</a></li>
<li><a class="doxyTocListItem" href="#cfg_strict_proto_matching">STRICT_PROTO_MATCHING</a></li>
<li><a class="doxyTocListItem" href="#cfg_strip_code_comments">STRIP_CODE_COMMENTS</a></li>
<li><a class="doxyTocListItem" href="#cfg_strip_from_inc_path">STRIP_FROM_INC_PATH</a></li>
<li><a class="doxyTocListItem" href="#cfg_strip_from_path">STRIP_FROM_PATH</a></li>
<li><a class="doxyTocListItem" href="#cfg_subgrouping">SUBGROUPING</a></li>
<li><a class="doxyTocListItem" href="#cfg_tab_size">TAB_SIZE</a></li>
<li><a class="doxyTocListItem" href="#cfg_tagfiles">TAGFILES</a></li>
<li><a class="doxyTocListItem" href="#cfg_template_relations">TEMPLATE_RELATIONS</a></li>
<li><a class="doxyTocListItem" href="#cfg_timestamp">TIMESTAMP</a></li>
<li><a class="doxyTocListItem" href="#cfg_toc_expand">TOC_EXPAND</a></li>
<li><a class="doxyTocListItem" href="#cfg_toc_include_headings">TOC_INCLUDE_HEADINGS</a></li>
<li><a class="doxyTocListItem" href="#cfg_treeview_width">TREEVIEW_WIDTH</a></li>
<li><a class="doxyTocListItem" href="#cfg_typedef_hides_struct">TYPEDEF_HIDES_STRUCT</a></li>
<li><a class="doxyTocListItem" href="#cfg_uml_limit_num_fields">UML_LIMIT_NUM_FIELDS</a></li>
<li><a class="doxyTocListItem" href="#cfg_uml_look">UML_LOOK</a></li>
<li><a class="doxyTocListItem" href="#cfg_uml_max_edge_labels">UML_MAX_EDGE_LABELS</a></li>
<li><a class="doxyTocListItem" href="#cfg_use_htags">USE_HTAGS</a></li>
<li><a class="doxyTocListItem" href="#cfg_use_mathjax">USE_MATHJAX</a></li>
<li><a class="doxyTocListItem" href="#cfg_use_mdfile_as_mainpage">USE_MDFILE_AS_MAINPAGE</a></li>
<li><a class="doxyTocListItem" href="#cfg_use_pdflatex">USE_PDFLATEX</a></li>
<li><a class="doxyTocListItem" href="#cfg_verbatim_headers">VERBATIM_HEADERS</a></li>
<li><a class="doxyTocListItem" href="#cfg_warnings">WARNINGS</a></li>
<li><a class="doxyTocListItem" href="#cfg_warn_as_error">WARN_AS_ERROR</a></li>
<li><a class="doxyTocListItem" href="#cfg_warn_format">WARN_FORMAT</a></li>
<li><a class="doxyTocListItem" href="#cfg_warn_if_doc_error">WARN_IF_DOC_ERROR</a></li>
<li><a class="doxyTocListItem" href="#cfg_warn_if_incomplete_doc">WARN_IF_INCOMPLETE_DOC</a></li>
<li><a class="doxyTocListItem" href="#cfg_warn_if_undocumented">WARN_IF_UNDOCUMENTED</a></li>
<li><a class="doxyTocListItem" href="#cfg_warn_if_undoc_enum_val">WARN_IF_UNDOC_ENUM_VAL</a></li>
<li><a class="doxyTocListItem" href="#cfg_warn_layout_file">WARN_LAYOUT_FILE</a></li>
<li><a class="doxyTocListItem" href="#cfg_warn_line_format">WARN_LINE_FORMAT</a></li>
<li><a class="doxyTocListItem" href="#cfg_warn_logfile">WARN_LOGFILE</a></li>
<li><a class="doxyTocListItem" href="#cfg_warn_no_paramdoc">WARN_NO_PARAMDOC</a></li>
<li><a class="doxyTocListItem" href="#cfg_xml_ns_memb_file_scope">XML_NS_MEMB_FILE_SCOPE</a></li>
<li><a class="doxyTocListItem" href="#cfg_xml_output">XML_OUTPUT</a></li>
<li><a class="doxyTocListItem" href="#cfg_xml_programlisting">XML_PROGRAMLISTING</a></li>
</ul>

## Project related configuration options {#config_project}


<p><a id="cfg_doxyfile_encoding"></a></p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">DOXYFILE_ENCODING</span></dt>
<dd>
<p>This tag specifies the encoding used for all characters in the configuration file that follow. The default is UTF-8 which is also the encoding used for all text before the first occurrence of this tag. Doxygen uses <span class="doxyComputerOutput">libiconv</span> (or the iconv built into <span class="doxyComputerOutput">libc</span>) for the transcoding. See <a href="https://www.gnu.org/software/libiconv/">https://www.gnu.org/software/libiconv/</a> for the list of possible encodings.</p>

<p>The default value is: <span class="doxyComputerOutput">UTF-8</span>.</p>

<p><a id="cfg_project_name"></a></p>
</dd>
<dt><span class="doxyComputerOutput">PROJECT_NAME</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">PROJECT_NAME</span> tag is a single word (or a sequence of words surrounded by double-quotes, unless you are using Doxywizard) that should identify the project for which the documentation is generated. This name is used in the title of most generated pages and in a few other places.</p>

<p>The default value is: <span class="doxyComputerOutput">My Project</span>.</p>

<p><a id="cfg_project_number"></a></p>
</dd>
<dt><span class="doxyComputerOutput">PROJECT_NUMBER</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">PROJECT_NUMBER</span> tag can be used to enter a project or revision number. This could be handy for archiving the generated documentation or if some version control system is used.</p>

<p><a id="cfg_project_brief"></a></p>
</dd>
<dt><span class="doxyComputerOutput">PROJECT_BRIEF</span></dt>
<dd>
<p>Using the <span class="doxyComputerOutput">PROJECT_BRIEF</span> tag one can provide an optional one line description for a project that appears at the top of each page and should give viewers a quick idea about the purpose of the project. Keep the description short.</p>

<p><a id="cfg_project_logo"></a></p>
</dd>
<dt><span class="doxyComputerOutput">PROJECT_LOGO</span></dt>
<dd>
<p>With the <span class="doxyComputerOutput">PROJECT_LOGO</span> tag one can specify a logo or an icon that is included in the documentation. The maximum height of the logo should not exceed 55 pixels and the maximum width should not exceed 200 pixels. Doxygen will copy the logo to the output directory.</p>

<p><a id="cfg_project_icon"></a></p>
</dd>
<dt><span class="doxyComputerOutput">PROJECT_ICON</span></dt>
<dd>
<p>With the <span class="doxyComputerOutput">PROJECT_ICON</span> tag one can specify an icon that is included in the tabs when the HTML document is shown. Doxygen will copy the logo to the output directory.</p>

<p><a id="cfg_output_directory"></a></p>
</dd>
<dt><span class="doxyComputerOutput">OUTPUT_DIRECTORY</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">OUTPUT_DIRECTORY</span> tag is used to specify the (relative or absolute) path into which the generated documentation will be written. If a relative path is entered, it will be relative to the location where Doxygen was started. If left blank the current directory will be used.</p>

<p><a id="cfg_create_subdirs"></a></p>
</dd>
<dt><span class="doxyComputerOutput">CREATE_SUBDIRS</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">CREATE_SUBDIRS</span> tag is set to <span class="doxyComputerOutput">YES</span> then Doxygen will create up to 4096 sub-directories (in 2 levels) under the output directory of each output format and will distribute the generated files over these directories. Enabling this option can be useful when feeding Doxygen a huge amount of source files, where putting all generated files in the same directory would otherwise cause performance problems for the file system. Adapt <span class="doxyComputerOutput">CREATE_SUBDIRS_LEVEL</span> to control the number of sub-directories.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_create_subdirs_level"></a></p>
</dd>
<dt><span class="doxyComputerOutput">CREATE_SUBDIRS_LEVEL</span></dt>
<dd>
<p>Controls the number of sub-directories that will be created when <span class="doxyComputerOutput">CREATE_SUBDIRS</span> tag is set to <span class="doxyComputerOutput">YES</span>. Level 0 represents 16 directories, and every level increment doubles the number of directories, resulting in 4096 directories at level 8 which is the default and also the maximum value. The sub-directories are organized in 2 levels, the first level always has a fixed number of 16 directories.</p>

<p>Minimum value: <span class="doxyComputerOutput">0</span>, maximum value: <span class="doxyComputerOutput">8</span>, default value: <span class="doxyComputerOutput">8</span>.</p>

<p>This tag requires that the tag <a href="#cfg_create_subdirs">CREATE_SUBDIRS</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_allow_unicode_names"></a></p>
</dd>
<dt><span class="doxyComputerOutput">ALLOW_UNICODE_NAMES</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">ALLOW_UNICODE_NAMES</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will allow non-ASCII characters to appear in the names of generated files. If set to <span class="doxyComputerOutput">NO</span>, non-ASCII characters will be escaped, for example _xE3_x81_x84 will be used for Unicode U+3044.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_output_language"></a></p>
</dd>
<dt><span class="doxyComputerOutput">OUTPUT_LANGUAGE</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">OUTPUT_LANGUAGE</span> tag is used to specify the language in which all documentation generated by Doxygen is written. Doxygen will use this information to generate all constant output in the proper language.</p>

<p>Possible values are: <span class="doxyComputerOutput">Afrikaans</span>, <span class="doxyComputerOutput">Arabic</span>, <span class="doxyComputerOutput">Armenian</span>, <span class="doxyComputerOutput">Brazilian</span>, <span class="doxyComputerOutput">Bulgarian</span>, <span class="doxyComputerOutput">Catalan</span>, <span class="doxyComputerOutput">Chinese</span>, <span class="doxyComputerOutput">Chinese-Traditional</span>, <span class="doxyComputerOutput">Croatian</span>, <span class="doxyComputerOutput">Czech</span>, <span class="doxyComputerOutput">Danish</span>, <span class="doxyComputerOutput">Dutch</span>, <span class="doxyComputerOutput">English</span> (United States), <span class="doxyComputerOutput">Esperanto</span>, <span class="doxyComputerOutput">Farsi</span> (Persian), <span class="doxyComputerOutput">Finnish</span>, <span class="doxyComputerOutput">French</span>, <span class="doxyComputerOutput">German</span>, <span class="doxyComputerOutput">Greek</span>, <span class="doxyComputerOutput">Hindi</span>, <span class="doxyComputerOutput">Hungarian</span>, <span class="doxyComputerOutput">Indonesian</span>, <span class="doxyComputerOutput">Italian</span>, <span class="doxyComputerOutput">Japanese</span>, <span class="doxyComputerOutput">Japanese-en</span> (Japanese with English messages), <span class="doxyComputerOutput">Korean</span>, <span class="doxyComputerOutput">Korean-en</span> (Korean with English messages), <span class="doxyComputerOutput">Latvian</span>, <span class="doxyComputerOutput">Lithuanian</span>, <span class="doxyComputerOutput">Macedonian</span>, <span class="doxyComputerOutput">Norwegian</span>, <span class="doxyComputerOutput">Persian</span> (Farsi), <span class="doxyComputerOutput">Polish</span>, <span class="doxyComputerOutput">Portuguese</span>, <span class="doxyComputerOutput">Romanian</span>, <span class="doxyComputerOutput">Russian</span>, <span class="doxyComputerOutput">Serbian</span>, <span class="doxyComputerOutput">Serbian-Cyrillic</span>, <span class="doxyComputerOutput">Slovak</span>, <span class="doxyComputerOutput">Slovene</span>, <span class="doxyComputerOutput">Spanish</span>, <span class="doxyComputerOutput">Swedish</span>, <span class="doxyComputerOutput">Turkish</span>, <span class="doxyComputerOutput">Ukrainian</span> and <span class="doxyComputerOutput">Vietnamese</span>.</p>

<p>The default value is: <span class="doxyComputerOutput">English</span>.</p>

<p><a id="cfg_brief_member_desc"></a></p>
</dd>
<dt><span class="doxyComputerOutput">BRIEF_MEMBER_DESC</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">BRIEF_MEMBER_DESC</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will include brief member descriptions after the members that are listed in the file and class documentation (similar to <span class="doxyComputerOutput">Javadoc</span>). Set to <span class="doxyComputerOutput">NO</span> to disable this.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_repeat_brief"></a></p>
</dd>
<dt><span class="doxyComputerOutput">REPEAT_BRIEF</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">REPEAT_BRIEF</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will prepend the brief description of a member or function before the detailed description 
<br/>
Note: If both <a href="#cfg_hide_undoc_members">HIDE_UNDOC_MEMBERS</a> and <a href="#cfg_brief_member_desc">BRIEF_MEMBER_DESC</a> are set to <span class="doxyComputerOutput">NO</span>, the brief descriptions will be completely suppressed.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_abbreviate_brief"></a></p>
</dd>
<dt><span class="doxyComputerOutput">ABBREVIATE_BRIEF</span></dt>
<dd>
<p>This tag implements a quasi-intelligent brief description abbreviator that is used to form the text in various listings. Each string in this list, if found as the leading text of the brief description, will be stripped from the text and the result, after processing the whole list, is used as the annotated text. Otherwise, the brief description is used as-is. If left blank, the following values are used (<span class="doxyComputerOutput">$name</span> is automatically replaced with the name of the entity): <span class="doxyComputerOutput">The $name class</span>, <span class="doxyComputerOutput">The $name widget</span>, <span class="doxyComputerOutput">The $name file</span>, <span class="doxyComputerOutput">is</span>, <span class="doxyComputerOutput">provides</span>, <span class="doxyComputerOutput">specifies</span>, <span class="doxyComputerOutput">contains</span>, <span class="doxyComputerOutput">represents</span>, <span class="doxyComputerOutput">a</span>, <span class="doxyComputerOutput">an</span> and <span class="doxyComputerOutput">the</span>.</p>

<p><a id="cfg_always_detailed_sec"></a></p>
</dd>
<dt><span class="doxyComputerOutput">ALWAYS_DETAILED_SEC</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">ALWAYS_DETAILED_SEC</span> and <a href="#cfg_repeat_brief">REPEAT_BRIEF</a> tags are both set to <span class="doxyComputerOutput">YES</span> then Doxygen will generate a detailed section even if there is only a brief description.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_inline_inherited_memb"></a></p>
</dd>
<dt><span class="doxyComputerOutput">INLINE_INHERITED_MEMB</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">INLINE_INHERITED_MEMB</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will show all inherited members of a class in the documentation of that class as if those members were ordinary class members. Constructors, destructors and assignment operators of the base classes will not be shown.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_full_path_names"></a></p>
</dd>
<dt><span class="doxyComputerOutput">FULL_PATH_NAMES</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">FULL_PATH_NAMES</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will prepend the full path before files name in the file list and in the header files. If set to <span class="doxyComputerOutput">NO</span> the shortest path that makes the file name unique will be used</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_strip_from_path"></a></p>
</dd>
<dt><span class="doxyComputerOutput">STRIP_FROM_PATH</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">STRIP_FROM_PATH</span> tag can be used to strip a user-defined part of the path. Stripping is only done if one of the specified strings matches the left-hand part of the path. The tag can be used to show relative paths in the file list. If left blank the directory from which Doxygen is run is used as the path to strip. 
<br/>
Note that you can specify absolute paths here, but also relative paths, which will be relative from the directory where Doxygen is started.</p>

<p>This tag requires that the tag <a href="#cfg_full_path_names">FULL_PATH_NAMES</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_strip_from_inc_path"></a></p>
</dd>
<dt><span class="doxyComputerOutput">STRIP_FROM_INC_PATH</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">STRIP_FROM_INC_PATH</span> tag can be used to strip a user-defined part of the path mentioned in the documentation of a class, which tells the reader which header file to include in order to use a class. If left blank only the name of the header file containing the class definition is used. Otherwise one should specify the list of include paths that are normally passed to the compiler using the <span class="doxyComputerOutput">-I</span> flag.</p>

<p><a id="cfg_short_names"></a></p>
</dd>
<dt><span class="doxyComputerOutput">SHORT_NAMES</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">SHORT_NAMES</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will generate much shorter (but less readable) file names. This can be useful if your file system doesn't support long names like on DOS, Mac, or CD-ROM.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_javadoc_autobrief"></a></p>
</dd>
<dt><span class="doxyComputerOutput">JAVADOC_AUTOBRIEF</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">JAVADOC_AUTOBRIEF</span> tag is set to <span class="doxyComputerOutput">YES</span> then Doxygen will interpret the first line (until the first dot, question mark or exclamation mark) of a Javadoc-style comment as the brief description. If set to <span class="doxyComputerOutput">NO</span>, the Javadoc-style will behave just like regular Qt-style comments (thus requiring an explicit <a href="/web-doxygen/docs/pages/commands/#cmdbrief">@brief</a> command for a brief description.)</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_javadoc_banner"></a></p>
</dd>
<dt><span class="doxyComputerOutput">JAVADOC_BANNER</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">JAVADOC_BANNER</span> tag is set to <span class="doxyComputerOutput">YES</span> then Doxygen will interpret a line such as</p>



<pre><code>/***************
</code></pre>


<p>as being the beginning of a Javadoc-style comment "banner". If set to <span class="doxyComputerOutput">NO</span>, the Javadoc-style will behave just like regular comments and it will not be interpreted by Doxygen.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_qt_autobrief"></a></p>
</dd>
<dt><span class="doxyComputerOutput">QT_AUTOBRIEF</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">QT_AUTOBRIEF</span> tag is set to <span class="doxyComputerOutput">YES</span> then Doxygen will interpret the first line (until the first dot, question mark or exclamation mark) of a Qt-style comment as the brief description. If set to <span class="doxyComputerOutput">NO</span>, the Qt-style will behave just like regular Qt-style comments (thus requiring an explicit <a href="/web-doxygen/docs/pages/commands/#cmdbrief">\brief</a> command for a brief description.)</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_multiline_cpp_is_brief"></a></p>
</dd>
<dt><span class="doxyComputerOutput">MULTILINE_CPP_IS_BRIEF</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">MULTILINE_CPP_IS_BRIEF</span> tag can be set to <span class="doxyComputerOutput">YES</span> to make Doxygen treat a multi-line C++ special comment block (i.e. a block of <span class="doxyComputerOutput">//!</span> or <span class="doxyComputerOutput">///</span> comments) as a brief description. This used to be the default behavior. The new default is to treat a multi-line C++ comment block as a detailed description. Set this tag to <span class="doxyComputerOutput">YES</span> if you prefer the old behavior instead. 
<br/>
Note that setting this tag to <span class="doxyComputerOutput">YES</span> also means that rational rose comments are not recognized any more.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_python_docstring"></a></p>
</dd>
<dt><span class="doxyComputerOutput">PYTHON_DOCSTRING</span></dt>
<dd>
<p>By default Python docstrings are displayed as preformatted text and Doxygen's special commands cannot be used. By setting <span class="doxyComputerOutput">PYTHON_DOCSTRING</span> to <span class="doxyComputerOutput">NO</span> the Doxygen's special commands can be used and the contents of the docstring documentation blocks is shown as Doxygen documentation.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_inherit_docs"></a></p>
</dd>
<dt><span class="doxyComputerOutput">INHERIT_DOCS</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">INHERIT_DOCS</span> tag is set to <span class="doxyComputerOutput">YES</span> then an undocumented member inherits the documentation from any documented member that it re-implements.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_separate_member_pages"></a></p>
</dd>
<dt><span class="doxyComputerOutput">SEPARATE_MEMBER_PAGES</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">SEPARATE_MEMBER_PAGES</span> tag is set to <span class="doxyComputerOutput">YES</span> then Doxygen will produce a new page for each member. If set to <span class="doxyComputerOutput">NO</span>, the documentation of a member will be part of the file/class/namespace that contains it.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_tab_size"></a></p>
</dd>
<dt><span class="doxyComputerOutput">TAB_SIZE</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">TAB_SIZE</span> tag can be used to set the number of spaces in a tab. Doxygen uses this value to replace tabs by spaces in code fragments.</p>

<p>Minimum value: <span class="doxyComputerOutput">1</span>, maximum value: <span class="doxyComputerOutput">16</span>, default value: <span class="doxyComputerOutput">4</span>.</p>

<p><a id="cfg_aliases"></a></p>
</dd>
<dt><span class="doxyComputerOutput">ALIASES</span></dt>
<dd>
<p>This tag can be used to specify a number of aliases that act as commands in the documentation. An alias has the form:</p>



<pre><code> name=value
</code></pre>


<p>For example adding</p>



<pre><code> "sideeffect=@par Side Effects:^^"
</code></pre>


<p>will allow you to put the command <span class="doxyComputerOutput">\sideeffect</span> (or <span class="doxyComputerOutput">@sideeffect</span>) in the documentation, which will result in a user-defined paragraph with heading "Side Effects:". Note that you cannot put <a href="/web-doxygen/docs/pages/commands/#cmdn">\n</a>'s in the value part of an alias to insert newlines (in the resulting output). You can put <span class="doxyComputerOutput">^^</span> in the value part of an alias to insert a newline as if a physical newline was in the original file. When you need a literal <span class="doxyComputerOutput">{</span> or <span class="doxyComputerOutput">}</span> or <span class="doxyComputerOutput">,</span> in the value part of an alias you have to escape them by means of a backslash (<span class="doxyComputerOutput">\</span>), this can lead to conflicts with the commands <span class="doxyComputerOutput">\{</span> and <span class="doxyComputerOutput">\}</span> for these it is advised to use the version <span class="doxyComputerOutput">@{</span> and <span class="doxyComputerOutput">@}</span> or use a double escape (<span class="doxyComputerOutput">\\{</span> and <span class="doxyComputerOutput">\\}</span>)</p>

<p><a id="cfg_optimize_output_for_c"></a></p>
</dd>
<dt><span class="doxyComputerOutput">OPTIMIZE_OUTPUT_FOR_C</span></dt>
<dd>
<p>Set the <span class="doxyComputerOutput">OPTIMIZE_OUTPUT_FOR_C</span> tag to <span class="doxyComputerOutput">YES</span> if your project consists of C sources only. Doxygen will then generate output that is more tailored for C. For instance, some of the names that are used will be different. The list of all members will be omitted, etc.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_optimize_output_java"></a></p>
</dd>
<dt><span class="doxyComputerOutput">OPTIMIZE_OUTPUT_JAVA</span></dt>
<dd>
<p>Set the <span class="doxyComputerOutput">OPTIMIZE_OUTPUT_JAVA</span> tag to <span class="doxyComputerOutput">YES</span> if your project consists of Java or Python sources only. Doxygen will then generate output that is more tailored for that language. For instance, namespaces will be presented as packages, qualified scopes will look different, etc.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_optimize_for_fortran"></a></p>
</dd>
<dt><span class="doxyComputerOutput">OPTIMIZE_FOR_FORTRAN</span></dt>
<dd>
<p>Set the <span class="doxyComputerOutput">OPTIMIZE_FOR_FORTRAN</span> tag to <span class="doxyComputerOutput">YES</span> if your project consists of Fortran sources. Doxygen will then generate output that is tailored for Fortran.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_optimize_output_vhdl"></a></p>
</dd>
<dt><span class="doxyComputerOutput">OPTIMIZE_OUTPUT_VHDL</span></dt>
<dd>
<p>Set the <span class="doxyComputerOutput">OPTIMIZE_OUTPUT_VHDL</span> tag to <span class="doxyComputerOutput">YES</span> if your project consists of VHDL sources. Doxygen will then generate output that is tailored for VHDL.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_optimize_output_slice"></a></p>
</dd>
<dt><span class="doxyComputerOutput">OPTIMIZE_OUTPUT_SLICE</span></dt>
<dd>
<p>Set the <span class="doxyComputerOutput">OPTIMIZE_OUTPUT_SLICE</span> tag to <span class="doxyComputerOutput">YES</span> if your project consists of Slice sources only. Doxygen will then generate output that is more tailored for that language. For instance, namespaces will be presented as modules, types will be separated into more groups, etc.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_extension_mapping"></a></p>
</dd>
<dt><span class="doxyComputerOutput">EXTENSION_MAPPING</span></dt>
<dd>
<p>Doxygen selects the parser to use depending on the extension of the files it parses. With this tag you can assign which parser to use for a given extension. Doxygen has a built-in mapping, but you can override or extend it using this tag. The format is <span class="doxyComputerOutput">ext=language</span>, where <span class="doxyComputerOutput">ext</span> is a file extension, and language is one of the parsers supported by Doxygen: IDL, Java, JavaScript, Csharp (C#), C, C++, Lex, D, PHP, md (Markdown), Objective-C, Python, Slice, VHDL, Fortran (fixed format Fortran: FortranFixed, free formatted Fortran: FortranFree, unknown formatted Fortran: Fortran. In the later case the parser tries to guess whether the code is fixed or free formatted code, this is the default for Fortran type files).</p>

<p>For instance to make Doxygen treat <span class="doxyComputerOutput">.inc</span> files as Fortran files (default is PHP), and <span class="doxyComputerOutput">.f</span> files as C (default is Fortran), use: <span class="doxyComputerOutput">inc=Fortran f=C</span>.</p>

<p><br/>
Note: For files without extension you can use <span class="doxyComputerOutput">no_extension</span> as a placeholder. 
<br/>
Note that for custom extensions you also need to set <a href="#cfg_file_patterns">FILE_PATTERNS</a> otherwise the files are not read by Doxygen. When specifying <span class="doxyComputerOutput">no_extension</span> you should add <span class="doxyComputerOutput">*</span> to the <a href="#cfg_file_patterns">FILE_PATTERNS</a>. 
<br/>
Note see also the list of <a href="/web-doxygen/docs/pages/starting/#default_file_extension_mapping">default file extension mappings</a>.</p>

<p><a id="cfg_markdown_support"></a></p>
</dd>
<dt><span class="doxyComputerOutput">MARKDOWN_SUPPORT</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">MARKDOWN_SUPPORT</span> tag is enabled then Doxygen pre-processes all comments according to the Markdown format, which allows for more readable documentation. See <a href="https://daringfireball.net/projects/markdown/">https://daringfireball.net/projects/markdown/</a> for details. The output of markdown processing is further processed by Doxygen, so you can mix Doxygen, HTML, and XML commands with Markdown formatting. Disable only in case of backward compatibilities issues.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_toc_include_headings"></a></p>
</dd>
<dt><span class="doxyComputerOutput">TOC_INCLUDE_HEADINGS</span></dt>
<dd>
<p>When the <span class="doxyComputerOutput">TOC_INCLUDE_HEADINGS</span> tag is set to a non-zero value, all headings up to that level are automatically included in the table of contents, even if they do not have an id attribute.</p>



:::info
<p>This feature currently applies only to Markdown headings.</p>
:::


<p>Minimum value: <span class="doxyComputerOutput">0</span>, maximum value: <span class="doxyComputerOutput">99</span>, default value: <span class="doxyComputerOutput">6</span>.</p>

<p>This tag requires that the tag <a href="#cfg_markdown_support">MARKDOWN_SUPPORT</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_markdown_id_style"></a></p>
</dd>
<dt><span class="doxyComputerOutput">MARKDOWN_ID_STYLE</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">MARKDOWN_ID_STYLE</span> tag can be used to specify the algorithm used to generate identifiers for the Markdown headings. Note: Every identifier is unique.</p>

<p>Possible values are: <span class="doxyComputerOutput">DOXYGEN</span> use a fixed 'autotoc_md' string followed by a sequence number starting at 0 and <span class="doxyComputerOutput">GITHUB</span> use the lower case version of title with any whitespace replaced by '-' and punctuation characters removed.</p>

<p>The default value is: <span class="doxyComputerOutput">DOXYGEN</span>.</p>

<p>This tag requires that the tag <a href="#cfg_markdown_support">MARKDOWN_SUPPORT</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_autolink_support"></a></p>
</dd>
<dt><span class="doxyComputerOutput">AUTOLINK_SUPPORT</span></dt>
<dd>
<p>When enabled Doxygen tries to link words that correspond to documented classes, or namespaces to their corresponding documentation. Such a link can be prevented in individual cases by putting a <span class="doxyComputerOutput">%</span> sign in front of the word or globally by setting <span class="doxyComputerOutput">AUTOLINK_SUPPORT</span> to <span class="doxyComputerOutput">NO</span>. Words listed in the <span class="doxyComputerOutput">AUTOLINK_IGNORE_WORDS</span> tag are excluded from automatic linking.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_autolink_ignore_words"></a></p>
</dd>
<dt><span class="doxyComputerOutput">AUTOLINK_IGNORE_WORDS</span></dt>
<dd>
<p>This tag specifies a list of words that, when matching the start of a word in the documentation, will suppress auto links generation, if it is enabled via AUTOLINK_SUPPORT. This list does not affect links explicitly created using # or the <a href="/web-doxygen/docs/pages/commands/#cmdlink">\link</a> or <a href="/web-doxygen/docs/pages/commands/#cmdref">\ref</a> commands.</p>

<p>This tag requires that the tag <a href="#cfg_autolink_support">AUTOLINK_SUPPORT</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_builtin_stl_support"></a></p>
</dd>
<dt><span class="doxyComputerOutput">BUILTIN_STL_SUPPORT</span></dt>
<dd>
<p>If you use STL classes (i.e. <span class="doxyComputerOutput">std::string</span>, <span class="doxyComputerOutput">std::vector</span>, etc.) but do not want to include (a tag file for) the STL sources as input, then you should set this tag to <span class="doxyComputerOutput">YES</span> in order to let Doxygen match functions declarations and definitions whose arguments contain STL classes (e.g. <span class="doxyComputerOutput">func(std::string</span>); versus <span class="doxyComputerOutput">func(std::string) {}</span>). This also makes the inheritance and collaboration diagrams that involve STL classes more complete and accurate.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_cpp_cli_support"></a></p>
</dd>
<dt><span class="doxyComputerOutput">CPP_CLI_SUPPORT</span></dt>
<dd>
<p>If you use Microsoft's C++/CLI language, you should set this option to <span class="doxyComputerOutput">YES</span> to enable parsing support.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_sip_support"></a></p>
</dd>
<dt><span class="doxyComputerOutput">SIP_SUPPORT</span></dt>
<dd>
<p>Set the <span class="doxyComputerOutput">SIP_SUPPORT</span> tag to <span class="doxyComputerOutput">YES</span> if your project consists of <a href="https://www.riverbankcomputing.com/software">sip</a> sources only. Doxygen will parse them like normal C++ but will assume all classes use public instead of private inheritance when no explicit protection keyword is present.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_idl_property_support"></a></p>
</dd>
<dt><span class="doxyComputerOutput">IDL_PROPERTY_SUPPORT</span></dt>
<dd>
<p>For Microsoft's IDL there are <span class="doxyComputerOutput">propget</span> and <span class="doxyComputerOutput">propput</span> attributes to indicate getter and setter methods for a property. Setting this option to <span class="doxyComputerOutput">YES</span> will make Doxygen to replace the get and set methods by a property in the documentation. This will only work if the methods are indeed getting or setting a simple type. If this is not the case, or you want to show the methods anyway, you should set this option to <span class="doxyComputerOutput">NO</span>.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_distribute_group_doc"></a></p>
</dd>
<dt><span class="doxyComputerOutput">DISTRIBUTE_GROUP_DOC</span></dt>
<dd>
<p>If member grouping is used in the documentation and the <span class="doxyComputerOutput">DISTRIBUTE_GROUP_DOC</span> tag is set to <span class="doxyComputerOutput">YES</span> then Doxygen will reuse the documentation of the first member in the group (if any) for the other members of the group. By default all members of a group must be documented explicitly.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_group_nested_compounds"></a></p>
</dd>
<dt><span class="doxyComputerOutput">GROUP_NESTED_COMPOUNDS</span></dt>
<dd>
<p>If one adds a struct or class to a group and this option is enabled, then also any nested class or struct is added to the same group. By default this option is disabled and one has to add nested compounds explicitly via <a href="/web-doxygen/docs/pages/commands/#cmdingroup">\ingroup</a>.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_subgrouping"></a></p>
</dd>
<dt><span class="doxyComputerOutput">SUBGROUPING</span></dt>
<dd>
<p>Set the <span class="doxyComputerOutput">SUBGROUPING</span> tag to <span class="doxyComputerOutput">YES</span> to allow class member groups of the same type (for instance a group of public functions) to be put as a subgroup of that type (e.g. under the Public Functions section). Set it to <span class="doxyComputerOutput">NO</span> to prevent subgrouping. Alternatively, this can be done per class using the <a href="/web-doxygen/docs/pages/commands/#cmdnosubgrouping">\nosubgrouping</a> command.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_inline_grouped_classes"></a></p>
</dd>
<dt><span class="doxyComputerOutput">INLINE_GROUPED_CLASSES</span></dt>
<dd>
<p>When the <span class="doxyComputerOutput">INLINE_GROUPED_CLASSES</span> tag is set to <span class="doxyComputerOutput">YES</span>, classes, structs and unions are shown inside the group in which they are included (e.g. using <a href="/web-doxygen/docs/pages/commands/#cmdingroup">\ingroup</a>) instead of on a separate page (for HTML and Man pages) or section (for <code>$\mbox{\LaTeX}$</code> and RTF). 
<br/>
Note that this feature does not work in combination with <a href="#cfg_separate_member_pages">SEPARATE_MEMBER_PAGES</a>.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_inline_simple_structs"></a></p>
</dd>
<dt><span class="doxyComputerOutput">INLINE_SIMPLE_STRUCTS</span></dt>
<dd>
<p>When the <span class="doxyComputerOutput">INLINE_SIMPLE_STRUCTS</span> tag is set to <span class="doxyComputerOutput">YES</span>, structs, classes, and unions with only public data fields or simple typedef fields will be shown inline in the documentation of the scope in which they are defined (i.e. file, namespace, or group documentation), provided this scope is documented. If set to <span class="doxyComputerOutput">NO</span>, structs, classes, and unions are shown on a separate page (for HTML and Man pages) or section (for <code>$\mbox{\LaTeX}$</code> and RTF).</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_typedef_hides_struct"></a></p>
</dd>
<dt><span class="doxyComputerOutput">TYPEDEF_HIDES_STRUCT</span></dt>
<dd>
<p>When <span class="doxyComputerOutput">TYPEDEF_HIDES_STRUCT</span> tag is enabled, a typedef of a struct, union, or enum is documented as struct, union, or enum with the name of the typedef. So <span class="doxyComputerOutput">typedef struct TypeS {} TypeT</span>, will appear in the documentation as a struct with name <span class="doxyComputerOutput">TypeT</span>. When disabled the typedef will appear as a member of a file, namespace, or class. And the struct will be named <span class="doxyComputerOutput">TypeS</span>. This can typically be useful for C code in case the coding convention dictates that all compound types are typedef'ed and only the typedef is referenced, never the tag name.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_lookup_cache_size"></a></p>
</dd>
<dt><span class="doxyComputerOutput">LOOKUP_CACHE_SIZE</span></dt>
<dd>
<p>The size of the symbol lookup cache can be set using <span class="doxyComputerOutput">LOOKUP_CACHE_SIZE</span>. This cache is used to resolve symbols given their name and scope. Since this can be an expensive process and often the same symbol appears multiple times in the code, Doxygen keeps a cache of pre-resolved symbols. If the cache is too small Doxygen will become slower. If the cache is too large, memory is wasted. The cache size is given by this formula: <code>$2^{(16+\mbox{LOOKUP\_CACHE\_SIZE})}$</code>. The valid range is 0..9, the default is 0, corresponding to a cache size of <code>$2^{16} = 65536$</code> symbols. At the end of a run Doxygen will report the cache usage and suggest the optimal cache size from a speed point of view.</p>

<p>Minimum value: <span class="doxyComputerOutput">0</span>, maximum value: <span class="doxyComputerOutput">9</span>, default value: <span class="doxyComputerOutput">0</span>.</p>

<p><a id="cfg_num_proc_threads"></a></p>
</dd>
<dt><span class="doxyComputerOutput">NUM_PROC_THREADS</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">NUM_PROC_THREADS</span> specifies the number of threads Doxygen is allowed to use during processing. When set to <span class="doxyComputerOutput">0</span> Doxygen will based this on the number of cores available in the system. You can set it explicitly to a value larger than 0 to get more control over the balance between CPU load and processing speed. At this moment only the input processing can be done using multiple threads. Since this is still an experimental feature the default is set to 1, which effectively disables parallel processing. Please report any issues you encounter. Generating dot graphs in parallel is controlled by the <span class="doxyComputerOutput">DOT_NUM_THREADS</span> setting.</p>

<p>Minimum value: <span class="doxyComputerOutput">0</span>, maximum value: <span class="doxyComputerOutput">32</span>, default value: <span class="doxyComputerOutput">1</span>.</p>

<p><a id="cfg_timestamp"></a></p>
</dd>
<dt><span class="doxyComputerOutput">TIMESTAMP</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">TIMESTAMP</span> tag is set different from <span class="doxyComputerOutput">NO</span> then each generated page will contain the date or date and time when the page was generated. Setting this to <span class="doxyComputerOutput">NO</span> can help when comparing the output of multiple runs.</p>

<p>Possible values are: <span class="doxyComputerOutput">YES</span>, <span class="doxyComputerOutput">NO</span>, <span class="doxyComputerOutput">DATETIME</span> and <span class="doxyComputerOutput">DATE</span>.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>
</dd>
</dl>

## Build related configuration options {#config_build}


<p><a id="cfg_extract_all"></a></p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">EXTRACT_ALL</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">EXTRACT_ALL</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will assume all entities in documentation are documented, even if no documentation was available. Private class members and static file members will be hidden unless the <a href="#cfg_extract_private">EXTRACT_PRIVATE</a> respectively <a href="#cfg_extract_static">EXTRACT_STATIC</a> tags are set to <span class="doxyComputerOutput">YES</span>.</p>


:::info
<p>This will also disable the warnings about undocumented members that are normally produced when <a href="#cfg_warnings">WARNINGS</a> is set to <span class="doxyComputerOutput">YES</span>.</p>
:::


<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_extract_private"></a></p>
</dd>
<dt><span class="doxyComputerOutput">EXTRACT_PRIVATE</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">EXTRACT_PRIVATE</span> tag is set to <span class="doxyComputerOutput">YES</span>, all private members of a class will be included in the documentation.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_extract_priv_virtual"></a></p>
</dd>
<dt><span class="doxyComputerOutput">EXTRACT_PRIV_VIRTUAL</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">EXTRACT_PRIV_VIRTUAL</span> tag is set to <span class="doxyComputerOutput">YES</span>, documented private virtual methods of a class will be included in the documentation.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_extract_package"></a></p>
</dd>
<dt><span class="doxyComputerOutput">EXTRACT_PACKAGE</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">EXTRACT_PACKAGE</span> tag is set to <span class="doxyComputerOutput">YES</span>, all members with package or internal scope will be included in the documentation.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_extract_static"></a></p>
</dd>
<dt><span class="doxyComputerOutput">EXTRACT_STATIC</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">EXTRACT_STATIC</span> tag is set to <span class="doxyComputerOutput">YES</span>, all static members of a file will be included in the documentation.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_extract_local_classes"></a></p>
</dd>
<dt><span class="doxyComputerOutput">EXTRACT_LOCAL_CLASSES</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">EXTRACT_LOCAL_CLASSES</span> tag is set to <span class="doxyComputerOutput">YES</span>, classes (and structs) defined locally in source files will be included in the documentation. If set to <span class="doxyComputerOutput">NO</span>, only classes defined in header files are included. Does not have any effect for Java sources.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_extract_local_methods"></a></p>
</dd>
<dt><span class="doxyComputerOutput">EXTRACT_LOCAL_METHODS</span></dt>
<dd>
<p>This flag is only useful for Objective-C code. If set to <span class="doxyComputerOutput">YES</span>, local methods, which are defined in the implementation section but not in the interface are included in the documentation. If set to <span class="doxyComputerOutput">NO</span>, only methods in the interface are included.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_extract_anon_nspaces"></a></p>
</dd>
<dt><span class="doxyComputerOutput">EXTRACT_ANON_NSPACES</span></dt>
<dd>
<p>If this flag is set to <span class="doxyComputerOutput">YES</span>, the members of anonymous namespaces will be extracted and appear in the documentation as a namespace called 'anonymous_namespace{file}', where file will be replaced with the base name of the file that contains the anonymous namespace. By default anonymous namespace are hidden.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_resolve_unnamed_params"></a></p>
</dd>
<dt><span class="doxyComputerOutput">RESOLVE_UNNAMED_PARAMS</span></dt>
<dd>
<p>If this flag is set to <span class="doxyComputerOutput">YES</span>, the name of an unnamed parameter in a declaration will be determined by the corresponding definition. By default unnamed parameters remain unnamed in the output.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_hide_undoc_members"></a></p>
</dd>
<dt><span class="doxyComputerOutput">HIDE_UNDOC_MEMBERS</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">HIDE_UNDOC_MEMBERS</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will hide all undocumented members inside documented classes or files. If set to <span class="doxyComputerOutput">NO</span> these members will be included in the various overviews, but no documentation section is generated. This option has no effect if <a href="#cfg_extract_all">EXTRACT_ALL</a> is enabled.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_hide_undoc_classes"></a></p>
</dd>
<dt><span class="doxyComputerOutput">HIDE_UNDOC_CLASSES</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">HIDE_UNDOC_CLASSES</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will hide all undocumented classes that are normally visible in the class hierarchy. If set to <span class="doxyComputerOutput">NO</span>, these classes will be included in the various overviews. This option will also hide undocumented C++ concepts if enabled. This option has no effect if <a href="#cfg_extract_all">EXTRACT_ALL</a> is enabled.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_hide_undoc_namespaces"></a></p>
</dd>
<dt><span class="doxyComputerOutput">HIDE_UNDOC_NAMESPACES</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">HIDE_UNDOC_NAMESPACES</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will hide all undocumented namespaces that are normally visible in the namespace hierarchy. If set to <span class="doxyComputerOutput">NO</span>, these namespaces will be included in the various overviews. This option has no effect if <a href="#cfg_extract_all">EXTRACT_ALL</a> is enabled.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_hide_friend_compounds"></a></p>
</dd>
<dt><span class="doxyComputerOutput">HIDE_FRIEND_COMPOUNDS</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">HIDE_FRIEND_COMPOUNDS</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will hide all friend declarations. If set to <span class="doxyComputerOutput">NO</span>, these declarations will be included in the documentation.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_hide_in_body_docs"></a></p>
</dd>
<dt><span class="doxyComputerOutput">HIDE_IN_BODY_DOCS</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">HIDE_IN_BODY_DOCS</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will hide any documentation blocks found inside the body of a function. If set to <span class="doxyComputerOutput">NO</span>, these blocks will be appended to the function's detailed documentation block.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_internal_docs"></a></p>
</dd>
<dt><span class="doxyComputerOutput">INTERNAL_DOCS</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">INTERNAL_DOCS</span> tag determines if documentation that is typed after a <a href="/web-doxygen/docs/pages/commands/#cmdinternal">\internal</a> command is included. If the tag is set to <span class="doxyComputerOutput">NO</span> then the documentation will be excluded. Set it to <span class="doxyComputerOutput">YES</span> to include the internal documentation.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_case_sense_names"></a></p>
</dd>
<dt><span class="doxyComputerOutput">CASE_SENSE_NAMES</span></dt>
<dd>
<p>With the correct setting of option <span class="doxyComputerOutput">CASE_SENSE_NAMES</span> Doxygen will better be able to match the capabilities of the underlying filesystem.</p>

<p>In case the filesystem is case sensitive (i.e. it supports files in the same directory whose names only differ in casing), the option must be set to <span class="doxyComputerOutput">YES</span> to properly deal with such files in case they appear in the input.</p>

<p>For filesystems that are not case sensitive the option should be set to <span class="doxyComputerOutput">NO</span> to properly deal with output files written for symbols that only differ in casing, such as for two classes, one named <span class="doxyComputerOutput">CLASS</span> and the other named <span class="doxyComputerOutput">Class</span>, and to also support references to files without having to specify the exact matching casing.</p>

<p>On Windows (including Cygwin) and macOS, users should typically set this option to <span class="doxyComputerOutput">NO</span>, whereas on Linux or other Unix flavors it should typically be set to <span class="doxyComputerOutput">YES</span>.</p>

<p>Possible values are: <span class="doxyComputerOutput">SYSTEM</span>, <span class="doxyComputerOutput">NO</span> and <span class="doxyComputerOutput">YES</span>.</p>

<p>The default value is: <span class="doxyComputerOutput">SYSTEM</span>.</p>

<p><a id="cfg_hide_scope_names"></a></p>
</dd>
<dt><span class="doxyComputerOutput">HIDE_SCOPE_NAMES</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">HIDE_SCOPE_NAMES</span> tag is set to <span class="doxyComputerOutput">NO</span> then Doxygen will show members with their full class and namespace scopes in the documentation. If set to <span class="doxyComputerOutput">YES</span>, the scope will be hidden.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_hide_compound_reference"></a></p>
</dd>
<dt><span class="doxyComputerOutput">HIDE_COMPOUND_REFERENCE</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">HIDE_COMPOUND_REFERENCE</span> tag is set to <span class="doxyComputerOutput">NO</span> (default) then Doxygen will append additional text to a page's title, such as Class Reference. If set to <span class="doxyComputerOutput">YES</span> the compound reference will be hidden.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_show_headerfile"></a></p>
</dd>
<dt><span class="doxyComputerOutput">SHOW_HEADERFILE</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">SHOW_HEADERFILE</span> tag is set to <span class="doxyComputerOutput">YES</span> then the documentation for a class will show which file needs to be included to use the class.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_show_include_files"></a></p>
</dd>
<dt><span class="doxyComputerOutput">SHOW_INCLUDE_FILES</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">SHOW_INCLUDE_FILES</span> tag is set to <span class="doxyComputerOutput">YES</span> then Doxygen will put a list of the files that are included by a file in the documentation of that file.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_show_grouped_memb_inc"></a></p>
</dd>
<dt><span class="doxyComputerOutput">SHOW_GROUPED_MEMB_INC</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">SHOW_GROUPED_MEMB_INC</span> tag is set to <span class="doxyComputerOutput">YES</span> then Doxygen will add for each grouped member an include statement to the documentation, telling the reader which file to include in order to use the member.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_force_local_includes"></a></p>
</dd>
<dt><span class="doxyComputerOutput">FORCE_LOCAL_INCLUDES</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">FORCE_LOCAL_INCLUDES</span> tag is set to <span class="doxyComputerOutput">YES</span> then Doxygen will list include files with double quotes in the documentation rather than with sharp brackets.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_inline_info"></a></p>
</dd>
<dt><span class="doxyComputerOutput">INLINE_INFO</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">INLINE_INFO</span> tag is set to <span class="doxyComputerOutput">YES</span> then a tag [inline] is inserted in the documentation for inline members.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_sort_member_docs"></a></p>
</dd>
<dt><span class="doxyComputerOutput">SORT_MEMBER_DOCS</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">SORT_MEMBER_DOCS</span> tag is set to <span class="doxyComputerOutput">YES</span> then Doxygen will sort the (detailed) documentation of file and class members alphabetically by member name. If set to <span class="doxyComputerOutput">NO</span>, the members will appear in declaration order.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_sort_brief_docs"></a></p>
</dd>
<dt><span class="doxyComputerOutput">SORT_BRIEF_DOCS</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">SORT_BRIEF_DOCS</span> tag is set to <span class="doxyComputerOutput">YES</span> then Doxygen will sort the brief descriptions of file, namespace and class members alphabetically by member name. If set to <span class="doxyComputerOutput">NO</span>, the members will appear in declaration order. Note that this will also influence the order of the classes in the class list.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="st"></a></p>
</dd>
<dt><span class="doxyComputerOutput">SORT_MEMBERS_CTORS_1ST</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">SORT_MEMBERS_CTORS_1ST</span> tag is set to <span class="doxyComputerOutput">YES</span> then Doxygen will sort the (brief and detailed) documentation of class members so that constructors and destructors are listed first. If set to <span class="doxyComputerOutput">NO</span> the constructors will appear in the respective orders defined by <a href="#cfg_sort_brief_docs">SORT_BRIEF_DOCS</a> and <a href="#cfg_sort_member_docs">SORT_MEMBER_DOCS</a>.</p>



:::info
<p>If <a href="#cfg_sort_brief_docs">SORT_BRIEF_DOCS</a> is set to <span class="doxyComputerOutput">NO</span> this option is ignored for sorting brief member documentation.</p>
:::



:::info
<p>If <a href="#cfg_sort_member_docs">SORT_MEMBER_DOCS</a> is set to <span class="doxyComputerOutput">NO</span> this option is ignored for sorting detailed member documentation.</p>
:::


<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_sort_group_names"></a></p>
</dd>
<dt><span class="doxyComputerOutput">SORT_GROUP_NAMES</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">SORT_GROUP_NAMES</span> tag is set to <span class="doxyComputerOutput">YES</span> then Doxygen will sort the hierarchy of group names into alphabetical order. If set to <span class="doxyComputerOutput">NO</span> the group names will appear in their defined order.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_sort_by_scope_name"></a></p>
</dd>
<dt><span class="doxyComputerOutput">SORT_BY_SCOPE_NAME</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">SORT_BY_SCOPE_NAME</span> tag is set to <span class="doxyComputerOutput">YES</span>, the class list will be sorted by fully-qualified names, including namespaces. If set to <span class="doxyComputerOutput">NO</span>, the class list will be sorted only by class name, not including the namespace part.</p>



:::info
<p>This option is not very useful if <a href="#cfg_hide_scope_names">HIDE_SCOPE_NAMES</a> is set to <span class="doxyComputerOutput">YES</span>.</p>
:::



:::info
<p>This option applies only to the class list, not to the alphabetical list.</p>
:::


<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_strict_proto_matching"></a></p>
</dd>
<dt><span class="doxyComputerOutput">STRICT_PROTO_MATCHING</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">STRICT_PROTO_MATCHING</span> option is enabled and Doxygen fails to do proper type resolution of all parameters of a function it will reject a match between the prototype and the implementation of a member function even if there is only one candidate or it is obvious which candidate to choose by doing a simple string match. By disabling <span class="doxyComputerOutput">STRICT_PROTO_MATCHING</span> Doxygen will still accept a match between prototype and implementation in such cases.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_generate_todolist"></a></p>
</dd>
<dt><span class="doxyComputerOutput">GENERATE_TODOLIST</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">GENERATE_TODOLIST</span> tag can be used to enable (<span class="doxyComputerOutput">YES</span>) or disable (<span class="doxyComputerOutput">NO</span>) the todo list. This list is created by putting <a href="/web-doxygen/docs/pages/commands/#cmdtodo">\todo</a> commands in the documentation.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_generate_testlist"></a></p>
</dd>
<dt><span class="doxyComputerOutput">GENERATE_TESTLIST</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">GENERATE_TESTLIST</span> tag can be used to enable (<span class="doxyComputerOutput">YES</span>) or disable (<span class="doxyComputerOutput">NO</span>) the test list. This list is created by putting <a href="/web-doxygen/docs/pages/commands/#cmdtest">\test</a> commands in the documentation.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_generate_buglist"></a></p>
</dd>
<dt><span class="doxyComputerOutput">GENERATE_BUGLIST</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">GENERATE_BUGLIST</span> tag can be used to enable (<span class="doxyComputerOutput">YES</span>) or disable (<span class="doxyComputerOutput">NO</span>) the bug list. This list is created by putting <a href="/web-doxygen/docs/pages/commands/#cmdbug">\bug</a> commands in the documentation.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_generate_deprecatedlist"></a></p>
</dd>
<dt><span class="doxyComputerOutput">GENERATE_DEPRECATEDLIST</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">GENERATE_DEPRECATEDLIST</span> tag can be used to enable (<span class="doxyComputerOutput">YES</span>) or disable (<span class="doxyComputerOutput">NO</span>) the deprecated list. This list is created by putting <a href="/web-doxygen/docs/pages/commands/#cmddeprecated">\deprecated</a> commands in the documentation.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_enabled_sections"></a></p>
</dd>
<dt><span class="doxyComputerOutput">ENABLED_SECTIONS</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">ENABLED_SECTIONS</span> tag can be used to enable conditional documentation sections, marked by <a href="/web-doxygen/docs/pages/commands/#cmdif">\if</a> &lt;section_label&gt; ... <a href="/web-doxygen/docs/pages/commands/#cmdendif">\endif</a> and <a href="/web-doxygen/docs/pages/commands/#cmdcond">\cond</a> &lt;section_label&gt; ... <a href="/web-doxygen/docs/pages/commands/#cmdendcond">\endcond</a> blocks.</p>

<p><a id="cfg_max_initializer_lines"></a></p>
</dd>
<dt><span class="doxyComputerOutput">MAX_INITIALIZER_LINES</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">MAX_INITIALIZER_LINES</span> tag determines the maximum number of lines that the initial value of a variable or macro / define can have for it to appear in the documentation. If the initializer consists of more lines than specified here it will be hidden. Use a value of 0 to hide initializers completely. The appearance of the value of individual variables and macros / defines can be controlled using <a href="/web-doxygen/docs/pages/commands/#cmdshowinitializer">\showinitializer</a> or <a href="/web-doxygen/docs/pages/commands/#cmdhideinitializer">\hideinitializer</a> command in the documentation regardless of this setting.</p>

<p>Minimum value: <span class="doxyComputerOutput">0</span>, maximum value: <span class="doxyComputerOutput">10000</span>, default value: <span class="doxyComputerOutput">30</span>.</p>

<p><a id="cfg_show_used_files"></a></p>
</dd>
<dt><span class="doxyComputerOutput">SHOW_USED_FILES</span></dt>
<dd>
<p>Set the <span class="doxyComputerOutput">SHOW_USED_FILES</span> tag to <span class="doxyComputerOutput">NO</span> to disable the list of files generated at the bottom of the documentation of classes and structs. If set to <span class="doxyComputerOutput">YES</span>, the list will mention the files that were used to generate the documentation.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_show_files"></a></p>
</dd>
<dt><span class="doxyComputerOutput">SHOW_FILES</span></dt>
<dd>
<p>Set the <span class="doxyComputerOutput">SHOW_FILES</span> tag to <span class="doxyComputerOutput">NO</span> to disable the generation of the Files page. This will remove the Files entry from the Quick Index and from the Folder Tree View (if specified).</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_show_namespaces"></a></p>
</dd>
<dt><span class="doxyComputerOutput">SHOW_NAMESPACES</span></dt>
<dd>
<p>Set the <span class="doxyComputerOutput">SHOW_NAMESPACES</span> tag to <span class="doxyComputerOutput">NO</span> to disable the generation of the Namespaces page. This will remove the Namespaces entry from the Quick Index and from the Folder Tree View (if specified).</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_file_version_filter"></a></p>
</dd>
<dt><span class="doxyComputerOutput">FILE_VERSION_FILTER</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">FILE_VERSION_FILTER</span> tag can be used to specify a program or script that Doxygen should invoke to get the current version for each file (typically from the version control system). Doxygen will invoke the program by executing (via <span class="doxyComputerOutput">popen()</span>) the command <span class="doxyComputerOutput">command input-file</span>, where <span class="doxyComputerOutput">command</span> is the value of the <span class="doxyComputerOutput">FILE_VERSION_FILTER</span> tag, and <span class="doxyComputerOutput">input-file</span> is the name of an input file provided by Doxygen. Whatever the program writes to standard output is used as the file version.
<br/>
 
<br/>
 Example of using a shell script as a filter for Unix:</p>



<pre><code> FILE_VERSION_FILTER = "/bin/sh versionfilter.sh"
</code></pre>


<p><br/>
 Example shell script for CVS:</p>



<pre><code>#!/bin/sh
cvs status $1 | sed -n 's/^[ \]*Working revision:[ \t]*\([0-9][0-9\.]*\).*/\1/p'
</code></pre>


<p><br/>
 Example shell script for Subversion:</p>



<pre><code>#!/bin/sh
svn stat -v $1 | sed -n 's/^[ A-Z?\*|!]\{1,15\}/r/;s/ \{1,15\}/\/r/;s/ .*//p'
</code></pre>


<p><br/>
 Example filter for ClearCase:</p>



<pre><code>FILE_VERSION_FILTER = "cleartool desc -fmt \%Vn"
</code></pre>

<p><a id="cfg_layout_file"></a></p>
</dd>
<dt><span class="doxyComputerOutput">LAYOUT_FILE</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">LAYOUT_FILE</span> tag can be used to specify a layout file which will be parsed by Doxygen. The layout file controls the global structure of the generated output files in an output format independent way. To create the layout file that represents Doxygen's defaults, run Doxygen with the <span class="doxyComputerOutput">-l</span> option. You can optionally specify a file name after the option, if omitted <span class="doxyComputerOutput">DoxygenLayout.xml</span> will be used as the name of the layout file. See also section <a href="/web-doxygen/docs/pages/customize/#layout">Changing the layout of pages</a> for information. 
<br/>
Note that if you run Doxygen from a directory containing a file called <span class="doxyComputerOutput">DoxygenLayout.xml</span>, Doxygen will parse it automatically even if the <span class="doxyComputerOutput">LAYOUT_FILE</span> tag is left empty.</p>

<p><a id="cfg_cite_bib_files"></a></p>
</dd>
<dt><span class="doxyComputerOutput">CITE_BIB_FILES</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">CITE_BIB_FILES</span> tag can be used to specify one or more <span class="doxyComputerOutput">bib</span> files containing the reference definitions. This must be a list of <span class="doxyComputerOutput">.bib</span> files. The <span class="doxyComputerOutput">.bib</span> extension is automatically appended if omitted. This requires the <span class="doxyComputerOutput">bibtex</span> tool to be installed. See also <a href="https://en.wikipedia.org/wiki/BibTeX">https://en.wikipedia.org/wiki/BibTeX</a> for more info. For <code>$\mbox{\LaTeX}$</code> the style of the bibliography can be controlled using <a href="#cfg_latex_bib_style">LATEX_BIB_STYLE</a>. To use this feature you need <span class="doxyComputerOutput">bibtex</span> and <span class="doxyComputerOutput">perl</span> available in the search path. See also <a href="/web-doxygen/docs/pages/commands/#cmdcite">\cite</a> for info how to create references.</p>

<p><a id="cfg_external_tool_path"></a></p>
</dd>
<dt><span class="doxyComputerOutput">EXTERNAL_TOOL_PATH</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">EXTERNAL_TOOL_PATH</span> tag can be used to extend the search path (PATH environment variable) so that external tools such as <span class="doxyComputerOutput">latex</span> and <span class="doxyComputerOutput">gs</span> can be found.</p>



:::info
<p>Directories specified with EXTERNAL_TOOL_PATH are added in front of the path already specified by the PATH variable, and are added in the order specified.</p>
:::



:::info
<p>This option is particularly useful for macOS version 14 (Sonoma) and higher, when running Doxygen from Doxywizard, because in this case any user-defined changes to the PATH are ignored. A typical example on macOS is to set</p>



<pre><code>EXTERNAL_TOOL_PATH = /Library/TeX/texbin /usr/local/bin
</code></pre>


<p>together with the standard path, the full search path used by doxygen when launching external tools will then become</p>



<pre><code>PATH=/Library/TeX/texbin:/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin
</code></pre>
:::
</dd>
</dl>

## Configuration options related to warning and progress messages {#config_messages}


<p><a id="cfg_quiet"></a></p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">QUIET</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">QUIET</span> tag can be used to turn on/off the messages that are generated to standard output by Doxygen. If <span class="doxyComputerOutput">QUIET</span> is set to <span class="doxyComputerOutput">YES</span> this implies that the messages are off.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_warnings"></a></p>
</dd>
<dt><span class="doxyComputerOutput">WARNINGS</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">WARNINGS</span> tag can be used to turn on/off the warning messages that are generated to standard error (<span class="doxyComputerOutput">stderr</span>) by Doxygen. If <span class="doxyComputerOutput">WARNINGS</span> is set to <span class="doxyComputerOutput">YES</span> this implies that the warnings are on. 
<br/>
 <b>Tip:</b> Turn warnings on while writing the documentation.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_warn_if_undocumented"></a></p>
</dd>
<dt><span class="doxyComputerOutput">WARN_IF_UNDOCUMENTED</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">WARN_IF_UNDOCUMENTED</span> tag is set to <span class="doxyComputerOutput">YES</span> then Doxygen will generate warnings for undocumented members. If <a href="#cfg_extract_all">EXTRACT_ALL</a> is set to <span class="doxyComputerOutput">YES</span> then this flag will automatically be disabled.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_warn_if_doc_error"></a></p>
</dd>
<dt><span class="doxyComputerOutput">WARN_IF_DOC_ERROR</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">WARN_IF_DOC_ERROR</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will generate warnings for potential errors in the documentation, such as documenting some parameters in a documented function twice, or documenting parameters that don't exist or using markup commands wrongly.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_warn_if_incomplete_doc"></a></p>
</dd>
<dt><span class="doxyComputerOutput">WARN_IF_INCOMPLETE_DOC</span></dt>
<dd>
<p>If <span class="doxyComputerOutput">WARN_IF_INCOMPLETE_DOC</span> is set to <span class="doxyComputerOutput">YES</span>, Doxygen will warn about incomplete function parameter documentation. If set to <span class="doxyComputerOutput">NO</span>, Doxygen will accept that some parameters have no documentation without warning.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_warn_no_paramdoc"></a></p>
</dd>
<dt><span class="doxyComputerOutput">WARN_NO_PARAMDOC</span></dt>
<dd>
<p>This <span class="doxyComputerOutput">WARN_NO_PARAMDOC</span> option can be enabled to get warnings for functions that are documented, but have no documentation for their parameters or return value. If set to <span class="doxyComputerOutput">NO</span>, Doxygen will only warn about wrong parameter documentation, but not about the absence of documentation. If <a href="#cfg_extract_all">EXTRACT_ALL</a> is set to <span class="doxyComputerOutput">YES</span> then this flag will automatically be disabled. See also <a href="#cfg_warn_if_incomplete_doc">WARN_IF_INCOMPLETE_DOC</a></p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_warn_if_undoc_enum_val"></a></p>
</dd>
<dt><span class="doxyComputerOutput">WARN_IF_UNDOC_ENUM_VAL</span></dt>
<dd>
<p>If <span class="doxyComputerOutput">WARN_IF_UNDOC_ENUM_VAL</span> option is set to <span class="doxyComputerOutput">YES</span>, Doxygen will warn about undocumented enumeration values. If set to <span class="doxyComputerOutput">NO</span>, Doxygen will accept undocumented enumeration values. If <a href="#cfg_extract_all">EXTRACT_ALL</a> is set to <span class="doxyComputerOutput">YES</span> then this flag will automatically be disabled.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_warn_layout_file"></a></p>
</dd>
<dt><span class="doxyComputerOutput">WARN_LAYOUT_FILE</span></dt>
<dd>
<p>If <span class="doxyComputerOutput">WARN_LAYOUT_FILE</span> option is set to <span class="doxyComputerOutput">YES</span>, Doxygen will warn about issues found while parsing the user defined layout file, such as missing or wrong elements. See also <a href="#cfg_layout_file">LAYOUT_FILE</a> for details. If set to <span class="doxyComputerOutput">NO</span>, problems with the layout file will be suppressed.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_warn_as_error"></a></p>
</dd>
<dt><span class="doxyComputerOutput">WARN_AS_ERROR</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">WARN_AS_ERROR</span> tag is set to <span class="doxyComputerOutput">YES</span> then Doxygen will immediately stop when a warning is encountered. If the <span class="doxyComputerOutput">WARN_AS_ERROR</span> tag is set to <span class="doxyComputerOutput">FAIL_ON_WARNINGS</span> then Doxygen will continue running as if <span class="doxyComputerOutput">WARN_AS_ERROR</span> tag is set to <span class="doxyComputerOutput">NO</span>, but at the end of the Doxygen process Doxygen will return with a non-zero status. If the <span class="doxyComputerOutput">WARN_AS_ERROR</span> tag is set to <span class="doxyComputerOutput">FAIL_ON_WARNINGS_PRINT</span> then Doxygen behaves like <span class="doxyComputerOutput">FAIL_ON_WARNINGS</span> but in case no <a href="#cfg_warn_logfile">WARN_LOGFILE</a> is defined Doxygen will not write the warning messages in between other messages but write them at the end of a run, in case a <a href="#cfg_warn_logfile">WARN_LOGFILE</a> is defined the warning messages will be besides being in the defined file also be shown at the end of a run, unless the <a href="#cfg_warn_logfile">WARN_LOGFILE</a> is defined as <span class="doxyComputerOutput">-</span> i.e. standard output (<span class="doxyComputerOutput">stdout</span>) in that case the behavior will remain as with the setting <span class="doxyComputerOutput">FAIL_ON_WARNINGS</span>.</p>

<p>Possible values are: <span class="doxyComputerOutput">NO</span>, <span class="doxyComputerOutput">YES</span>, <span class="doxyComputerOutput">FAIL_ON_WARNINGS</span> and <span class="doxyComputerOutput">FAIL_ON_WARNINGS_PRINT</span>.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_warn_format"></a></p>
</dd>
<dt><span class="doxyComputerOutput">WARN_FORMAT</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">WARN_FORMAT</span> tag determines the format of the warning messages that Doxygen can produce. The string should contain the <span class="doxyComputerOutput">$file</span>, <span class="doxyComputerOutput">$line</span>, and <span class="doxyComputerOutput">$text</span> tags, which will be replaced by the file and line number from which the warning originated and the warning text. Optionally the format may contain <span class="doxyComputerOutput">$version</span>, which will be replaced by the version of the file (if it could be obtained via <a href="#cfg_file_version_filter">FILE_VERSION_FILTER</a>)</p>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#cfg_warn_line_format">WARN_LINE_FORMAT</a></p></dd>
</dl>


<p>The default value is: <span class="doxyComputerOutput">$file:$line: $text</span>.</p>

<p><a id="cfg_warn_line_format"></a></p>
</dd>
<dt><span class="doxyComputerOutput">WARN_LINE_FORMAT</span></dt>
<dd>
<p>In the <span class="doxyComputerOutput">$text</span> part of the <a href="#cfg_warn_format">WARN_FORMAT</a> command it is possible that a reference to a more specific place is given. To make it easier to jump to this place (outside of Doxygen) the user can define a custom "cut" / "paste" string.</p>

<p>Example:</p>



<pre><code>  WARN_LINE_FORMAT = "'vi $file +$line'"
</code></pre>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#cfg_warn_format">WARN_FORMAT</a></p></dd>
</dl>


<p>The default value is: <span class="doxyComputerOutput">at line $line of file $file</span>.</p>

<p><a id="cfg_warn_logfile"></a></p>
</dd>
<dt><span class="doxyComputerOutput">WARN_LOGFILE</span></dt>
<dd><p>The <span class="doxyComputerOutput">WARN_LOGFILE</span> tag can be used to specify a file to which warning and error messages should be written. If left blank the output is written to standard error (<span class="doxyComputerOutput">stderr</span>). In case the file specified cannot be opened for writing the warning and error messages are written to standard error. When as file <span class="doxyComputerOutput">-</span> is specified the warning and error messages are written to standard output (<span class="doxyComputerOutput">stdout</span>).</p></dd>
</dl>

## Configuration options related to the input files {#config_input}


<p><a id="cfg_input"></a></p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">INPUT</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">INPUT</span> tag is used to specify the files and/or directories that contain documented source files. You may enter file names like <span class="doxyComputerOutput">myfile.cpp</span> or directories like <span class="doxyComputerOutput">/usr/src/myproject</span>. Separate the files or directories with spaces. See also <a href="#cfg_file_patterns">FILE_PATTERNS</a> and <a href="#cfg_extension_mapping">EXTENSION_MAPPING</a></p>


:::info
<p>If this tag is empty the current directory is searched.</p>
:::


<p><a id="cfg_input_encoding"></a></p>
</dd>
<dt><span class="doxyComputerOutput">INPUT_ENCODING</span></dt>
<dd>
<p>This tag can be used to specify the character encoding of the source files that Doxygen parses. Internally Doxygen uses the UTF-8 encoding. Doxygen uses <span class="doxyComputerOutput">libiconv</span> (or the <span class="doxyComputerOutput">iconv</span> built into <span class="doxyComputerOutput">libc</span>) for the transcoding. See <a href="https://www.gnu.org/software/libiconv/">the libiconv documentation</a> for the list of possible encodings.</p>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#cfg_input_file_encoding">INPUT_FILE_ENCODING</a></p></dd>
</dl>


<p>The default value is: <span class="doxyComputerOutput">UTF-8</span>.</p>

<p><a id="cfg_input_file_encoding"></a></p>
</dd>
<dt><span class="doxyComputerOutput">INPUT_FILE_ENCODING</span></dt>
<dd>
<p>This tag can be used to specify the character encoding of the source files that Doxygen parses. The <span class="doxyComputerOutput">INPUT_FILE_ENCODING</span> tag can be used to specify character encoding on a per file pattern basis. Doxygen will compare the file name with each pattern and apply the encoding instead of the default <a href="#cfg_input_encoding">INPUT_ENCODING</a> if there is a match. The character encodings are a list of the form: pattern=encoding (like <span class="doxyComputerOutput">*.php=ISO-8859-1</span>).</p>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#cfg_input_encoding">INPUT_ENCODING</a> for further information on supported encodings.</p></dd>
</dl>


<p><a id="cfg_file_patterns"></a></p>
</dd>
<dt><span class="doxyComputerOutput">FILE_PATTERNS</span></dt>
<dd>
<p>If the value of the <a href="#cfg_input">INPUT</a> tag contains directories, you can use the <span class="doxyComputerOutput">FILE_PATTERNS</span> tag to specify one or more wildcard patterns (like <span class="doxyComputerOutput">*.cpp</span> and <span class="doxyComputerOutput">*.h</span>) to filter out the source-files in the directories.
<br/>
 Note that for custom extensions or not directly supported extensions you also need to set <a href="#cfg_extension_mapping">EXTENSION_MAPPING</a> for the extension otherwise the files are not read by Doxygen.
<br/>
 Note the list of default checked file patterns might differ from the list of <a href="/web-doxygen/docs/pages/starting/#default_file_extension_mapping">default file extension mappings</a>.
<br/>
 If left blank the following patterns are tested: <span class="doxyComputerOutput">*.c</span>, <span class="doxyComputerOutput">*.cc</span>, <span class="doxyComputerOutput">*.cxx</span>, <span class="doxyComputerOutput">*.cxxm</span>, <span class="doxyComputerOutput">*.cpp</span>, <span class="doxyComputerOutput">*.cppm</span>, <span class="doxyComputerOutput">*.ccm</span>, <span class="doxyComputerOutput">*.c++</span>, <span class="doxyComputerOutput">*.c++m</span>, <span class="doxyComputerOutput">*.java</span>, <span class="doxyComputerOutput">*.ii</span>, <span class="doxyComputerOutput">*.ixx</span>, <span class="doxyComputerOutput">*.ipp</span>, <span class="doxyComputerOutput">*.i++</span>, <span class="doxyComputerOutput">*.inl</span>, <span class="doxyComputerOutput">*.idl</span>, <span class="doxyComputerOutput">*.ddl</span>, <span class="doxyComputerOutput">*.odl</span>, <span class="doxyComputerOutput">*.h</span>, <span class="doxyComputerOutput">*.hh</span>, <span class="doxyComputerOutput">*.hxx</span>, <span class="doxyComputerOutput">*.hpp</span>, <span class="doxyComputerOutput">*.h++</span>, <span class="doxyComputerOutput">*.l</span>, <span class="doxyComputerOutput">*.cs</span>, <span class="doxyComputerOutput">*.d</span>, <span class="doxyComputerOutput">*.php</span>, <span class="doxyComputerOutput">*.php4</span>, <span class="doxyComputerOutput">*.php5</span>, <span class="doxyComputerOutput">*.phtml</span>, <span class="doxyComputerOutput">*.inc</span>, <span class="doxyComputerOutput">*.m</span>, <span class="doxyComputerOutput">*.markdown</span>, <span class="doxyComputerOutput">*.md</span>, <span class="doxyComputerOutput">*.mm</span>, <span class="doxyComputerOutput">*.dox</span> (to be provided as Doxygen C comment), <span class="doxyComputerOutput">*.py</span>, <span class="doxyComputerOutput">*.pyw</span>, <span class="doxyComputerOutput">*.f90</span>, <span class="doxyComputerOutput">*.f95</span>, <span class="doxyComputerOutput">*.f03</span>, <span class="doxyComputerOutput">*.f08</span>, <span class="doxyComputerOutput">*.f18</span>, <span class="doxyComputerOutput">*.f</span>, <span class="doxyComputerOutput">*.for</span>, <span class="doxyComputerOutput">*.vhd</span>, <span class="doxyComputerOutput">*.vhdl</span>, <span class="doxyComputerOutput">*.ucf</span>, <span class="doxyComputerOutput">*.qsf</span> and <span class="doxyComputerOutput">*.ice</span>.</p>

<p><a id="cfg_recursive"></a></p>
</dd>
<dt><span class="doxyComputerOutput">RECURSIVE</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">RECURSIVE</span> tag can be used to specify whether or not subdirectories should be searched for input files as well.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_exclude"></a></p>
</dd>
<dt><span class="doxyComputerOutput">EXCLUDE</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">EXCLUDE</span> tag can be used to specify files and/or directories that should be excluded from the <a href="#cfg_input">INPUT</a> source files. This way you can easily exclude a subdirectory from a directory tree whose root is specified with the <a href="#cfg_input">INPUT</a> tag. 
<br/>
Note that relative paths are relative to the directory from which Doxygen is run.</p>

<p><a id="cfg_exclude_symlinks"></a></p>
</dd>
<dt><span class="doxyComputerOutput">EXCLUDE_SYMLINKS</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">EXCLUDE_SYMLINKS</span> tag can be used to select whether or not files or directories that are symbolic links (a Unix file system feature) are excluded from the input.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_exclude_patterns"></a></p>
</dd>
<dt><span class="doxyComputerOutput">EXCLUDE_PATTERNS</span></dt>
<dd>
<p>If the value of the <a href="#cfg_input">INPUT</a> tag contains directories, you can use the <span class="doxyComputerOutput">EXCLUDE_PATTERNS</span> tag to specify one or more wildcard patterns to exclude certain files from those directories. 
<br/>
Note that the wildcards are matched against the file with absolute path, so to exclude all test directories for example use the pattern <span class="doxyComputerOutput">*</span><span class="doxyComputerOutput">/test/</span><span class="doxyComputerOutput">*</span></p>

<p><a id="cfg_exclude_symbols"></a></p>
</dd>
<dt><span class="doxyComputerOutput">EXCLUDE_SYMBOLS</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">EXCLUDE_SYMBOLS</span> tag can be used to specify one or more symbol names (namespaces, classes, functions, etc.) that should be excluded from the output. The symbol name can be a fully qualified name, a word, or if the wildcard <span class="doxyComputerOutput">*</span> is used, a substring. Examples: <span class="doxyComputerOutput">ANamespace</span>, <span class="doxyComputerOutput">AClass</span>, <span class="doxyComputerOutput">ANamespace::AClass</span>, <span class="doxyComputerOutput">ANamespace::*Test</span></p>

<p><a id="cfg_example_path"></a></p>
</dd>
<dt><span class="doxyComputerOutput">EXAMPLE_PATH</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">EXAMPLE_PATH</span> tag can be used to specify one or more files or directories that contain example code fragments that are included (see the <a href="/web-doxygen/docs/pages/commands/#cmdinclude">\include</a> command).</p>

<p><a id="cfg_example_patterns"></a></p>
</dd>
<dt><span class="doxyComputerOutput">EXAMPLE_PATTERNS</span></dt>
<dd>
<p>If the value of the <a href="#cfg_example_path">EXAMPLE_PATH</a> tag contains directories, you can use the <span class="doxyComputerOutput">EXAMPLE_PATTERNS</span> tag to specify one or more wildcard pattern (like <span class="doxyComputerOutput">*.cpp</span> and <span class="doxyComputerOutput">*.h</span>) to filter out the source-files in the directories. If left blank all files are included.</p>

<p><a id="cfg_example_recursive"></a></p>
</dd>
<dt><span class="doxyComputerOutput">EXAMPLE_RECURSIVE</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">EXAMPLE_RECURSIVE</span> tag is set to <span class="doxyComputerOutput">YES</span> then subdirectories will be searched for input files to be used with the <a href="/web-doxygen/docs/pages/commands/#cmdinclude">\include</a> or <a href="/web-doxygen/docs/pages/commands/#cmddontinclude">\dontinclude</a> commands irrespective of the value of the <a href="#cfg_recursive">RECURSIVE</a> tag.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_image_path"></a></p>
</dd>
<dt><span class="doxyComputerOutput">IMAGE_PATH</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">IMAGE_PATH</span> tag can be used to specify one or more files or directories that contain images that are to be included in the documentation (see the <a href="/web-doxygen/docs/pages/commands/#cmdimage">\image</a> command).</p>

<p><a id="cfg_input_filter"></a></p>
</dd>
<dt><span class="doxyComputerOutput">INPUT_FILTER</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">INPUT_FILTER</span> tag can be used to specify a program that Doxygen should invoke to filter for each input file. Doxygen will invoke the filter program by executing (via <span class="doxyComputerOutput">popen()</span>) the command: 
<br/>
 <span class="doxyComputerOutput">&lt;filter&gt; &lt;input-file&gt;</span> 
<br/>
 where <span class="doxyComputerOutput">&lt;filter&gt;</span> is the value of the <span class="doxyComputerOutput">INPUT_FILTER</span> tag, and <span class="doxyComputerOutput">&lt;input-file&gt;</span> is the name of an input file. Doxygen will then use the output that the filter program writes to standard output. If <a href="#cfg_filter_patterns">FILTER_PATTERNS</a> is specified, this tag will be ignored. 
<br/>
Note that the filter must not add or remove lines; it is applied before the code is scanned, but not when the output code is generated. If lines are added or removed, the anchors will not be placed correctly. 
<br/>
Note that Doxygen will use the data processed and written to standard output for further processing, therefore nothing else, like debug statements or used commands (so in case of a Windows batch file always use <span class="doxyComputerOutput">@echo OFF</span>), should be written to standard output. 
<br/>
Note that for custom extensions or not directly supported extensions you also need to set <a href="#cfg_extension_mapping">EXTENSION_MAPPING</a> for the extension otherwise the files are not properly processed by Doxygen.
<br/></p>

<p><a id="cfg_filter_patterns"></a></p>
</dd>
<dt><span class="doxyComputerOutput">FILTER_PATTERNS</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">FILTER_PATTERNS</span> tag can be used to specify filters on a per file pattern basis. Doxygen will compare the file name with each pattern and apply the filter if there is a match. The filters are a list of the form: pattern=filter (like <span class="doxyComputerOutput">*.cpp=my_cpp_filter</span>). See <a href="#cfg_input_filter">INPUT_FILTER</a> for further information on how filters are used. If the <span class="doxyComputerOutput">FILTER_PATTERNS</span> tag is empty or if none of the patterns match the file name, <a href="#cfg_input_filter">INPUT_FILTER</a> is applied. 
<br/>
Note that for custom extensions or not directly supported extensions you also need to set <a href="#cfg_extension_mapping">EXTENSION_MAPPING</a> for the extension otherwise the files are not properly processed by Doxygen.
<br/></p>

<p><a id="cfg_filter_source_files"></a></p>
</dd>
<dt><span class="doxyComputerOutput">FILTER_SOURCE_FILES</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">FILTER_SOURCE_FILES</span> tag is set to <span class="doxyComputerOutput">YES</span>, the input filter (if set using <a href="#cfg_input_filter">INPUT_FILTER</a>) will also be used to filter the input files that are used for producing the source files to browse (i.e. when <a href="#cfg_source_browser">SOURCE_BROWSER</a> is set to <span class="doxyComputerOutput">YES</span>).</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_filter_source_patterns"></a></p>
</dd>
<dt><span class="doxyComputerOutput">FILTER_SOURCE_PATTERNS</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">FILTER_SOURCE_PATTERNS</span> tag can be used to specify source filters per file pattern. A pattern will override the setting for <a href="#cfg_filter_patterns">FILTER_PATTERN</a> (if any) and it is also possible to disable source filtering for a specific pattern using <span class="doxyComputerOutput">*.ext=</span> (so without naming a filter).</p>

<p>This tag requires that the tag <a href="#cfg_filter_source_files">FILTER_SOURCE_FILES</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_use_mdfile_as_mainpage"></a></p>
</dd>
<dt><span class="doxyComputerOutput">USE_MDFILE_AS_MAINPAGE</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">USE_MDFILE_AS_MAINPAGE</span> tag refers to the name of a markdown file that is part of the input, its contents will be placed on the main page (<span class="doxyComputerOutput">index.html</span>). This can be useful if you have a project on for instance GitHub and want to reuse the introduction page also for the Doxygen output.</p>

<p><a id="cfg_implicit_dir_docs"></a></p>
</dd>
<dt><span class="doxyComputerOutput">IMPLICIT_DIR_DOCS</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">IMPLICIT_DIR_DOCS</span> tag is set to <span class="doxyComputerOutput">YES</span>, any <span class="doxyComputerOutput">README.md</span> file found in sub-directories of the project's root, is used as the documentation for that sub-directory, except when the <span class="doxyComputerOutput">README.md</span> starts with a <a href="/web-doxygen/docs/pages/commands/#cmddir">\dir</a>, <a href="/web-doxygen/docs/pages/commands/#cmdpage">\page</a> or <a href="/web-doxygen/docs/pages/commands/#cmdmainpage">\mainpage</a> command. If set to <span class="doxyComputerOutput">NO</span>, the <span class="doxyComputerOutput">README.md</span> file needs to start with an explicit <a href="/web-doxygen/docs/pages/commands/#cmddir">\dir</a> command in order to be used as directory documentation.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_fortran_comment_after"></a></p>
</dd>
<dt><span class="doxyComputerOutput">FORTRAN_COMMENT_AFTER</span></dt>
<dd>
<p>The Fortran standard specifies that for fixed formatted Fortran code all characters from position 72 are to be considered as comment. A common extension is to allow longer lines before the automatic comment starts. The setting <span class="doxyComputerOutput">FORTRAN_COMMENT_AFTER</span> will also make it possible that longer lines can be processed before the automatic comment starts.</p>

<p>Minimum value: <span class="doxyComputerOutput">7</span>, maximum value: <span class="doxyComputerOutput">10000</span>, default value: <span class="doxyComputerOutput">72</span>.</p>
</dd>
</dl>

## Configuration options related to source browsing {#config_source_browser}


<p><a id="cfg_source_browser"></a></p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">SOURCE_BROWSER</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">SOURCE_BROWSER</span> tag is set to <span class="doxyComputerOutput">YES</span> then a list of source files will be generated. Documented entities will be cross-referenced with these sources. 
<br/>
Note: To get rid of all source code in the generated output, make sure that also <a href="#cfg_verbatim_headers">VERBATIM_HEADERS</a> is set to <span class="doxyComputerOutput">NO</span>.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_inline_sources"></a></p>
</dd>
<dt><span class="doxyComputerOutput">INLINE_SOURCES</span></dt>
<dd>
<p>Setting the <span class="doxyComputerOutput">INLINE_SOURCES</span> tag to <span class="doxyComputerOutput">YES</span> will include the body of functions, multi-line macros, enums or list initialized variables directly into the documentation.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_strip_code_comments"></a></p>
</dd>
<dt><span class="doxyComputerOutput">STRIP_CODE_COMMENTS</span></dt>
<dd>
<p>Setting the <span class="doxyComputerOutput">STRIP_CODE_COMMENTS</span> tag to <span class="doxyComputerOutput">YES</span> will instruct Doxygen to hide any special comment blocks from generated source code fragments. Normal C, C++ and Fortran comments will always remain visible.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_referenced_by_relation"></a></p>
</dd>
<dt><span class="doxyComputerOutput">REFERENCED_BY_RELATION</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">REFERENCED_BY_RELATION</span> tag is set to <span class="doxyComputerOutput">YES</span> then for each documented entity all documented functions referencing it will be listed.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_references_relation"></a></p>
</dd>
<dt><span class="doxyComputerOutput">REFERENCES_RELATION</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">REFERENCES_RELATION</span> tag is set to <span class="doxyComputerOutput">YES</span> then for each documented function all documented entities called/used by that function will be listed.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_references_link_source"></a></p>
</dd>
<dt><span class="doxyComputerOutput">REFERENCES_LINK_SOURCE</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">REFERENCES_LINK_SOURCE</span> tag is set to <span class="doxyComputerOutput">YES</span> and <a href="#cfg_source_browser">SOURCE_BROWSER</a> tag is set to <span class="doxyComputerOutput">YES</span> then the hyperlinks from functions in <a href="#cfg_references_relation">REFERENCES_RELATION</a> and <a href="#cfg_referenced_by_relation">REFERENCED_BY_RELATION</a> lists will link to the source code. Otherwise they will link to the documentation.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_source_tooltips"></a></p>
</dd>
<dt><span class="doxyComputerOutput">SOURCE_TOOLTIPS</span></dt>
<dd>
<p>If <span class="doxyComputerOutput">SOURCE_TOOLTIPS</span> is enabled (the default) then hovering a hyperlink in the source code will show a tooltip with additional information such as prototype, brief description and links to the definition and documentation. Since this will make the HTML file larger and loading of large files a bit slower, you can opt to disable this feature.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p>This tag requires that the tag <a href="#cfg_source_browser">SOURCE_BROWSER</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_use_htags"></a></p>
</dd>
<dt><span class="doxyComputerOutput">USE_HTAGS</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">USE_HTAGS</span> tag is set to <span class="doxyComputerOutput">YES</span> then the references to source code will point to the HTML generated by the <span class="doxyComputerOutput">htags(1)</span> tool instead of Doxygen built-in source browser. The <span class="doxyComputerOutput">htags</span> tool is part of GNU's global source tagging system (see <a href="https://www.gnu.org/software/global/global.html">https://www.gnu.org/software/global/global.html</a>). You will need version 4.8.6 or higher. 
<br/>
 To use it do the following:</p>


<ol class="doxyList" type="1">
<li>Install the latest version of <span class="doxyComputerOutput">global</span></li>
<li>Enable <a href="#cfg_source_browser">SOURCE_BROWSER</a> and <span class="doxyComputerOutput">USE_HTAGS</span> in the configuration file</li>
<li>Make sure the <a href="#cfg_input">INPUT</a> points to the root of the source tree</li>
<li>Run <span class="doxyComputerOutput">doxygen</span> as normal 
<br/>
 Doxygen will invoke <span class="doxyComputerOutput">htags</span> (and that will in turn invoke <span class="doxyComputerOutput">gtags</span>), so these tools must be available from the command line (i.e. in the search path). 
<br/>
 The result: instead of the source browser generated by Doxygen, the links to source code will now point to the output of <span class="doxyComputerOutput">htags</span>.</li>
</ol>
<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_source_browser">SOURCE_BROWSER</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_verbatim_headers"></a></p>
</dd>
<dt><span class="doxyComputerOutput">VERBATIM_HEADERS</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">VERBATIM_HEADERS</span> tag is set the <span class="doxyComputerOutput">YES</span> then Doxygen will generate a verbatim copy of the header file for each class for which an include is specified. Set to <span class="doxyComputerOutput">NO</span> to disable this.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>Section <a href="/web-doxygen/docs/pages/commands/#cmdclass">\class</a>.</p></dd>
</dl>


<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_clang_assisted_parsing"></a></p>
</dd>
<dt><span class="doxyComputerOutput">CLANG_ASSISTED_PARSING</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">CLANG_ASSISTED_PARSING</span> tag is set to <span class="doxyComputerOutput">YES</span> then Doxygen will use the <a href="http://clang.llvm.org/">clang parser</a> for more accurate parsing at the cost of reduced performance. This can be particularly helpful with template rich C++ code for which Doxygen's built-in parser lacks the necessary type information.</p>


:::info
<p>The availability of this option depends on whether or not Doxygen was generated with the <span class="doxyComputerOutput">-Duse_libclang=ON</span> option for CMake.</p>
:::


<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_clang_add_inc_paths"></a></p>
</dd>
<dt><span class="doxyComputerOutput">CLANG_ADD_INC_PATHS</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">CLANG_ASSISTED_PARSING</span> tag is set to <span class="doxyComputerOutput">YES</span> and the <span class="doxyComputerOutput">CLANG_ADD_INC_PATHS</span> tag is set to <span class="doxyComputerOutput">YES</span> then Doxygen will add the directory of each input to the include path.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p>This tag requires that the tag <a href="#cfg_clang_assisted_parsing">CLANG_ASSISTED_PARSING</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_clang_options"></a></p>
</dd>
<dt><span class="doxyComputerOutput">CLANG_OPTIONS</span></dt>
<dd>
<p>If clang assisted parsing is enabled you can provide the compiler with command line options that you would normally use when invoking the compiler. Note that the include paths will already be set by Doxygen for the files and directories specified with <a href="#cfg_input">INPUT</a> and <a href="#cfg_include_path">INCLUDE_PATH</a>.</p>

<p>This tag requires that the tag <a href="#cfg_clang_assisted_parsing">CLANG_ASSISTED_PARSING</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_clang_database_path"></a></p>
</dd>
<dt><span class="doxyComputerOutput">CLANG_DATABASE_PATH</span></dt>
<dd>
<p>If clang assisted parsing is enabled you can provide the clang parser with the path to the directory containing a file called <span class="doxyComputerOutput">compile_commands.json</span>. This file is the <a href="http://clang.llvm.org/docs/HowToSetupToolingForLLVM.html">compilation database</a> containing the options used when the source files were built. This is equivalent to specifying the <span class="doxyComputerOutput">-p</span> option to a clang tool, such as <span class="doxyComputerOutput">clang-check</span>. These options will then be passed to the parser. Any options specified with <a href="#cfg_clang_options">CLANG_OPTIONS</a> will be added as well.</p>


:::info
<p>The availability of this option depends on whether or not Doxygen was generated with the <span class="doxyComputerOutput">-Duse_libclang=ON</span> option for CMake.</p>
:::
</dd>
</dl>

## Configuration options related to the alphabetical class index {#config_index}


<p><a id="cfg_alphabetical_index"></a></p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">ALPHABETICAL_INDEX</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">ALPHABETICAL_INDEX</span> tag is set to <span class="doxyComputerOutput">YES</span>, an alphabetical index of all compounds will be generated. Enable this if the project contains a lot of classes, structs, unions or interfaces.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_ignore_prefix"></a></p>
</dd>
<dt><span class="doxyComputerOutput">IGNORE_PREFIX</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">IGNORE_PREFIX</span> tag can be used to specify a prefix (or a list of prefixes) that should be ignored while generating the index headers. The <span class="doxyComputerOutput">IGNORE_PREFIX</span> tag works for classes, function and member names. The entity will be placed in the alphabetical list under the first letter of the entity name that remains after removing the prefix.</p>

<p>This tag requires that the tag <a href="#cfg_alphabetical_index">ALPHABETICAL_INDEX</a> is set to <span class="doxyComputerOutput">YES</span>.</p>
</dd>
</dl>

## Configuration options related to the HTML output {#config_html}


<p><a id="cfg_generate_html"></a></p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">GENERATE_HTML</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">GENERATE_HTML</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will generate HTML output</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_html_output"></a></p>
</dd>
<dt><span class="doxyComputerOutput">HTML_OUTPUT</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">HTML_OUTPUT</span> tag is used to specify where the HTML docs will be put. If a relative path is entered the value of <a href="#cfg_output_directory">OUTPUT_DIRECTORY</a> will be put in front of it.</p>

<p>The default directory is: <span class="doxyComputerOutput">html</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_html_file_extension"></a></p>
</dd>
<dt><span class="doxyComputerOutput">HTML_FILE_EXTENSION</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">HTML_FILE_EXTENSION</span> tag can be used to specify the file extension for each generated HTML page (for example: <span class="doxyComputerOutput">.htm, .php, .asp</span>).</p>

<p>The default value is: <span class="doxyComputerOutput">.html</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_html_header"></a></p>
</dd>
<dt><span class="doxyComputerOutput">HTML_HEADER</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">HTML_HEADER</span> tag can be used to specify a user-defined HTML header file for each generated HTML page. If the tag is left blank Doxygen will generate a standard header. 
<br/>
 To get valid HTML the header file that includes any scripts and style sheets that Doxygen needs, which is dependent on the configuration options used (e.g. the setting <a href="#cfg_generate_treeview">GENERATE_TREEVIEW</a>). It is highly recommended to start with a default header using</p>



<pre><code>doxygen -w html new_header.html new_footer.html new_stylesheet.css YourConfigFile
</code></pre>


<p>and then modify the file <span class="doxyComputerOutput">new_header.html</span>.</p>

<p>See also section <a href="/web-doxygen/docs/pages/doxygen-usage">Doxygen usage</a> for information on how to generate the default header that Doxygen normally uses.</p>


:::info
<p>The header is subject to change so you typically have to regenerate the default header when upgrading to a newer version of Doxygen. The following markers have a special meaning inside the header and footer:</p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">$title</span></dt>
<dd><p>will be replaced with the title of the page.</p></dd>
<dt><span class="doxyComputerOutput">$datetime</span></dt>
<dd><p>will be replaced with the current date and time.</p></dd>
<dt><span class="doxyComputerOutput">$date</span></dt>
<dd><p>will be replaced with the current date.</p></dd>
<dt><span class="doxyComputerOutput">$time</span></dt>
<dd><p>will be replaced with the current time.</p></dd>
<dt><span class="doxyComputerOutput">$year</span></dt>
<dd><p>will be replaces with the current year.</p></dd>
<dt><span class="doxyComputerOutput">$showdate(&lt;format&gt;)</span></dt>
<dd><p>will be replaced with the current date and time according to the format as specified by <span class="doxyComputerOutput">&lt;format&gt;</span>. The <span class="doxyComputerOutput">&lt;format&gt;</span> follows the rules as specified for the <a href="/web-doxygen/docs/pages/commands/#cmdshowdate">\showdate</a> command with the exception that no <span class="doxyComputerOutput">)</span> is allowed in the <span class="doxyComputerOutput">&lt;format&gt;</span>.</p></dd>
<dt><span class="doxyComputerOutput">$doxygenversion</span></dt>
<dd><p>will be replaced with the version of Doxygen</p></dd>
<dt><span class="doxyComputerOutput">$projectname</span></dt>
<dd><p>will be replaced with the name of the project (see <a href="#cfg_project_name">PROJECT_NAME</a>)</p></dd>
<dt><span class="doxyComputerOutput">$projectnumber</span></dt>
<dd><p>will be replaced with the project number (see <a href="#cfg_project_number">PROJECT_NUMBER</a>)</p></dd>
<dt><span class="doxyComputerOutput">$projectbrief</span></dt>
<dd><p>will be replaced with the project brief description (see <a href="#cfg_project_brief">PROJECT_BRIEF</a>)</p></dd>
<dt><span class="doxyComputerOutput">$projectlogo</span></dt>
<dd><p>will be replaced with the project logo (see <a href="#cfg_project_logo">PROJECT_LOGO</a>)</p></dd>
<dt><span class="doxyComputerOutput">$generatedby</span></dt>
<dd><p>will be replaced with the output language dependent version of the text "Generated by" or when the <a href="#cfg_timestamp">TIMESTAMP</a> is set by the output language dependent version of the text "Generated on <span class="doxyComputerOutput">$datetime</span> for <span class="doxyComputerOutput">$projectname</span> by".</p></dd>
<dt><span class="doxyComputerOutput">$stylesheet</span></dt>
<dd><p>will be replaced with the setting of <a href="#cfg_html_stylesheet">HTML_STYLESHEET</a> unless it is empty or the file in which case it is replaced by the default setting <span class="doxyComputerOutput">doxygen.css</span>.</p></dd>
<dt><span class="doxyComputerOutput">$extrastylesheet</span></dt>
<dd><p>will be replaced with the setting of <a href="#cfg_html_extra_stylesheet">HTML_EXTRA_STYLESHEET</a> including the required HTML tags for each extra stylesheet.</p></dd>
<dt><span class="doxyComputerOutput">$treeview</span></dt>
<dd><p>will be replaced with links to the JavaScript and style sheets needed for the navigation tree (or an empty string when <a href="#cfg_generate_treeview">GENERATE_TREEVIEW</a> is disabled).</p></dd>
<dt><span class="doxyComputerOutput">$search</span></dt>
<dd><p>will be replaced with a links to the JavaScript and style sheets needed for the search engine (or an empty string when <a href="#cfg_searchengine">SEARCHENGINE</a> is disabled).</p></dd>
<dt><span class="doxyComputerOutput">$searchbox</span></dt>
<dd><p>will be replaced with the HTML code needed for the search box to be shown (or an empty string when <a href="#cfg_searchengine">SEARCHENGINE</a> is disabled).</p></dd>
<dt><span class="doxyComputerOutput">$mathjax</span></dt>
<dd><p>will be replaced with a links to the JavaScript and style sheets needed for the MathJax feature (or an empty string when <a href="#cfg_use_mathjax">USE_MATHJAX</a> is disabled).</p></dd>
<dt><span class="doxyComputerOutput">$relpath^</span></dt>
<dd><p>If <a href="#cfg_create_subdirs">CREATE_SUBDIRS</a> is enabled, the command <span class="doxyComputerOutput">$relpath^</span> can be used to produce a relative path to the root of the HTML output directory, e.g. use <span class="doxyComputerOutput">$relpath^doxygen.css</span>, to refer to the standard style sheet.</p></dd>
<dt><span class="doxyComputerOutput">$navpath</span></dt>
<dd><p>will be replaced with a path as required by <a href="#cfg_generate_treeview">GENERATE_TREEVIEW</a></p></dd>
</dl>
:::


<p>To cope with differences in the layout of the header and footer that depend on configuration settings, the header can also contain special blocks that will be copied to the output or skipped depending on the configuration. Such blocks have the following form:</p>



<pre><code> &lt;!--BEGIN BLOCKNAME--&gt;
 Some context copied when condition BLOCKNAME holds
 &lt;!--END BLOCKNAME--&gt;
 &lt;!--BEGIN !BLOCKNAME--&gt;
 Some context copied when condition BLOCKNAME does not hold
 &lt;!--END !BLOCKNAME--&gt;
</code></pre>


<p>The following block names are supported:</p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">DISABLE_INDEX</span></dt>
<dd><p>Content within this block is copied to the output if the <a href="#cfg_disable_index">DISABLE_INDEX</a> option is enabled (so when the index is disabled).</p></dd>
<dt><span class="doxyComputerOutput">GENERATE_TREEVIEW</span></dt>
<dd><p>Content within this block is copied to the output if the <a href="#cfg_generate_treeview">GENERATE_TREEVIEW</a> option is enabled.</p></dd>
<dt><span class="doxyComputerOutput">SEARCHENGINE</span></dt>
<dd><p>Content within this block is copied to the output if the <a href="#cfg_searchengine">SEARCHENGINE</a> option is enabled.</p></dd>
<dt><span class="doxyComputerOutput">PROJECT_NAME</span></dt>
<dd><p>Content within the block is copied to the output if the <a href="#cfg_project_name">PROJECT_NAME</a> option is not empty.</p></dd>
<dt><span class="doxyComputerOutput">PROJECT_NUMBER</span></dt>
<dd><p>Content within the block is copied to the output if the <a href="#cfg_project_number">PROJECT_NUMBER</a> option is not empty.</p></dd>
<dt><span class="doxyComputerOutput">PROJECT_BRIEF</span></dt>
<dd><p>Content within the block is copied to the output if the <a href="#cfg_project_brief">PROJECT_BRIEF</a> option is not empty.</p></dd>
<dt><span class="doxyComputerOutput">PROJECT_LOGO</span></dt>
<dd><p>Content within the block is copied to the output if the <a href="#cfg_project_logo">PROJECT_LOGO</a> option is not empty.</p></dd>
<dt><span class="doxyComputerOutput">FULL_SIDEBAR</span></dt>
<dd><p>Content within the block is copied to the output if the <a href="#cfg_full_sidebar">FULL_SIDEBAR</a>, <a href="#cfg_disable_index">DISABLE_INDEX</a> and <a href="#cfg_generate_treeview">GENERATE_TREEVIEW</a> options are all enabled.</p></dd>
<dt><span class="doxyComputerOutput">TITLEAREA</span></dt>
<dd><p>Content within this block is copied to the output if a title is visible at the top of each page. This is the case if either <a href="#cfg_project_name">PROJECT_NAME</a>, <a href="#cfg_project_brief">PROJECT_BRIEF</a>, <a href="#cfg_project_logo">PROJECT_LOGO</a> is filled in or if both <a href="#cfg_disable_index">DISABLE_INDEX</a> and <a href="#cfg_searchengine">SEARCHENGINE</a> are enabled.</p></dd>
</dl>
<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_html_footer"></a></p>
</dd>
<dt><span class="doxyComputerOutput">HTML_FOOTER</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">HTML_FOOTER</span> tag can be used to specify a user-defined HTML footer for each generated HTML page. If the tag is left blank Doxygen will generate a standard footer.</p>

<p>See <a href="#cfg_html_header">HTML_HEADER</a> for more information on how to generate a default footer and what special commands can be used inside the footer.</p>

<p>See also section <a href="/web-doxygen/docs/pages/doxygen-usage">Doxygen usage</a> for information on how to generate the default footer that Doxygen normally uses.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_html_stylesheet"></a></p>
</dd>
<dt><span class="doxyComputerOutput">HTML_STYLESHEET</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">HTML_STYLESHEET</span> tag can be used to specify a user-defined cascading style sheet that is used by each HTML page. It can be used to fine-tune the look of the HTML output. If left blank Doxygen will generate a default style sheet.</p>

<p>See also section <a href="/web-doxygen/docs/pages/doxygen-usage">Doxygen usage</a> for information on how to generate the style sheet that Doxygen normally uses.</p>


:::info
<p>It is recommended to use <a href="#cfg_html_extra_stylesheet">HTML_EXTRA_STYLESHEET</a> instead of this tag, as it is more robust and this tag (<span class="doxyComputerOutput">HTML_STYLESHEET</span>) will in the future become obsolete.</p>
:::


<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_html_extra_stylesheet"></a></p>
</dd>
<dt><span class="doxyComputerOutput">HTML_EXTRA_STYLESHEET</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">HTML_EXTRA_STYLESHEET</span> tag can be used to specify additional user-defined cascading style sheets that are included after the standard style sheets created by Doxygen. Using this option one can overrule certain style aspects. This is preferred over using <a href="#cfg_html_stylesheet">HTML_STYLESHEET</a> since it does not replace the standard style sheet and is therefore more robust against future updates. Doxygen will copy the style sheet files to the output directory.</p>



:::info
<p>The order of the extra style sheet files is of importance (e.g. the last style sheet in the list overrules the setting of the previous ones in the list).</p>
:::



:::info
<p>Since the styling of scrollbars can currently not be overruled in Webkit/Chromium, the styling will be left out of the default doxygen.css if one or more extra stylesheets have been specified. So if scrollbar customization is desired it has to be added explicitly. Here is an example style sheet that gives the contents area a fixed width:</p>



<pre><code>body {
        background-color: #CCC;
        color: black;
        margin: 0;
}

div.contents {
        margin-bottom: 10px;
        padding: 12px;
        margin-left: auto;
        margin-right: auto;
        width: 960px;
        background-color: white;
        border-radius: 8px;
}

#titlearea {
        background-color: white;
}

hr.footer {
        display: none;
}

.footer {
        background-color: #AAA;
}
</code></pre>
:::


<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_html_extra_files"></a></p>
</dd>
<dt><span class="doxyComputerOutput">HTML_EXTRA_FILES</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">HTML_EXTRA_FILES</span> tag can be used to specify one or more extra images or other source files which should be copied to the HTML output directory. Note that these files will be copied to the base HTML output directory. Use the <span class="doxyComputerOutput">$relpath^</span> marker in the <a href="#cfg_html_header">HTML_HEADER</a> and/or <a href="#cfg_html_footer">HTML_FOOTER</a> files to load these files. In the <a href="#cfg_html_stylesheet">HTML_STYLESHEET</a> file, use the file name only. Also note that the files will be copied as-is; there are no commands or markers available.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_html_colorstyle"></a></p>
</dd>
<dt><span class="doxyComputerOutput">HTML_COLORSTYLE</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">HTML_COLORSTYLE</span> tag can be used to specify if the generated HTML output should be rendered with a dark or light theme.</p>

<p>Possible values are: <span class="doxyComputerOutput">LIGHT</span> always generates light mode output, <span class="doxyComputerOutput">DARK</span> always generates dark mode output, <span class="doxyComputerOutput">AUTO_LIGHT</span> automatically sets the mode according to the user preference, uses light mode if no preference is set (the default), <span class="doxyComputerOutput">AUTO_DARK</span> automatically sets the mode according to the user preference, uses dark mode if no preference is set and <span class="doxyComputerOutput">TOGGLE</span> allows a user to switch between light and dark mode via a button.</p>

<p>The default value is: <span class="doxyComputerOutput">AUTO_LIGHT</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_html_colorstyle_hue"></a></p>
</dd>
<dt><span class="doxyComputerOutput">HTML_COLORSTYLE_HUE</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">HTML_COLORSTYLE_HUE</span> tag controls the color of the HTML output. Doxygen will adjust the colors in the style sheet and background images according to this color. Hue is specified as an angle on a color-wheel, see <a href="https://en.wikipedia.org/wiki/Hue">https://en.wikipedia.org/wiki/Hue</a> for more information. For instance the value 0 represents red, 60 is yellow, 120 is green, 180 is cyan, 240 is blue, 300 purple, and 360 is red again.</p>

<p>Minimum value: <span class="doxyComputerOutput">0</span>, maximum value: <span class="doxyComputerOutput">359</span>, default value: <span class="doxyComputerOutput">220</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_html_colorstyle_sat"></a></p>
</dd>
<dt><span class="doxyComputerOutput">HTML_COLORSTYLE_SAT</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">HTML_COLORSTYLE_SAT</span> tag controls the purity (or saturation) of the colors in the HTML output. For a value of 0 the output will use gray-scales only. A value of 255 will produce the most vivid colors.</p>

<p>Minimum value: <span class="doxyComputerOutput">0</span>, maximum value: <span class="doxyComputerOutput">255</span>, default value: <span class="doxyComputerOutput">100</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_html_colorstyle_gamma"></a></p>
</dd>
<dt><span class="doxyComputerOutput">HTML_COLORSTYLE_GAMMA</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">HTML_COLORSTYLE_GAMMA</span> tag controls the gamma correction applied to the luminance component of the colors in the HTML output. Values below 100 gradually make the output lighter, whereas values above 100 make the output darker. The value divided by 100 is the actual gamma applied, so 80 represents a gamma of 0.8, The value 220 represents a gamma of 2.2, and 100 does not change the gamma.</p>

<p>Minimum value: <span class="doxyComputerOutput">40</span>, maximum value: <span class="doxyComputerOutput">240</span>, default value: <span class="doxyComputerOutput">80</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_html_dynamic_menus"></a></p>
</dd>
<dt><span class="doxyComputerOutput">HTML_DYNAMIC_MENUS</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">HTML_DYNAMIC_MENUS</span> tag is set to <span class="doxyComputerOutput">YES</span> then the generated HTML documentation will contain a main index with vertical navigation menus that are dynamically created via JavaScript. If disabled, the navigation index will consists of multiple levels of tabs that are statically embedded in every HTML page. Disable this option to support browsers that do not have JavaScript, like the Qt help browser.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_html_dynamic_sections"></a></p>
</dd>
<dt><span class="doxyComputerOutput">HTML_DYNAMIC_SECTIONS</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">HTML_DYNAMIC_SECTIONS</span> tag is set to <span class="doxyComputerOutput">YES</span> then the generated HTML documentation will contain sections that can be hidden and shown after the page has loaded.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_html_code_folding"></a></p>
</dd>
<dt><span class="doxyComputerOutput">HTML_CODE_FOLDING</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">HTML_CODE_FOLDING</span> tag is set to <span class="doxyComputerOutput">YES</span> then classes and functions can be dynamically folded and expanded in the generated HTML source code.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_html_copy_clipboard"></a></p>
</dd>
<dt><span class="doxyComputerOutput">HTML_COPY_CLIPBOARD</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">HTML_COPY_CLIPBOARD</span> tag is set to <span class="doxyComputerOutput">YES</span> then Doxygen will show an icon in the top right corner of code and text fragments that allows the user to copy its content to the clipboard. Note this only works if supported by the browser and the web page is served via a <a href="https://www.w3.org/TR/secure-contexts/">secure context</a>, i.e. using the https: or file: protocol.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_html_project_cookie"></a></p>
</dd>
<dt><span class="doxyComputerOutput">HTML_PROJECT_COOKIE</span></dt>
<dd>
<p>Doxygen stores a couple of settings persistently in the browser (via e.g. cookies). By default these settings apply to all HTML pages generated by Doxygen across all projects. The <span class="doxyComputerOutput">HTML_PROJECT_COOKIE</span> tag can be used to store the settings under a project specific key, such that the user preferences will be stored separately.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_html_index_num_entries"></a></p>
</dd>
<dt><span class="doxyComputerOutput">HTML_INDEX_NUM_ENTRIES</span></dt>
<dd>
<p>With <span class="doxyComputerOutput">HTML_INDEX_NUM_ENTRIES</span> one can control the preferred number of entries shown in the various tree structured indices initially; the user can expand and collapse entries dynamically later on. Doxygen will expand the tree to such a level that at most the specified number of entries are visible (unless a fully collapsed tree already exceeds this amount). So setting the number of entries 1 will produce a full collapsed tree by default. 0 is a special value representing an infinite number of entries and will result in a full expanded tree by default.</p>

<p>Minimum value: <span class="doxyComputerOutput">0</span>, maximum value: <span class="doxyComputerOutput">9999</span>, default value: <span class="doxyComputerOutput">100</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_generate_docset"></a></p>
</dd>
<dt><span class="doxyComputerOutput">GENERATE_DOCSET</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">GENERATE_DOCSET</span> tag is set to <span class="doxyComputerOutput">YES</span>, additional index files will be generated that can be used as input for <a href="https://developer.apple.com/xcode/">Apple's Xcode 3 integrated development environment</a>, introduced with OSX 10.5 (Leopard). To create a documentation set, Doxygen will generate a Makefile in the HTML output directory. Running <span class="doxyComputerOutput">make</span> will produce the docset in that directory and running <span class="doxyComputerOutput">make install</span> will install the docset in <span class="doxyComputerOutput">~/Library/Developer/Shared/Documentation/DocSets</span> so that Xcode will find it at startup. See <a href="https://developer.apple.com/library/archive/featuredarticles/DoxygenXcode/_index.html">https://developer.apple.com/library/archive/featuredarticles/DoxygenXcode/_index.html</a> for more information.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_docset_feedname"></a></p>
</dd>
<dt><span class="doxyComputerOutput">DOCSET_FEEDNAME</span></dt>
<dd>
<p>This tag determines the name of the docset feed. A documentation feed provides an umbrella under which multiple documentation sets from a single provider (such as a company or product suite) can be grouped.</p>

<p>The default value is: <span class="doxyComputerOutput">Doxygen generated docs</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_docset">GENERATE_DOCSET</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_docset_feedurl"></a></p>
</dd>
<dt><span class="doxyComputerOutput">DOCSET_FEEDURL</span></dt>
<dd>
<p>This tag determines the URL of the docset feed. A documentation feed provides an umbrella under which multiple documentation sets from a single provider (such as a company or product suite) can be grouped.</p>

<p>This tag requires that the tag <a href="#cfg_generate_docset">GENERATE_DOCSET</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_docset_bundle_id"></a></p>
</dd>
<dt><span class="doxyComputerOutput">DOCSET_BUNDLE_ID</span></dt>
<dd>
<p>This tag specifies a string that should uniquely identify the documentation set bundle. This should be a reverse domain-name style string, e.g. <span class="doxyComputerOutput">com.mycompany.MyDocSet</span>. Doxygen will append <span class="doxyComputerOutput">.docset</span> to the name.</p>

<p>The default value is: <span class="doxyComputerOutput">org.doxygen.Project</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_docset">GENERATE_DOCSET</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_docset_publisher_id"></a></p>
</dd>
<dt><span class="doxyComputerOutput">DOCSET_PUBLISHER_ID</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">DOCSET_PUBLISHER_ID</span> tag specifies a string that should uniquely identify the documentation publisher. This should be a reverse domain-name style string, e.g. <span class="doxyComputerOutput">com.mycompany.MyDocSet.documentation</span>.</p>

<p>The default value is: <span class="doxyComputerOutput">org.doxygen.Publisher</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_docset">GENERATE_DOCSET</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_docset_publisher_name"></a></p>
</dd>
<dt><span class="doxyComputerOutput">DOCSET_PUBLISHER_NAME</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">DOCSET_PUBLISHER_NAME</span> tag identifies the documentation publisher.</p>

<p>The default value is: <span class="doxyComputerOutput">Publisher</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_docset">GENERATE_DOCSET</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_generate_htmlhelp"></a></p>
</dd>
<dt><span class="doxyComputerOutput">GENERATE_HTMLHELP</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">GENERATE_HTMLHELP</span> tag is set to <span class="doxyComputerOutput">YES</span> then Doxygen generates three additional HTML index files: <span class="doxyComputerOutput">index.hhp</span>, <span class="doxyComputerOutput">index.hhc</span>, and <span class="doxyComputerOutput">index.hhk</span>. The <span class="doxyComputerOutput">index.hhp</span> is a project file that can be read by Microsoft's HTML Help Workshop on Windows. In the beginning of 2021 Microsoft took the original page, with a.o. the download links, offline (the HTML help workshop was already many years in maintenance mode). You can download the HTML help workshop from the web archives at <a href="http://web.archive.org/web/20160201063255/http://download.microsoft.com/download/0/A/9/0A939EF6-E31C-430F-A3DF-DFAE7960D564/htmlhelp.exe">Installation executable</a>. 
<br/>
 The HTML Help Workshop contains a compiler that can convert all HTML output generated by Doxygen into a single compiled HTML file (<span class="doxyComputerOutput">.chm</span>). Compiled HTML files are now used as the Windows 98 help format, and will replace the old Windows help format (<span class="doxyComputerOutput">.hlp</span>) on all Windows platforms in the future. Compressed HTML files also contain an index, a table of contents, and you can search for words in the documentation. The HTML workshop also contains a viewer for compressed HTML files.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_chm_file"></a></p>
</dd>
<dt><span class="doxyComputerOutput">CHM_FILE</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">CHM_FILE</span> tag can be used to specify the file name of the resulting <span class="doxyComputerOutput">.chm</span> file. You can add a path in front of the file if the result should not be written to the html output directory.</p>

<p>This tag requires that the tag <a href="#cfg_generate_htmlhelp">GENERATE_HTMLHELP</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_hhc_location"></a></p>
</dd>
<dt><span class="doxyComputerOutput">HHC_LOCATION</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">HHC_LOCATION</span> tag can be used to specify the location (absolute path including file name) of the HTML help compiler (<span class="doxyComputerOutput">hhc.exe</span>). If non-empty, Doxygen will try to run the HTML help compiler on the generated <span class="doxyComputerOutput">index.hhp</span>.</p>

<p>The file has to be specified with full path.</p>

<p>This tag requires that the tag <a href="#cfg_generate_htmlhelp">GENERATE_HTMLHELP</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_generate_chi"></a></p>
</dd>
<dt><span class="doxyComputerOutput">GENERATE_CHI</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">GENERATE_CHI</span> flag controls if a separate <span class="doxyComputerOutput">.chi</span> index file is generated (<span class="doxyComputerOutput">YES</span>) or that it should be included in the main <span class="doxyComputerOutput">.chm</span> file (<span class="doxyComputerOutput">NO</span>).</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_htmlhelp">GENERATE_HTMLHELP</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_chm_index_encoding"></a></p>
</dd>
<dt><span class="doxyComputerOutput">CHM_INDEX_ENCODING</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">CHM_INDEX_ENCODING</span> is used to encode HtmlHelp index (<span class="doxyComputerOutput">hhk</span>), content (<span class="doxyComputerOutput">hhc</span>) and project file content.</p>

<p>This tag requires that the tag <a href="#cfg_generate_htmlhelp">GENERATE_HTMLHELP</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_binary_toc"></a></p>
</dd>
<dt><span class="doxyComputerOutput">BINARY_TOC</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">BINARY_TOC</span> flag controls whether a binary table of contents is generated (<span class="doxyComputerOutput">YES</span>) or a normal table of contents (<span class="doxyComputerOutput">NO</span>) in the <span class="doxyComputerOutput">.chm</span> file. Furthermore it enables the <span class="doxyComputerOutput">Previous</span> and <span class="doxyComputerOutput">Next</span> buttons.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_htmlhelp">GENERATE_HTMLHELP</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_toc_expand"></a></p>
</dd>
<dt><span class="doxyComputerOutput">TOC_EXPAND</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">TOC_EXPAND</span> flag can be set to <span class="doxyComputerOutput">YES</span> to add extra items for group members to the table of contents of the HTML help documentation and to the tree view.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_htmlhelp">GENERATE_HTMLHELP</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_sitemap_url"></a></p>
</dd>
<dt><span class="doxyComputerOutput">SITEMAP_URL</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">SITEMAP_URL</span> tag is used to specify the full URL of the place where the generated documentation will be placed on the server by the user during the deployment of the documentation. The generated sitemap is called <span class="doxyComputerOutput">sitemap.xml</span> and placed on the directory specified by <a href="#cfg_html_output">HTML_OUTPUT</a>. In case no <span class="doxyComputerOutput">SITEMAP_URL</span> is specified no sitemap is generated. For information about the sitemap protocol see <a href="https://www.sitemaps.org">https://www.sitemaps.org</a></p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_generate_qhp"></a></p>
</dd>
<dt><span class="doxyComputerOutput">GENERATE_QHP</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">GENERATE_QHP</span> tag is set to <span class="doxyComputerOutput">YES</span> and both <a href="#cfg_qhp_namespace">QHP_NAMESPACE</a> and <a href="#cfg_qhp_virtual_folder">QHP_VIRTUAL_FOLDER</a> are set, an additional index file will be generated that can be used as input for Qt's qhelpgenerator to generate a Qt Compressed Help (<span class="doxyComputerOutput">.qch</span>) of the generated HTML documentation.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_qch_file"></a></p>
</dd>
<dt><span class="doxyComputerOutput">QCH_FILE</span></dt>
<dd>
<p>If the <a href="#cfg_qhg_location">QHG_LOCATION</a> tag is specified, the <span class="doxyComputerOutput">QCH_FILE</span> tag can be used to specify the file name of the resulting <span class="doxyComputerOutput">.qch</span> file. The path specified is relative to the HTML output folder.</p>

<p>This tag requires that the tag <a href="#cfg_generate_qhp">GENERATE_QHP</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_qhp_namespace"></a></p>
</dd>
<dt><span class="doxyComputerOutput">QHP_NAMESPACE</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">QHP_NAMESPACE</span> tag specifies the namespace to use when generating Qt Help Project output. For more information please see <a href="https://doc.qt.io/archives/qt-4.8/qthelpproject.html#namespace">Qt Help Project / Namespace</a>.</p>

<p>The default value is: <span class="doxyComputerOutput">org.doxygen.Project</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_qhp">GENERATE_QHP</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_qhp_virtual_folder"></a></p>
</dd>
<dt><span class="doxyComputerOutput">QHP_VIRTUAL_FOLDER</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">QHP_VIRTUAL_FOLDER</span> tag specifies the namespace to use when generating Qt Help Project output. For more information please see <a href="https://doc.qt.io/archives/qt-4.8/qthelpproject.html#virtual-folders">Qt Help Project / Virtual Folders</a>.</p>

<p>The default value is: <span class="doxyComputerOutput">doc</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_qhp">GENERATE_QHP</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_qhp_cust_filter_name"></a></p>
</dd>
<dt><span class="doxyComputerOutput">QHP_CUST_FILTER_NAME</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">QHP_CUST_FILTER_NAME</span> tag is set, it specifies the name of a custom filter to add. For more information please see <a href="https://doc.qt.io/archives/qt-4.8/qthelpproject.html#custom-filters">Qt Help Project / Custom Filters</a>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_qhp">GENERATE_QHP</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_qhp_cust_filter_attrs"></a></p>
</dd>
<dt><span class="doxyComputerOutput">QHP_CUST_FILTER_ATTRS</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">QHP_CUST_FILTER_ATTRS</span> tag specifies the list of the attributes of the custom filter to add. For more information please see <a href="https://doc.qt.io/archives/qt-4.8/qthelpproject.html#custom-filters">Qt Help Project / Custom Filters</a>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_qhp">GENERATE_QHP</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_qhp_sect_filter_attrs"></a></p>
</dd>
<dt><span class="doxyComputerOutput">QHP_SECT_FILTER_ATTRS</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">QHP_SECT_FILTER_ATTRS</span> tag specifies the list of the attributes this project's filter section matches. <a href="https://doc.qt.io/archives/qt-4.8/qthelpproject.html#filter-attributes">Qt Help Project / Filter Attributes</a>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_qhp">GENERATE_QHP</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_qhg_location"></a></p>
</dd>
<dt><span class="doxyComputerOutput">QHG_LOCATION</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">QHG_LOCATION</span> tag can be used to specify the location (absolute path including file name) of Qt's qhelpgenerator. If non-empty Doxygen will try to run qhelpgenerator on the generated <span class="doxyComputerOutput">.qhp</span> file.</p>

<p>This tag requires that the tag <a href="#cfg_generate_qhp">GENERATE_QHP</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_generate_eclipsehelp"></a></p>
</dd>
<dt><span class="doxyComputerOutput">GENERATE_ECLIPSEHELP</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">GENERATE_ECLIPSEHELP</span> tag is set to <span class="doxyComputerOutput">YES</span>, additional index files will be generated, together with the HTML files, they form an <span class="doxyComputerOutput">Eclipse</span> help plugin.</p>

<p>To install this plugin and make it available under the help contents menu in <span class="doxyComputerOutput">Eclipse</span>, the contents of the directory containing the HTML and XML files needs to be copied into the plugins directory of eclipse. The name of the directory within the plugins directory should be the same as the <a href="#cfg_eclipse_doc_id">ECLIPSE_DOC_ID</a> value.</p>

<p>After copying <span class="doxyComputerOutput">Eclipse</span> needs to be restarted before the help appears.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_eclipse_doc_id"></a></p>
</dd>
<dt><span class="doxyComputerOutput">ECLIPSE_DOC_ID</span></dt>
<dd>
<p>A unique identifier for the <span class="doxyComputerOutput">Eclipse</span> help plugin. When installing the plugin the directory name containing the HTML and XML files should also have this name. Each documentation set should have its own identifier.</p>

<p>The default value is: <span class="doxyComputerOutput">org.doxygen.Project</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_eclipsehelp">GENERATE_ECLIPSEHELP</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_disable_index"></a></p>
</dd>
<dt><span class="doxyComputerOutput">DISABLE_INDEX</span></dt>
<dd>
<p>If you want full control over the layout of the generated HTML pages it might be necessary to disable the index and replace it with your own. The <span class="doxyComputerOutput">DISABLE_INDEX</span> tag can be used to turn on/off the condensed index (tabs) at top of each HTML page. A value of <span class="doxyComputerOutput">NO</span> enables the index and the value <span class="doxyComputerOutput">YES</span> disables it. Since the tabs in the index contain the same information as the navigation tree, you can set this option to <span class="doxyComputerOutput">YES</span> if you also set <a href="#cfg_generate_treeview">GENERATE_TREEVIEW</a> to <span class="doxyComputerOutput">YES</span>.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_generate_treeview"></a></p>
</dd>
<dt><span class="doxyComputerOutput">GENERATE_TREEVIEW</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">GENERATE_TREEVIEW</span> tag is used to specify whether a tree-like index structure should be generated to display hierarchical information. If the tag value is set to <span class="doxyComputerOutput">YES</span>, a side panel will be generated containing a tree-like index structure (just like the one that is generated for HTML Help). For this to work a browser that supports JavaScript, DHTML, CSS and frames is required (i.e. any modern browser). Windows users are probably better off using the HTML help feature.</p>

<p>Via custom style sheets (see <a href="#cfg_html_extra_stylesheet">HTML_EXTRA_STYLESHEET</a>) one can further fine tune the look of the index (see <a href="/web-doxygen/docs/pages/doxygen-usage/#doxygen_finetune">Fine-tuning the output</a>). As an example, the default style sheet generated by Doxygen has an example that shows how to put an image at the root of the tree instead of the <a href="#cfg_project_name">PROJECT_NAME</a>.</p>

<p>Since the tree basically has more details information than the tab index, you could consider setting <a href="#cfg_disable_index">DISABLE_INDEX</a> to <span class="doxyComputerOutput">YES</span> when enabling this option.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_page_outline_panel"></a></p>
</dd>
<dt><span class="doxyComputerOutput">PAGE_OUTLINE_PANEL</span></dt>
<dd>
<p>When <a href="#cfg_generate_treeview">GENERATE_TREEVIEW</a> is set to <span class="doxyComputerOutput">YES</span>, the <span class="doxyComputerOutput">PAGE_OUTLINE_PANEL</span> option determines if an additional navigation panel is shown at the right hand side of the screen, displaying an outline of the contents of the main page, similar to e.g. <a href="https://developer.android.com/reference">https://developer.android.com/reference</a></p>

<p>If <a href="#cfg_generate_treeview">GENERATE_TREEVIEW</a> is set to <span class="doxyComputerOutput">NO</span>, this option has no effect.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_full_sidebar"></a></p>
</dd>
<dt><span class="doxyComputerOutput">FULL_SIDEBAR</span></dt>
<dd>
<p>When <a href="#cfg_generate_treeview">GENERATE_TREEVIEW</a> is set to <span class="doxyComputerOutput">YES</span>, the <span class="doxyComputerOutput">FULL_SIDEBAR</span> option determines if the side bar is limited to only the treeview area (value <span class="doxyComputerOutput">NO</span>) or if it should extend to the full height of the window (value <span class="doxyComputerOutput">YES</span>). Setting this to <span class="doxyComputerOutput">YES</span> gives a layout similar to e.g. <a href="https://docs.readthedocs.io">https://docs.readthedocs.io</a> with more room for contents, but less room for the project logo, title, and description.</p>

<p>If <a href="#cfg_generate_treeview">GENERATE_TREEVIEW</a> is set to <span class="doxyComputerOutput">NO</span>, this option has no effect.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_enum_values_per_line"></a></p>
</dd>
<dt><span class="doxyComputerOutput">ENUM_VALUES_PER_LINE</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">ENUM_VALUES_PER_LINE</span> tag can be used to set the number of enum values that Doxygen will group on one line in the generated HTML documentation. 
<br/>
Note that a value of 0 will completely suppress the enum values from appearing in the overview section.</p>

<p>Minimum value: <span class="doxyComputerOutput">0</span>, maximum value: <span class="doxyComputerOutput">20</span>, default value: <span class="doxyComputerOutput">4</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_show_enum_values"></a></p>
</dd>
<dt><span class="doxyComputerOutput">SHOW_ENUM_VALUES</span></dt>
<dd>
<p>When the <span class="doxyComputerOutput">SHOW_ENUM_VALUES</span> tag is set doxygen will show the specified enumeration values besides the enumeration mnemonics.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_treeview_width"></a></p>
</dd>
<dt><span class="doxyComputerOutput">TREEVIEW_WIDTH</span></dt>
<dd>
<p>If the treeview is enabled (see <a href="#cfg_generate_treeview">GENERATE_TREEVIEW</a>) then this tag can be used to set the initial width (in pixels) of the frame in which the tree is shown.</p>

<p>Minimum value: <span class="doxyComputerOutput">0</span>, maximum value: <span class="doxyComputerOutput">1500</span>, default value: <span class="doxyComputerOutput">250</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_ext_links_in_window"></a></p>
</dd>
<dt><span class="doxyComputerOutput">EXT_LINKS_IN_WINDOW</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">EXT_LINKS_IN_WINDOW</span> option is set to <span class="doxyComputerOutput">YES</span>, Doxygen will open links to external symbols imported via tag files in a separate window.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_obfuscate_emails"></a></p>
</dd>
<dt><span class="doxyComputerOutput">OBFUSCATE_EMAILS</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">OBFUSCATE_EMAILS</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will obfuscate email addresses.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_html_formula_format"></a></p>
</dd>
<dt><span class="doxyComputerOutput">HTML_FORMULA_FORMAT</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">HTML_FORMULA_FORMAT</span> option is set to <span class="doxyComputerOutput">svg</span>, Doxygen will use the pdf2svg tool (see <a href="https://github.com/dawbarton/pdf2svg">https://github.com/dawbarton/pdf2svg</a>) or inkscape (see <a href="https://inkscape.org">https://inkscape.org</a>) to generate formulas as SVG images instead of PNGs for the HTML output. These images will generally look nicer at scaled resolutions.</p>

<p>Possible values are: <span class="doxyComputerOutput">png</span> (the default) and <span class="doxyComputerOutput">svg</span> (looks nicer but requires the pdf2svg or inkscape tool).</p>

<p>The default value is: <span class="doxyComputerOutput">png</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_formula_fontsize"></a></p>
</dd>
<dt><span class="doxyComputerOutput">FORMULA_FONTSIZE</span></dt>
<dd>
<p>Use this tag to change the font size of <code>$\mbox{\LaTeX}$</code> formulas included as images in the HTML documentation. When you change the font size after a successful Doxygen run you need to manually remove any <span class="doxyComputerOutput">form_*.png</span> images from the HTML output directory to force them to be regenerated.</p>

<p>Minimum value: <span class="doxyComputerOutput">8</span>, maximum value: <span class="doxyComputerOutput">50</span>, default value: <span class="doxyComputerOutput">10</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_formula_macrofile"></a></p>
</dd>
<dt><span class="doxyComputerOutput">FORMULA_MACROFILE</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">FORMULA_MACROFILE</span> can contain <code>$\mbox{\LaTeX}$</code> <span class="doxyComputerOutput">\newcommand</span> and <span class="doxyComputerOutput">\renewcommand</span> commands to create new <code>$\mbox{\LaTeX}$</code> commands to be used in formulas as building blocks. See the section <a href="/web-doxygen/docs/pages/formulas">Including formulas</a> for details.</p>

<p><a id="cfg_use_mathjax"></a></p>
</dd>
<dt><span class="doxyComputerOutput">USE_MATHJAX</span></dt>
<dd>
<p>Enable the <span class="doxyComputerOutput">USE_MATHJAX</span> option to render <code>$\mbox{\LaTeX}$</code> formulas using MathJax (see <a href="https://www.mathjax.org">https://www.mathjax.org</a>) which uses client side JavaScript for the rendering instead of using pre-rendered bitmaps. Use this if you do not have <code>$\mbox{\LaTeX}$</code> installed or if you want to formulas look prettier in the HTML output. When enabled you may also need to install MathJax separately and configure the path to it using the <a href="#cfg_mathjax_relpath">MATHJAX_RELPATH</a> option.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_mathjax_version"></a></p>
</dd>
<dt><span class="doxyComputerOutput">MATHJAX_VERSION</span></dt>
<dd>
<p>With <span class="doxyComputerOutput">MATHJAX_VERSION</span> it is possible to specify the MathJax version to be used. Note that the different versions of MathJax have different requirements with regards to the different settings, so it is possible that also other MathJax settings have to be changed when switching between the different MathJax versions.</p>

<p>Possible values are: <span class="doxyComputerOutput">MathJax_2</span> and <span class="doxyComputerOutput">MathJax_3</span>.</p>

<p>The default value is: <span class="doxyComputerOutput">MathJax_2</span>.</p>

<p>This tag requires that the tag <a href="#cfg_use_mathjax">USE_MATHJAX</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_mathjax_format"></a></p>
</dd>
<dt><span class="doxyComputerOutput">MATHJAX_FORMAT</span></dt>
<dd>
<p>When MathJax is enabled you can set the default output format to be used for the MathJax output. For more details about the output format see <a href="http://docs.mathjax.org/en/v2.7-latest/output.html">MathJax version 2</a> and <a href="http://docs.mathjax.org/en/latest/web/components/output.html">MathJax version 3</a>.</p>

<p>Possible values are: <span class="doxyComputerOutput">HTML-CSS</span> (which is slower, but has the best compatibility. This is the name for Mathjax version 2, for MathJax version 3 this will be translated into <span class="doxyComputerOutput">chtml</span>), <span class="doxyComputerOutput">NativeMML</span> (i.e. MathML. Only supported for MathJax 2. For MathJax version 3 <span class="doxyComputerOutput">chtml</span> will be used instead.), <span class="doxyComputerOutput">chtml</span> (This is the name for Mathjax version 3, for MathJax version 2 this will be translated into <span class="doxyComputerOutput">HTML-CSS</span>) and <span class="doxyComputerOutput">SVG</span>.</p>

<p>The default value is: <span class="doxyComputerOutput">HTML-CSS</span>.</p>

<p>This tag requires that the tag <a href="#cfg_use_mathjax">USE_MATHJAX</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_mathjax_relpath"></a></p>
</dd>
<dt><span class="doxyComputerOutput">MATHJAX_RELPATH</span></dt>
<dd>
<p>When MathJax is enabled you need to specify the location relative to the HTML output directory using the <span class="doxyComputerOutput">MATHJAX_RELPATH</span> option. The destination directory should contain the <span class="doxyComputerOutput">MathJax.js</span> script. For instance, if the <span class="doxyComputerOutput">mathjax</span> directory is located at the same level as the HTML output directory, then <span class="doxyComputerOutput">MATHJAX_RELPATH</span> should be <span class="doxyComputerOutput">../mathjax</span>. The default value points to the MathJax Content Delivery Network so you can quickly see the result without installing MathJax. However, it is strongly recommended to install a local copy of MathJax from <a href="https://www.mathjax.org">https://www.mathjax.org</a> before deployment.</p>

<p>The default value is:</p>


<ul class="doxyList ">
<li>in case of MathJax version 2: <a href="https://cdn.jsdelivr.net/npm/mathjax@2">https://cdn.jsdelivr.net/npm/mathjax@2</a></li>
<li>in case of MathJax version 3: <a href="https://cdn.jsdelivr.net/npm/mathjax@3">https://cdn.jsdelivr.net/npm/mathjax@3</a></li>
</ul>
<p>This tag requires that the tag <a href="#cfg_use_mathjax">USE_MATHJAX</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_mathjax_extensions"></a></p>
</dd>
<dt><span class="doxyComputerOutput">MATHJAX_EXTENSIONS</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">MATHJAX_EXTENSIONS</span> tag can be used to specify one or more MathJax extension names that should be enabled during MathJax rendering. For example for MathJax version 2 (see <a href="https://docs.mathjax.org/en/v2.7-latest/tex.html#tex-and-latex-extensions">https://docs.mathjax.org/en/v2.7-latest/tex.html#tex-and-latex-extensions</a>):</p>



<pre><code>MATHJAX_EXTENSIONS     = TeX/AMSmath TeX/AMSsymbols
</code></pre>


<p>For example for MathJax version 3 (see <a href="http://docs.mathjax.org/en/latest/input/tex/extensions/index.html">http://docs.mathjax.org/en/latest/input/tex/extensions/index.html</a>):</p>



<pre><code>MATHJAX_EXTENSIONS     = ams
</code></pre>

<p>This tag requires that the tag <a href="#cfg_use_mathjax">USE_MATHJAX</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_mathjax_codefile"></a></p>
</dd>
<dt><span class="doxyComputerOutput">MATHJAX_CODEFILE</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">MATHJAX_CODEFILE</span> tag can be used to specify a file with JavaScript pieces of code that will be used on startup of the MathJax code. See <a href="http://docs.mathjax.org/en/v2.7-latest/output.html">the MathJax site</a> for more details. As an example to disable the "Math Renderer" menu item in the "Math
 Settings" menu of MathJax:</p>



<pre><code>MATHJAX_CODEFILE = disableRenderer.js
</code></pre>


<p>with in the file <span class="doxyComputerOutput">disableRenderer.js</span>:</p>



<pre><code>  MathJax.Hub.Config({
   menuSettings: {
    showRenderer: false,
   }
  });
</code></pre>

<p>This tag requires that the tag <a href="#cfg_use_mathjax">USE_MATHJAX</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_searchengine"></a></p>
</dd>
<dt><span class="doxyComputerOutput">SEARCHENGINE</span></dt>
<dd>
<p>When the <span class="doxyComputerOutput">SEARCHENGINE</span> tag is enabled Doxygen will generate a search box for the HTML output. The underlying search engine uses JavaScript and DHTML and should work on any modern browser. Note that when using HTML help (<a href="#cfg_generate_htmlhelp">GENERATE_HTMLHELP</a>), Qt help (<a href="#cfg_generate_qhp">GENERATE_QHP</a>), or docsets (<a href="#cfg_generate_docset">GENERATE_DOCSET</a>) there is already a search function so this one should typically be disabled. For large projects the JavaScript based search engine can be slow, then enabling <a href="#cfg_server_based_search">SERVER_BASED_SEARCH</a> may provide a better solution.</p>

<p>It is possible to search using the keyboard; to jump to the search box use <span class="doxyComputerOutput">&lt;access key&gt; + S</span> (what the <span class="doxyComputerOutput">&lt;access key&gt;</span> is depends on the OS and browser, but it is typically <span class="doxyComputerOutput">&lt;CTRL&gt;</span>, <span class="doxyComputerOutput">&lt;ALT&gt;</span>/<span class="doxyComputerOutput">&lt;option&gt;</span>, or both). Inside the search box use the <span class="doxyComputerOutput">&lt;cursor down key&gt;</span> to jump into the search results window, the results can be navigated using the <span class="doxyComputerOutput">&lt;cursor keys&gt;</span>. Press <span class="doxyComputerOutput">&lt;Enter&gt;</span> to select an item or <span class="doxyComputerOutput">&lt;escape&gt;</span> to cancel the search. The filter options can be selected when the cursor is inside the search box by pressing <span class="doxyComputerOutput">&lt;Shift&gt;+&lt;cursor down&gt;</span>. Also here use the <span class="doxyComputerOutput">&lt;cursor keys&gt;</span> to select a filter and <span class="doxyComputerOutput">&lt;Enter&gt;</span> or <span class="doxyComputerOutput">&lt;escape&gt;</span> to activate or cancel the filter option.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_server_based_search"></a></p>
</dd>
<dt><span class="doxyComputerOutput">SERVER_BASED_SEARCH</span></dt>
<dd>
<p>When the <span class="doxyComputerOutput">SERVER_BASED_SEARCH</span> tag is enabled the search engine will be implemented using a web server instead of a web client using JavaScript.</p>

<p>There are two flavors of web server based searching depending on the <a href="#cfg_external_search">EXTERNAL_SEARCH</a> setting. When disabled, Doxygen will generate a PHP script for searching and an index file used by the script. When <a href="#cfg_external_search">EXTERNAL_SEARCH</a> is enabled the indexing and searching needs to be provided by external tools. See the section <a href="/web-doxygen/docs/pages/extsearch">External Indexing and Searching</a> for details.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_searchengine">SEARCHENGINE</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_external_search"></a></p>
</dd>
<dt><span class="doxyComputerOutput">EXTERNAL_SEARCH</span></dt>
<dd>
<p>When <span class="doxyComputerOutput">EXTERNAL_SEARCH</span> tag is enabled Doxygen will no longer generate the PHP script for searching. Instead the search results are written to an XML file which needs to be processed by an external indexer. Doxygen will invoke an external search engine pointed to by the <a href="#cfg_searchengine_url">SEARCHENGINE_URL</a> option to obtain the search results. 
<br/>
Doxygen ships with an example indexer (<span class="doxyComputerOutput">doxyindexer</span>) and search engine (<span class="doxyComputerOutput">doxysearch.cgi</span>) which are based on the open source search engine library <a href="https://xapian.org/">Xapian</a>. 
<br/>
See the section <a href="/web-doxygen/docs/pages/extsearch">External Indexing and Searching</a> for details.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_searchengine">SEARCHENGINE</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_searchengine_url"></a></p>
</dd>
<dt><span class="doxyComputerOutput">SEARCHENGINE_URL</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">SEARCHENGINE_URL</span> should point to a search engine hosted by a web server which will return the search results when <a href="#cfg_external_search">EXTERNAL_SEARCH</a> is enabled. 
<br/>
Doxygen ships with an example indexer (<span class="doxyComputerOutput">doxyindexer</span>) and search engine (<span class="doxyComputerOutput">doxysearch.cgi</span>) which are based on the open source search engine library <a href="https://xapian.org/">Xapian</a>. See the section <a href="/web-doxygen/docs/pages/extsearch">External Indexing and Searching</a> for details.</p>

<p>This tag requires that the tag <a href="#cfg_searchengine">SEARCHENGINE</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_searchdata_file"></a></p>
</dd>
<dt><span class="doxyComputerOutput">SEARCHDATA_FILE</span></dt>
<dd>
<p>When <a href="#cfg_server_based_search">SERVER_BASED_SEARCH</a> and <a href="#cfg_external_search">EXTERNAL_SEARCH</a> are both enabled the unindexed search data is written to a file for indexing by an external tool. With the <span class="doxyComputerOutput">SEARCHDATA_FILE</span> tag the name of this file can be specified.</p>

<p>The default file is: <span class="doxyComputerOutput">searchdata.xml</span>.</p>

<p>This tag requires that the tag <a href="#cfg_searchengine">SEARCHENGINE</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_external_search_id"></a></p>
</dd>
<dt><span class="doxyComputerOutput">EXTERNAL_SEARCH_ID</span></dt>
<dd>
<p>When <a href="#cfg_server_based_search">SERVER_BASED_SEARCH</a> and <a href="#cfg_external_search">EXTERNAL_SEARCH</a> are both enabled the <span class="doxyComputerOutput">EXTERNAL_SEARCH_ID</span> tag can be used as an identifier for the project. This is useful in combination with <a href="#cfg_extra_search_mappings">EXTRA_SEARCH_MAPPINGS</a> to search through multiple projects and redirect the results back to the right project.</p>

<p>This tag requires that the tag <a href="#cfg_searchengine">SEARCHENGINE</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_extra_search_mappings"></a></p>
</dd>
<dt><span class="doxyComputerOutput">EXTRA_SEARCH_MAPPINGS</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">EXTRA_SEARCH_MAPPINGS</span> tag can be used to enable searching through Doxygen projects other than the one defined by this configuration file, but that are all added to the same external search index. Each project needs to have a unique id set via <a href="#cfg_external_search_id">EXTERNAL_SEARCH_ID</a>. The search mapping then maps the id of to a relative location where the documentation can be found.</p>

<p>The format is:</p>



<pre><code>EXTRA_SEARCH_MAPPINGS = tagname1=loc1 tagname2=loc2 ...
</code></pre>

<p>This tag requires that the tag <a href="#cfg_searchengine">SEARCHENGINE</a> is set to <span class="doxyComputerOutput">YES</span>.</p>
</dd>
</dl>

## Configuration options related to the LaTeX output {#config_latex}


<p><a id="cfg_generate_latex"></a></p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">GENERATE_LATEX</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">GENERATE_LATEX</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will generate <code>$\mbox{\LaTeX}$</code> output.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_latex_output"></a></p>
</dd>
<dt><span class="doxyComputerOutput">LATEX_OUTPUT</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">LATEX_OUTPUT</span> tag is used to specify where the <code>$\mbox{\LaTeX}$</code> docs will be put. If a relative path is entered the value of <a href="#cfg_output_directory">OUTPUT_DIRECTORY</a> will be put in front of it.</p>

<p>The default directory is: <span class="doxyComputerOutput">latex</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_latex_cmd_name"></a></p>
</dd>
<dt><span class="doxyComputerOutput">LATEX_CMD_NAME</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">LATEX_CMD_NAME</span> tag can be used to specify the <code>$\mbox{\LaTeX}$</code> command name to be invoked. 
<br/>
Note that when not enabling <a href="#cfg_use_pdflatex">USE_PDFLATEX</a> the default is <span class="doxyComputerOutput">latex</span> when enabling <a href="#cfg_use_pdflatex">USE_PDFLATEX</a> the default is <span class="doxyComputerOutput">pdflatex</span> and when in the later case <span class="doxyComputerOutput">latex</span> is chosen this is overwritten by <span class="doxyComputerOutput">pdflatex</span>. For specific output languages the default can have been set differently, this depends on the implementation of the output language.</p>

<p>This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_makeindex_cmd_name"></a></p>
</dd>
<dt><span class="doxyComputerOutput">MAKEINDEX_CMD_NAME</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">MAKEINDEX_CMD_NAME</span> tag can be used to specify the command name to generate index for <code>$\mbox{\LaTeX}$</code>.</p>


:::info
<p>This tag is used in the <span class="doxyComputerOutput">Makefile</span> / <span class="doxyComputerOutput">make.bat</span>.</p>
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#cfg_latex_makeindex_cmd">LATEX_MAKEINDEX_CMD</a> for the part in the generated output file (<span class="doxyComputerOutput">.tex</span>).</p></dd>
</dl>


<p>The default file is: <span class="doxyComputerOutput">makeindex</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_latex_makeindex_cmd"></a></p>
</dd>
<dt><span class="doxyComputerOutput">LATEX_MAKEINDEX_CMD</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">LATEX_MAKEINDEX_CMD</span> tag can be used to specify the command name to generate index for <code>$\mbox{\LaTeX}$</code>. In case there is no backslash (<span class="doxyComputerOutput">\</span>) as first character it will be automatically added in the <code>$\mbox{\LaTeX}$</code> code.</p>


:::info
<p>This tag is used in the generated output file (<span class="doxyComputerOutput">.tex</span>).</p>
:::


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#cfg_makeindex_cmd_name">MAKEINDEX_CMD_NAME</a> for the part in the <span class="doxyComputerOutput">Makefile</span> / <span class="doxyComputerOutput">make.bat</span>.</p></dd>
</dl>


<p>The default value is: <span class="doxyComputerOutput">makeindex</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_compact_latex"></a></p>
</dd>
<dt><span class="doxyComputerOutput">COMPACT_LATEX</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">COMPACT_LATEX</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen generates more compact <code>$\mbox{\LaTeX}$</code> documents. This may be useful for small projects and may help to save some trees in general.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_paper_type"></a></p>
</dd>
<dt><span class="doxyComputerOutput">PAPER_TYPE</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">PAPER_TYPE</span> tag can be used to set the paper type that is used by the printer.</p>

<p>Possible values are: <span class="doxyComputerOutput">a4</span> (210 x 297 mm), <span class="doxyComputerOutput">letter</span> (8.5 x 11 inches), <span class="doxyComputerOutput">legal</span> (8.5 x 14 inches) and <span class="doxyComputerOutput">executive</span> (7.25 x 10.5 inches).</p>

<p>The default value is: <span class="doxyComputerOutput">a4</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_extra_packages"></a></p>
</dd>
<dt><span class="doxyComputerOutput">EXTRA_PACKAGES</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">EXTRA_PACKAGES</span> tag can be used to specify one or more <code>$\mbox{\LaTeX}$</code> package names that should be included in the <code>$\mbox{\LaTeX}$</code> output. The package can be specified just by its name or with the correct syntax as to be used with the <code>$\mbox{\LaTeX}$</code> <span class="doxyComputerOutput">\usepackage</span> command.</p>

<p>To get the <span class="doxyComputerOutput">times</span> font for instance you can specify :</p>



<pre><code>  EXTRA_PACKAGES=times
or
  EXTRA_PACKAGES={times}
</code></pre>


<p>To use the option <span class="doxyComputerOutput">intlimits</span> with the <span class="doxyComputerOutput">amsmath</span> package you can specify:</p>



<pre><code>   EXTRA_PACKAGES=[intlimits]{amsmath}
</code></pre>


<p>If left blank no extra packages will be included.</p>

<p>This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_latex_header"></a></p>
</dd>
<dt><span class="doxyComputerOutput">LATEX_HEADER</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">LATEX_HEADER</span> tag can be used to specify a user-defined <code>$\mbox{\LaTeX}$</code> header for the generated <code>$\mbox{\LaTeX}$</code> document. The header should contain everything until the first chapter. If it is left blank Doxygen will generate a standard header.</p>

<p>It is highly recommended to start with a default header using</p>



<pre><code>doxygen -w latex new_header.tex new_footer.tex new_stylesheet.sty
</code></pre>


<p>and then modify the file <span class="doxyComputerOutput">new_header.tex</span>.</p>

<p>See also section <a href="/web-doxygen/docs/pages/doxygen-usage">Doxygen usage</a> for information on how to generate the default header that Doxygen normally uses.</p>

<p><br/>
Note: Only use a user-defined header if you know what you are doing!</p>


:::info
<p>The header is subject to change so you typically have to regenerate the default header when upgrading to a newer version of Doxygen. The following commands have a special meaning inside the header (and footer):</p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">$title</span></dt>
<dd><p>will be replaced with the project name.</p></dd>
<dt><span class="doxyComputerOutput">$datetime</span></dt>
<dd><p>will be replaced with the current date and time.</p></dd>
<dt><span class="doxyComputerOutput">$date</span></dt>
<dd><p>will be replaced with the current date.</p></dd>
<dt><span class="doxyComputerOutput">$time</span></dt>
<dd><p>will be replaced with the current time.</p></dd>
<dt><span class="doxyComputerOutput">$year</span></dt>
<dd><p>will be replaces with the current year.</p></dd>
<dt><span class="doxyComputerOutput">$showdate(&lt;format&gt;)</span></dt>
<dd><p>will be replaced with the current date and time according to the format as specified by <span class="doxyComputerOutput">&lt;format&gt;</span>. The <span class="doxyComputerOutput">&lt;format&gt;</span> follows the rules as specified for the <a href="/web-doxygen/docs/pages/commands/#cmdshowdate">\showdate</a> command with the exception that no <span class="doxyComputerOutput">)</span> is allowed in the <span class="doxyComputerOutput">&lt;format&gt;</span>.</p></dd>
<dt><span class="doxyComputerOutput">$doxygenversion</span></dt>
<dd><p>will be replaced with the version of Doxygen</p></dd>
<dt><span class="doxyComputerOutput">$projectname</span></dt>
<dd><p>will be replaced with the name of the project (see <a href="#cfg_project_name">PROJECT_NAME</a>)</p></dd>
<dt><span class="doxyComputerOutput">$projectnumber</span></dt>
<dd><p>will be replaced with the project number (see <a href="#cfg_project_number">PROJECT_NUMBER</a>)</p></dd>
<dt><span class="doxyComputerOutput">$projectbrief</span></dt>
<dd><p>will be replaced with the project brief description (see <a href="#cfg_project_brief">PROJECT_BRIEF</a>)</p></dd>
<dt><span class="doxyComputerOutput">$projectlogo</span></dt>
<dd><p>will be replaced with the project logo (see <a href="#cfg_project_logo">PROJECT_LOGO</a>)</p></dd>
<dt><span class="doxyComputerOutput">$latexdocumentpre</span></dt>
<dd><p>will be replaced by an output language dependent setting e.g. embed the entire document in a special environment (for Chinese, Japanese etc.) Commonly used together with <span class="doxyComputerOutput">$latexdocumentpost</span> in the footer.</p></dd>
<dt><span class="doxyComputerOutput">$latexdocumentpost</span></dt>
<dd><p>will be replaced by an output language dependent setting e.g. embed the entire document in a special environment (for Chinese, Japanese etc.) Commonly used together with <span class="doxyComputerOutput">$latexdocumentpre</span> in the header.</p></dd>
<dt><span class="doxyComputerOutput">$generatedby</span></dt>
<dd><p>will be replaced with the output language dependent version of the text "Generated by" or when the <a href="#cfg_timestamp">TIMESTAMP</a> is set by the output language dependent version of the text "Generated on <span class="doxyComputerOutput">$datetime</span> for <span class="doxyComputerOutput">$projectname</span> by".</p></dd>
<dt><span class="doxyComputerOutput">$latexcitereference</span></dt>
<dd><p>will be replaced by the output language dependent$ version of the word "Bibliography". This setting is typically used in combination with the block name <span class="doxyComputerOutput">CITATIONS_PRESENT</span>.</p></dd>
<dt><span class="doxyComputerOutput">$latexbibstyle</span></dt>
<dd><p>will be replaced with the latex bib style to be used as set by <a href="#cfg_latex_bib_style">LATEX_BIB_STYLE</a>, in case nothing is set the bib style <span class="doxyComputerOutput">plain</span> is used. This setting is typically used in combination with the block name <span class="doxyComputerOutput">CITATIONS_PRESENT</span>.</p></dd>
<dt><span class="doxyComputerOutput">$latexbibfiles</span></dt>
<dd><p>will be replaced by the comma separated list of <span class="doxyComputerOutput">bib</span>. files as set by <a href="#cfg_cite_bib_files">CITE_BIB_FILES</a> (when necessary a missing <span class="doxyComputerOutput">.bib</span> is automatically added). This setting is typically used in combination with the block name <span class="doxyComputerOutput">CITATIONS_PRESENT</span>.</p></dd>
<dt><span class="doxyComputerOutput">$papertype</span></dt>
<dd><p>will be replaced by the paper type as set in <a href="#cfg_paper_type">PAPER_TYPE</a> and the word "paper" is directly appended to it to have a correct <code>$\mbox{\LaTeX}$</code> paper type.</p></dd>
<dt><span class="doxyComputerOutput">$langISO</span></dt>
<dd><p>will be replaced by the ISO language name.</p></dd>
<dt><span class="doxyComputerOutput">$languagesupport</span></dt>
<dd><p>will be replaced by an output language dependent setting of packages required for translating terms of the specified language.</p></dd>
<dt><span class="doxyComputerOutput">$latexfontenc</span></dt>
<dd><p>will be replaced by an output language dependent setting of the fontencoding to be used. This setting is typically used in combination with the block name <span class="doxyComputerOutput">LATEX_FONTENC</span>.</p></dd>
<dt><span class="doxyComputerOutput">$latexfont</span></dt>
<dd><p>will be replaced by an output language dependent setting of the fonts to be used.</p></dd>
<dt><span class="doxyComputerOutput">$latexemojidirectory</span></dt>
<dd><p>will be replaced by the directory as set in <a href="#cfg_latex_emoji_directory">LATEX_EMOJI_DIRECTORY</a> with the backslashes replaced by forward slashes (so usable by <code>$\mbox{\LaTeX}$</code>). In case the <a href="#cfg_latex_emoji_directory">LATEX_EMOJI_DIRECTORY</a> is empty, the current directory will be used.</p></dd>
<dt><span class="doxyComputerOutput">$makeindex</span></dt>
<dd><p>will be replaced by the command as set in <a href="#cfg_latex_makeindex_cmd">LATEX_MAKEINDEX_CMD</a>. Then the command doesn't start with a backslash, a backslash is automatically prepended. In case the setting is empty the command <span class="doxyComputerOutput">\makeindex</span> is used.</p></dd>
<dt><span class="doxyComputerOutput">$extralatexpackages</span></dt>
<dd><p>will be replaced by commands for using the packages set in <a href="#cfg_extra_packages">EXTRA_PACKAGES</a>.</p></dd>
<dt><span class="doxyComputerOutput">$extralatexstylesheet</span></dt>
<dd><p>will be replaced by commands for using the packages set in <a href="#cfg_latex_extra_stylesheet">LATEX_EXTRA_STYLESHEET</a> (when the extension is the default extension, <span class="doxyComputerOutput">.sty</span>, this extension is stripped for the package name).</p></dd>
<dt><span class="doxyComputerOutput">$latexspecialformulachars</span></dt>
<dd><p>will be replaced by the code for some special unicode characters that are commonly used (i.e. superscript minus, superscript 2 and superscript 3)</p></dd>
<dt><span class="doxyComputerOutput">$formulamacrofile</span></dt>
<dd><p>will be replaced by the name of the file as set in <a href="#cfg_formula_macrofile">FORMULA_MACROFILE</a>. This setting is typically used in combination with the block name <span class="doxyComputerOutput">FORMULA_MACROFILE</span>.</p></dd>
</dl>
:::


<p>To cope with differences in the layout of the header and footer that depend on configuration settings, the header and footer can also contain special blocks that will be copied to the output or skipped depending on the configuration. Such blocks have the following form:</p>



<pre><code> %%BEGIN BLOCKNAME
 Some context copied when condition BLOCKNAME holds
 %%END BLOCKNAME
 %%BEGIN !BLOCKNAME
 Some context copied when condition BLOCKNAME does not hold
 %%END !BLOCKNAME
</code></pre>


<p>The following block names are set based on the used settings in the configuration file:</p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">COMPACT_LATEX</span></dt>
<dd><p>Content within this block is copied to the output when the <a href="#cfg_compact_latex">COMPACT_LATEX</a> option is enabled.</p></dd>
<dt><span class="doxyComputerOutput">PDF_HYPERLINKS</span></dt>
<dd><p>Content within this block is copied to the output when the <a href="#cfg_pdf_hyperlinks">PDF_HYPERLINKS</a> option is enabled.</p></dd>
<dt><span class="doxyComputerOutput">USE_PDFLATEX</span></dt>
<dd><p>Content within this block is copied to the output when the <a href="#cfg_use_pdflatex">USE_PDFLATEX</a> option is enabled.</p></dd>
<dt><span class="doxyComputerOutput">LATEX_BATCHMODE</span></dt>
<dd><p>Content within this block is copied to the output when the <a href="#cfg_latex_batchmode">LATEX_BATCHMODE</a> option is enabled.</p></dd>
<dt><span class="doxyComputerOutput">TIMESTAMP</span></dt>
<dd><p>Content within this block is copied to the output when the <a href="#cfg_timestamp">TIMESTAMP</a> option is enabled.</p></dd>
</dl>

<p>The following block names are set based on the fact whether or not the tag has a value in the used configuration file:</p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">LATEX_FONTENC</span></dt>
<dd><p>Content within this block is copied to the output when the Doxygen latex translator function returns a value for the font encoding to be used. It is to be used in combination with the above mentioned <span class="doxyComputerOutput">$latexfontenc</span>.</p></dd>
<dt><span class="doxyComputerOutput">FORMULA_MACROFILE</span></dt>
<dd><p>Content within this block is copied to the output when the <a href="#cfg_formula_macrofile">FORMULA_MACROFILE</a> option is not empty. It is to be used in combination with the above mentioned <span class="doxyComputerOutput">$formulamacrofile</span>.</p></dd>
</dl>

<p>The following block name is set based on whether or not a feature is used in the documentation:</p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">CITATIONS_PRESENT</span></dt>
<dd><p>Content within this block is copied to the output when in the documentation citations are present and the relevant .. are present. It is to be used in combination with the above mentioned <span class="doxyComputerOutput">$latexcitereference</span>, <span class="doxyComputerOutput">$latexbibstyle</span> and <span class="doxyComputerOutput">$latexbibfiles</span>.</p></dd>
</dl>
<p>This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_latex_footer"></a></p>
</dd>
<dt><span class="doxyComputerOutput">LATEX_FOOTER</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">LATEX_FOOTER</span> tag can be used to specify a user-defined <code>$\mbox{\LaTeX}$</code> footer for the generated <code>$\mbox{\LaTeX}$</code> document. The footer should contain everything after the last chapter. If it is left blank Doxygen will generate a standard footer.</p>

<p>See <a href="#cfg_latex_header">LATEX_HEADER</a> for more information on how to generate a default footer and what special commands can be used inside the footer.</p>

<p>See also section <a href="/web-doxygen/docs/pages/doxygen-usage">Doxygen usage</a> for information on how to generate the default footer that Doxygen normally uses.</p>

<p>Note: Only use a user-defined footer if you know what you are doing!</p>

<p>This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_latex_extra_stylesheet"></a></p>
</dd>
<dt><span class="doxyComputerOutput">LATEX_EXTRA_STYLESHEET</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">LATEX_EXTRA_STYLESHEET</span> tag can be used to specify additional user-defined <code>$\mbox{\LaTeX}$</code> style sheets that are included after the standard style sheets created by Doxygen. Using this option one can overrule certain style aspects. Doxygen will copy the style sheet files to the output directory.</p>



:::info
<p>The order of the extra style sheet files is of importance (e.g. the last style sheet in the list overrules the setting of the previous ones in the list).</p>
:::


<p>This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_latex_extra_files"></a></p>
</dd>
<dt><span class="doxyComputerOutput">LATEX_EXTRA_FILES</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">LATEX_EXTRA_FILES</span> tag can be used to specify one or more extra images or other source files which should be copied to the <a href="#cfg_latex_output">LATEX_OUTPUT</a> output directory. Note that the files will be copied as-is; there are no commands or markers available.</p>

<p>This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_pdf_hyperlinks"></a></p>
</dd>
<dt><span class="doxyComputerOutput">PDF_HYPERLINKS</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">PDF_HYPERLINKS</span> tag is set to <span class="doxyComputerOutput">YES</span>, the <code>$\mbox{\LaTeX}$</code> that is generated is prepared for conversion to PDF (using <span class="doxyComputerOutput">ps2pdf</span> or <span class="doxyComputerOutput">pdflatex</span>). The PDF file will contain links (just like the HTML output) instead of page references. This makes the output suitable for online browsing using a PDF viewer.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_use_pdflatex"></a></p>
</dd>
<dt><span class="doxyComputerOutput">USE_PDFLATEX</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">USE_PDFLATEX</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will use the engine as specified with <a href="#cfg_latex_cmd_name">LATEX_CMD_NAME</a> to generate the PDF file directly from the <code>$\mbox{\LaTeX}$</code> files. Set this option to <span class="doxyComputerOutput">YES</span>, to get a higher quality PDF documentation. 
<br/>
 See also section <a href="#cfg_latex_cmd_name">LATEX_CMD_NAME</a> for selecting the engine.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_latex_batchmode"></a></p>
</dd>
<dt><span class="doxyComputerOutput">LATEX_BATCHMODE</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">LATEX_BATCHMODE</span> tag signals the behavior of <code>$\mbox{\LaTeX}$</code> in case of an error.</p>

<p>Possible values are: <span class="doxyComputerOutput">NO</span> same as ERROR_STOP, <span class="doxyComputerOutput">YES</span> same as BATCH, <span class="doxyComputerOutput">BATCH</span> In batch mode nothing is printed on the terminal, errors are scrolled as if &lt;return&gt; is hit at every error; missing files that TeX tries to input or request from keyboard input (\read on a not open input stream) cause the job to abort, <span class="doxyComputerOutput">NON_STOP</span> In nonstop mode the diagnostic message will appear on the terminal, but there is no possibility of user interaction just like in batch mode, <span class="doxyComputerOutput">SCROLL</span> In scroll mode, TeX will stop only for missing files to input or if keyboard input is necessary and <span class="doxyComputerOutput">ERROR_STOP</span> In errorstop mode, TeX will stop at each error, asking for user intervention.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_latex_hide_indices"></a></p>
</dd>
<dt><span class="doxyComputerOutput">LATEX_HIDE_INDICES</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">LATEX_HIDE_INDICES</span> tag is set to <span class="doxyComputerOutput">YES</span> then Doxygen will not include the index chapters (such as File Index, Compound Index, etc.) in the output.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_latex_bib_style"></a></p>
</dd>
<dt><span class="doxyComputerOutput">LATEX_BIB_STYLE</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">LATEX_BIB_STYLE</span> tag can be used to specify the style to use for the bibliography, e.g. <span class="doxyComputerOutput">plainnat</span>, or <span class="doxyComputerOutput">ieeetr</span>. See <a href="https://en.wikipedia.org/wiki/BibTeX">https://en.wikipedia.org/wiki/BibTeX</a> and <a href="/web-doxygen/docs/pages/commands/#cmdcite">\cite</a> for more info.</p>

<p>The default value is: <span class="doxyComputerOutput">plainnat</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_latex_emoji_directory"></a></p>
</dd>
<dt><span class="doxyComputerOutput">LATEX_EMOJI_DIRECTORY</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">LATEX_EMOJI_DIRECTORY</span> tag is used to specify the (relative or absolute) path from which the emoji images will be read. If a relative path is entered, it will be relative to the <a href="#cfg_latex_output">LATEX_OUTPUT</a> directory. If left blank the <a href="#cfg_latex_output">LATEX_OUTPUT</a> directory will be used.</p>

<p>This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <span class="doxyComputerOutput">YES</span>.</p>
</dd>
</dl>

## Configuration options related to the RTF output {#config_rtf}


<p><a id="cfg_generate_rtf"></a></p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">GENERATE_RTF</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">GENERATE_RTF</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will generate RTF output. The RTF output is optimized for Word 97 and may not look too pretty with other RTF readers/editors.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_rtf_output"></a></p>
</dd>
<dt><span class="doxyComputerOutput">RTF_OUTPUT</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">RTF_OUTPUT</span> tag is used to specify where the RTF docs will be put. If a relative path is entered the value of <a href="#cfg_output_directory">OUTPUT_DIRECTORY</a> will be put in front of it.</p>

<p>The default directory is: <span class="doxyComputerOutput">rtf</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_rtf">GENERATE_RTF</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_compact_rtf"></a></p>
</dd>
<dt><span class="doxyComputerOutput">COMPACT_RTF</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">COMPACT_RTF</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen generates more compact RTF documents. This may be useful for small projects and may help to save some trees in general.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_rtf">GENERATE_RTF</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_rtf_hyperlinks"></a></p>
</dd>
<dt><span class="doxyComputerOutput">RTF_HYPERLINKS</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">RTF_HYPERLINKS</span> tag is set to <span class="doxyComputerOutput">YES</span>, the RTF that is generated will contain hyperlink fields. The RTF file will contain links (just like the HTML output) instead of page references. This makes the output suitable for online browsing using Word or some other Word compatible readers that support those fields.</p>

<p><br/>
Note: WordPad (write) and others do not support links.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_rtf">GENERATE_RTF</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_rtf_stylesheet_file"></a></p>
</dd>
<dt><span class="doxyComputerOutput">RTF_STYLESHEET_FILE</span></dt>
<dd>
<p>Load stylesheet definitions from file. Syntax is similar to Doxygen's configuration file, i.e. a series of assignments. You only have to provide replacements, missing definitions are set to their default value. 
<br/>
 See also section <a href="/web-doxygen/docs/pages/doxygen-usage">Doxygen usage</a> for information on how to generate the default style sheet that Doxygen normally uses.</p>

<p>This tag requires that the tag <a href="#cfg_generate_rtf">GENERATE_RTF</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_rtf_extensions_file"></a></p>
</dd>
<dt><span class="doxyComputerOutput">RTF_EXTENSIONS_FILE</span></dt>
<dd>
<p>Set optional variables used in the generation of an RTF document. Syntax is similar to Doxygen's configuration file. A template extensions file can be generated using <span class="doxyComputerOutput">doxygen -e rtf extensionFile</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_rtf">GENERATE_RTF</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_rtf_extra_files"></a></p>
</dd>
<dt><span class="doxyComputerOutput">RTF_EXTRA_FILES</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">RTF_EXTRA_FILES</span> tag can be used to specify one or more extra images or other source files which should be copied to the <a href="#cfg_rtf_output">RTF_OUTPUT</a> output directory. Note that the files will be copied as-is; there are no commands or markers available.</p>

<p>This tag requires that the tag <a href="#cfg_generate_rtf">GENERATE_RTF</a> is set to <span class="doxyComputerOutput">YES</span>.</p>
</dd>
</dl>

## Configuration options related to the man page output {#config_man}


<p><a id="cfg_generate_man"></a></p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">GENERATE_MAN</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">GENERATE_MAN</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will generate man pages for classes and files.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_man_output"></a></p>
</dd>
<dt><span class="doxyComputerOutput">MAN_OUTPUT</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">MAN_OUTPUT</span> tag is used to specify where the man pages will be put. If a relative path is entered the value of <a href="#cfg_output_directory">OUTPUT_DIRECTORY</a> will be put in front of it. A directory <span class="doxyComputerOutput">man3</span> will be created inside the directory specified by <span class="doxyComputerOutput">MAN_OUTPUT</span>.</p>

<p>The default directory is: <span class="doxyComputerOutput">man</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_man">GENERATE_MAN</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_man_extension"></a></p>
</dd>
<dt><span class="doxyComputerOutput">MAN_EXTENSION</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">MAN_EXTENSION</span> tag determines the extension that is added to the generated man pages. In case the manual section does not start with a number, the number 3 is prepended. The dot (.) at the beginning of the <span class="doxyComputerOutput">MAN_EXTENSION</span> tag is optional.</p>

<p>The default value is: <span class="doxyComputerOutput">0.3</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_man">GENERATE_MAN</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_man_subdir"></a></p>
</dd>
<dt><span class="doxyComputerOutput">MAN_SUBDIR</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">MAN_SUBDIR</span> tag determines the name of the directory created within <span class="doxyComputerOutput">MAN_OUTPUT</span> in which the man pages are placed. If defaults to man followed by <span class="doxyComputerOutput">MAN_EXTENSION</span> with the initial . removed.</p>

<p>This tag requires that the tag <a href="#cfg_generate_man">GENERATE_MAN</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_man_links"></a></p>
</dd>
<dt><span class="doxyComputerOutput">MAN_LINKS</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">MAN_LINKS</span> tag is set to <span class="doxyComputerOutput">YES</span> and Doxygen generates man output, then it will generate one additional man file for each entity documented in the real man page(s). These additional files only source the real man page, but without them the <span class="doxyComputerOutput">man</span> command would be unable to find the correct page.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_man">GENERATE_MAN</a> is set to <span class="doxyComputerOutput">YES</span>.</p>
</dd>
</dl>

## Configuration options related to the XML output {#config_xml}


<p><a id="cfg_generate_xml"></a></p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">GENERATE_XML</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">GENERATE_XML</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will generate an XML file that captures the structure of the code including all documentation.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_xml_output"></a></p>
</dd>
<dt><span class="doxyComputerOutput">XML_OUTPUT</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">XML_OUTPUT</span> tag is used to specify where the XML pages will be put. If a relative path is entered the value of <a href="#cfg_output_directory">OUTPUT_DIRECTORY</a> will be put in front of it.</p>

<p>The default directory is: <span class="doxyComputerOutput">xml</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_xml">GENERATE_XML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_xml_programlisting"></a></p>
</dd>
<dt><span class="doxyComputerOutput">XML_PROGRAMLISTING</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">XML_PROGRAMLISTING</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will dump the program listings (including syntax highlighting and cross-referencing information) to the XML output. Note that enabling this will significantly increase the size of the XML output.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_xml">GENERATE_XML</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_xml_ns_memb_file_scope"></a></p>
</dd>
<dt><span class="doxyComputerOutput">XML_NS_MEMB_FILE_SCOPE</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">XML_NS_MEMB_FILE_SCOPE</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will include namespace members in file scope as well, matching the HTML output.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_xml">GENERATE_XML</a> is set to <span class="doxyComputerOutput">YES</span>.</p>
</dd>
</dl>

## Configuration options related to the DOCBOOK output {#config_docbook}


<p><a id="cfg_generate_docbook"></a></p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">GENERATE_DOCBOOK</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">GENERATE_DOCBOOK</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will generate Docbook files that can be used to generate PDF.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_docbook_output"></a></p>
</dd>
<dt><span class="doxyComputerOutput">DOCBOOK_OUTPUT</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">DOCBOOK_OUTPUT</span> tag is used to specify where the Docbook pages will be put. If a relative path is entered the value of <a href="#cfg_output_directory">OUTPUT_DIRECTORY</a> will be put in front of it.</p>

<p>The default directory is: <span class="doxyComputerOutput">docbook</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_docbook">GENERATE_DOCBOOK</a> is set to <span class="doxyComputerOutput">YES</span>.</p>
</dd>
</dl>

## Configuration options for the AutoGen Definitions output {#config_autogen}


<p><a id="cfg_generate_autogen_def"></a></p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">GENERATE_AUTOGEN_DEF</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">GENERATE_AUTOGEN_DEF</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will generate an AutoGen Definitions (see <a href="https://autogen.sourceforge.net/">https://autogen.sourceforge.net/</a>) file that captures the structure of the code including all documentation. Note that this feature is still experimental and incomplete at the moment.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>
</dd>
</dl>

## Configuration options related to Sqlite3 output {#config_sqlite3}


<p><a id="cfg_generate_sqlite3"></a></p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">GENERATE_SQLITE3</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">GENERATE_SQLITE3</span> tag is set to <span class="doxyComputerOutput">YES</span> Doxygen will generate a <span class="doxyComputerOutput">Sqlite3</span> database with symbols found by Doxygen stored in tables.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_sqlite3_output"></a></p>
</dd>
<dt><span class="doxyComputerOutput">SQLITE3_OUTPUT</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">SQLITE3_OUTPUT</span> tag is used to specify where the <span class="doxyComputerOutput">Sqlite3</span> database will be put. If a relative path is entered the value of <a href="#cfg_output_directory">OUTPUT_DIRECTORY</a> will be put in front of it.</p>

<p>The default directory is: <span class="doxyComputerOutput">sqlite3</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_sqlite3">GENERATE_SQLITE3</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_sqlite3_recreate_db"></a></p>
</dd>
<dt><span class="doxyComputerOutput">SQLITE3_RECREATE_DB</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">SQLITE3_RECREATE_DB</span> tag is set to <span class="doxyComputerOutput">YES</span>, the existing doxygen_sqlite3.db database file will be recreated with each Doxygen run. If set to <span class="doxyComputerOutput">NO</span>, Doxygen will warn if a database file is already found and not modify it.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_sqlite3">GENERATE_SQLITE3</a> is set to <span class="doxyComputerOutput">YES</span>.</p>
</dd>
</dl>

## Configuration options related to the Perl module output {#config_perlmod}


<p><a id="cfg_generate_perlmod"></a></p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">GENERATE_PERLMOD</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">GENERATE_PERLMOD</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will generate a Perl module file that captures the structure of the code including all documentation. 
<br/>
Note that this feature is still experimental and incomplete at the moment.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_perlmod_latex"></a></p>
</dd>
<dt><span class="doxyComputerOutput">PERLMOD_LATEX</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">PERLMOD_LATEX</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will generate the necessary <span class="doxyComputerOutput">Makefile</span> rules, <span class="doxyComputerOutput">Perl</span> scripts and <code>$\mbox{\LaTeX}$</code> code to be able to generate PDF and DVI output from the Perl module output.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_perlmod">GENERATE_PERLMOD</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_perlmod_pretty"></a></p>
</dd>
<dt><span class="doxyComputerOutput">PERLMOD_PRETTY</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">PERLMOD_PRETTY</span> tag is set to <span class="doxyComputerOutput">YES</span>, the Perl module output will be nicely formatted so it can be parsed by a human reader. This is useful if you want to understand what is going on. On the other hand, if this tag is set to <span class="doxyComputerOutput">NO</span>, the size of the Perl module output will be much smaller and Perl will parse it just the same.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p>This tag requires that the tag <a href="#cfg_generate_perlmod">GENERATE_PERLMOD</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_perlmod_makevar_prefix"></a></p>
</dd>
<dt><span class="doxyComputerOutput">PERLMOD_MAKEVAR_PREFIX</span></dt>
<dd>
<p>The names of the make variables in the generated <span class="doxyComputerOutput">doxyrules.make</span> file are prefixed with the string contained in <span class="doxyComputerOutput">PERLMOD_MAKEVAR_PREFIX</span>. This is useful so different <span class="doxyComputerOutput">doxyrules.make</span> files included by the same <span class="doxyComputerOutput">Makefile</span> don't overwrite each other's variables.</p>

<p>This tag requires that the tag <a href="#cfg_generate_perlmod">GENERATE_PERLMOD</a> is set to <span class="doxyComputerOutput">YES</span>.</p>
</dd>
</dl>

## Configuration options related to the preprocessor {#config_preprocessor}


<p><a id="cfg_enable_preprocessing"></a></p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">ENABLE_PREPROCESSING</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">ENABLE_PREPROCESSING</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will evaluate all C-preprocessor directives found in the sources and include files.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_macro_expansion"></a></p>
</dd>
<dt><span class="doxyComputerOutput">MACRO_EXPANSION</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">MACRO_EXPANSION</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will expand all macro names in the source code. If set to <span class="doxyComputerOutput">NO</span>, only conditional compilation will be performed. Macro expansion can be done in a controlled way by setting <a href="#cfg_expand_only_predef">EXPAND_ONLY_PREDEF</a> to <span class="doxyComputerOutput">YES</span>.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_enable_preprocessing">ENABLE_PREPROCESSING</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_expand_only_predef"></a></p>
</dd>
<dt><span class="doxyComputerOutput">EXPAND_ONLY_PREDEF</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">EXPAND_ONLY_PREDEF</span> and <a href="#cfg_macro_expansion">MACRO_EXPANSION</a> tags are both set to <span class="doxyComputerOutput">YES</span> then the macro expansion is limited to the macros specified with the <a href="#cfg_predefined">PREDEFINED</a> and <a href="#cfg_expand_as_defined">EXPAND_AS_DEFINED</a> tags.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_enable_preprocessing">ENABLE_PREPROCESSING</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_search_includes"></a></p>
</dd>
<dt><span class="doxyComputerOutput">SEARCH_INCLUDES</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">SEARCH_INCLUDES</span> tag is set to <span class="doxyComputerOutput">YES</span>, the include files in the <a href="#cfg_include_path">INCLUDE_PATH</a> will be searched if a <span class="doxyComputerOutput">#include</span> is found.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p>This tag requires that the tag <a href="#cfg_enable_preprocessing">ENABLE_PREPROCESSING</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_include_path"></a></p>
</dd>
<dt><span class="doxyComputerOutput">INCLUDE_PATH</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">INCLUDE_PATH</span> tag can be used to specify one or more directories that contain include files that are not input files but should be processed by the preprocessor.</p>

<p>Note that the <span class="doxyComputerOutput">INCLUDE_PATH</span> is not recursive, so the setting of <a href="#cfg_recursive">RECURSIVE</a> has no effect here.</p>

<p>This tag requires that the tag <a href="#cfg_search_includes">SEARCH_INCLUDES</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_include_file_patterns"></a></p>
</dd>
<dt><span class="doxyComputerOutput">INCLUDE_FILE_PATTERNS</span></dt>
<dd>
<p>You can use the <span class="doxyComputerOutput">INCLUDE_FILE_PATTERNS</span> tag to specify one or more wildcard patterns (like <span class="doxyComputerOutput">*.h</span> and <span class="doxyComputerOutput">*.hpp</span>) to filter out the header-files in the directories. If left blank, the patterns specified with <a href="#cfg_file_patterns">FILE_PATTERNS</a> will be used.</p>

<p>This tag requires that the tag <a href="#cfg_enable_preprocessing">ENABLE_PREPROCESSING</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_predefined"></a></p>
</dd>
<dt><span class="doxyComputerOutput">PREDEFINED</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">PREDEFINED</span> tag can be used to specify one or more macro names that are defined before the preprocessor is started (similar to the <span class="doxyComputerOutput">-D</span> option of e.g. <span class="doxyComputerOutput">gcc</span>). The argument of the tag is a list of macros of the form: <span class="doxyComputerOutput">name</span> or <span class="doxyComputerOutput">name=definition</span> (no spaces). If the definition and the <span class="doxyComputerOutput">"="</span> are omitted, <span class="doxyComputerOutput">"=1"</span> is assumed. To prevent a macro definition from being undefined via <span class="doxyComputerOutput">#undef</span> or recursively expanded use the <span class="doxyComputerOutput">:=</span> operator instead of the <span class="doxyComputerOutput">=</span> operator.</p>

<p>This tag requires that the tag <a href="#cfg_enable_preprocessing">ENABLE_PREPROCESSING</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_expand_as_defined"></a></p>
</dd>
<dt><span class="doxyComputerOutput">EXPAND_AS_DEFINED</span></dt>
<dd>
<p>If the <a href="#cfg_macro_expansion">MACRO_EXPANSION</a> and <a href="#cfg_expand_only_predef">EXPAND_ONLY_PREDEF</a> tags are set to <span class="doxyComputerOutput">YES</span> then this tag can be used to specify a list of macro names that should be expanded. The macro definition that is found in the sources will be used. Use the <a href="#cfg_predefined">PREDEFINED</a> tag if you want to use a different macro definition that overrules the definition found in the source code.</p>

<p>This tag requires that the tag <a href="#cfg_enable_preprocessing">ENABLE_PREPROCESSING</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_skip_function_macros"></a></p>
</dd>
<dt><span class="doxyComputerOutput">SKIP_FUNCTION_MACROS</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">SKIP_FUNCTION_MACROS</span> tag is set to <span class="doxyComputerOutput">YES</span> then Doxygen's preprocessor will remove all references to function-like macros that are alone on a line, have an all uppercase name, and do not end with a semicolon. Such function macros are typically used for boiler-plate code, and will confuse the parser if not removed.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p>This tag requires that the tag <a href="#cfg_enable_preprocessing">ENABLE_PREPROCESSING</a> is set to <span class="doxyComputerOutput">YES</span>.</p>
</dd>
</dl>

## Configuration options related to external references {#config_external}


<p><a id="cfg_tagfiles"></a></p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">TAGFILES</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">TAGFILES</span> tag can be used to specify one or more tag files.</p>

<p>For each tag file the location of the external documentation should be added. The format of a tag file without this location is as follows:</p>



<pre><code>  TAGFILES = file1 file2 ...
</code></pre>


<p>Adding location for the tag files is done as follows:</p>



<pre><code>  TAGFILES = file1=loc1 "file2 = loc2" ...
</code></pre>


<p>where <span class="doxyComputerOutput">loc1</span> and <span class="doxyComputerOutput">loc2</span> can be relative or absolute paths or URLs. See the section <a href="/web-doxygen/docs/pages/external">Linking to external documentation</a> for more information about the use of tag files.</p>


:::info
<p>Each tag file must have a unique name (where the name does <em>NOT</em> include the path). If a tag file is not located in the directory in which Doxygen is run, you must also specify the path to the tagfile here.</p>
:::


<p><a id="cfg_generate_tagfile"></a></p>
</dd>
<dt><span class="doxyComputerOutput">GENERATE_TAGFILE</span></dt>
<dd>
<p>When a file name is specified after <span class="doxyComputerOutput">GENERATE_TAGFILE</span>, Doxygen will create a tag file that is based on the input files it reads. See section <a href="/web-doxygen/docs/pages/external">Linking to external documentation</a> for more information about the usage of tag files.</p>

<p><a id="cfg_allexternals"></a></p>
</dd>
<dt><span class="doxyComputerOutput">ALLEXTERNALS</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">ALLEXTERNALS</span> tag is set to <span class="doxyComputerOutput">YES</span>, all external classes and namespaces will be listed in the class and namespace index. If set to <span class="doxyComputerOutput">NO</span>, only the inherited external classes will be listed.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_external_groups"></a></p>
</dd>
<dt><span class="doxyComputerOutput">EXTERNAL_GROUPS</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">EXTERNAL_GROUPS</span> tag is set to <span class="doxyComputerOutput">YES</span>, all external groups will be listed in the topic index. If set to <span class="doxyComputerOutput">NO</span>, only the current project's groups will be listed.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_external_pages"></a></p>
</dd>
<dt><span class="doxyComputerOutput">EXTERNAL_PAGES</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">EXTERNAL_PAGES</span> tag is set to <span class="doxyComputerOutput">YES</span>, all external pages will be listed in the related pages index. If set to <span class="doxyComputerOutput">NO</span>, only the current project's pages will be listed.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>
</dd>
</dl>

## Configuration options related to diagram generator tools {#config_dot}


<p><a id="cfg_hide_undoc_relations"></a></p>


<dl class="doxyVariableList">
<dt><span class="doxyComputerOutput">HIDE_UNDOC_RELATIONS</span></dt>
<dd>
<p>If set to <span class="doxyComputerOutput">YES</span> the inheritance and collaboration graphs will hide inheritance and usage relations if the target is undocumented or is not a class.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_have_dot"></a></p>
</dd>
<dt><span class="doxyComputerOutput">HAVE_DOT</span></dt>
<dd>
<p>If you set the <span class="doxyComputerOutput">HAVE_DOT</span> tag to <span class="doxyComputerOutput">YES</span> then Doxygen will assume the <span class="doxyComputerOutput">dot</span> tool is available from the <span class="doxyComputerOutput">path</span>. This tool is part of <a href="https://www.graphviz.org/">Graphviz</a>, a graph visualization toolkit from AT&amp;T and Lucent Bell Labs. The other options in this section have no effect if this option is set to <span class="doxyComputerOutput">NO</span></p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p><a id="cfg_dot_num_threads"></a></p>
</dd>
<dt><span class="doxyComputerOutput">DOT_NUM_THREADS</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">DOT_NUM_THREADS</span> specifies the number of <span class="doxyComputerOutput">dot</span> invocations Doxygen is allowed to run in parallel. When set to <span class="doxyComputerOutput">0</span> Doxygen will base this on the number of processors available in the system. You can set it explicitly to a value larger than 0 to get control over the balance between CPU load and processing speed.</p>

<p>Minimum value: <span class="doxyComputerOutput">0</span>, maximum value: <span class="doxyComputerOutput">32</span>, default value: <span class="doxyComputerOutput">0</span>.</p>

<p>This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_dot_common_attr"></a></p>
</dd>
<dt><span class="doxyComputerOutput">DOT_COMMON_ATTR</span></dt>
<dd>
<p><span class="doxyComputerOutput">DOT_COMMON_ATTR</span> is common attributes for nodes, edges and labels of subgraphs. When you want a differently looking font in the dot files that Doxygen generates you can specify fontname, fontcolor and fontsize attributes. For details please see <a href="https://graphviz.org/doc/info/attrs.html">Node, Edge and Graph Attributes specification</a> You need to make sure dot is able to find the font, which can be done by putting it in a standard location or by setting the <span class="doxyComputerOutput">DOTFONTPATH</span> environment variable or by setting <a href="#cfg_dot_fontpath">DOT_FONTPATH</a> to the directory containing the font. Default graphviz fontsize is 14.</p>

<p>The default value is: <span class="doxyComputerOutput">fontname=Helvetica,fontsize=10</span>.</p>

<p>This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_dot_edge_attr"></a></p>
</dd>
<dt><span class="doxyComputerOutput">DOT_EDGE_ATTR</span></dt>
<dd>
<p><span class="doxyComputerOutput">DOT_EDGE_ATTR</span> is concatenated with <a href="#cfg_dot_common_attr">DOT_COMMON_ATTR</a>. For elegant style you can add 'arrowhead=open, arrowtail=open, arrowsize=0.5'. <a href="https://graphviz.org/doc/info/arrows.html">Complete documentation about arrows shapes.</a></p>

<p>The default value is: <span class="doxyComputerOutput">labelfontname=Helvetica,labelfontsize=10</span>.</p>

<p>This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_dot_node_attr"></a></p>
</dd>
<dt><span class="doxyComputerOutput">DOT_NODE_ATTR</span></dt>
<dd>
<p><span class="doxyComputerOutput">DOT_NODE_ATTR</span> is concatenated with <a href="#cfg_dot_common_attr">DOT_COMMON_ATTR</a>. For view without boxes around nodes set 'shape=plain' or 'shape=plaintext' <a href="https://www.graphviz.org/doc/info/shapes.html">Shapes specification</a></p>

<p>The default value is: <span class="doxyComputerOutput">shape=box,height=0.2,width=0.4</span>.</p>

<p>This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_dot_fontpath"></a></p>
</dd>
<dt><span class="doxyComputerOutput">DOT_FONTPATH</span></dt>
<dd>
<p>You can set the path where <span class="doxyComputerOutput">dot</span> can find font specified with fontname in <a href="#cfg_dot_common_attr">DOT_COMMON_ATTR</a> and others dot attributes.</p>

<p>This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_class_graph"></a></p>
</dd>
<dt><span class="doxyComputerOutput">CLASS_GRAPH</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">CLASS_GRAPH</span> tag is set to <span class="doxyComputerOutput">YES</span> or <span class="doxyComputerOutput">GRAPH</span> or <span class="doxyComputerOutput">BUILTIN</span> then Doxygen will generate a graph for each documented class showing the direct and indirect inheritance relations. In case the <span class="doxyComputerOutput">CLASS_GRAPH</span> tag is set to <span class="doxyComputerOutput">YES</span> or <span class="doxyComputerOutput">GRAPH</span> and <a href="#cfg_have_dot">HAVE_DOT</a> is enabled as well, then <span class="doxyComputerOutput">dot</span> will be used to draw the graph. In case the <span class="doxyComputerOutput">CLASS_GRAPH</span> tag is set to <span class="doxyComputerOutput">YES</span> and <a href="#cfg_have_dot">HAVE_DOT</a> is disabled or if the <span class="doxyComputerOutput">CLASS_GRAPH</span> tag is set to <span class="doxyComputerOutput">BUILTIN</span>, then the built-in generator will be used. If the <span class="doxyComputerOutput">CLASS_GRAPH</span> tag is set to <span class="doxyComputerOutput">TEXT</span> the direct and indirect inheritance relations will be shown as texts / links. Explicit enabling an inheritance graph or choosing a different representation for an inheritance graph of a specific class, can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmdinheritancegraph">\inheritancegraph</a>. Disabling an inheritance graph can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmdhideinheritancegraph">\hideinheritancegraph</a>.</p>

<p>Possible values are: <span class="doxyComputerOutput">NO</span>, <span class="doxyComputerOutput">YES</span>, <span class="doxyComputerOutput">TEXT</span>, <span class="doxyComputerOutput">GRAPH</span> and <span class="doxyComputerOutput">BUILTIN</span>.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_collaboration_graph"></a></p>
</dd>
<dt><span class="doxyComputerOutput">COLLABORATION_GRAPH</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">COLLABORATION_GRAPH</span> tag is set to <span class="doxyComputerOutput">YES</span> then Doxygen will generate a graph for each documented class showing the direct and indirect implementation dependencies (inheritance, containment, and class references variables) of the class with other documented classes. Explicit enabling a collaboration graph, when <span class="doxyComputerOutput">COLLABORATION_GRAPH</span> is set to <span class="doxyComputerOutput">NO</span>, can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmdcollaborationgraph">\collaborationgraph</a>. Disabling a collaboration graph can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmdhidecollaborationgraph">\hidecollaborationgraph</a>.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p>This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_group_graphs"></a></p>
</dd>
<dt><span class="doxyComputerOutput">GROUP_GRAPHS</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">GROUP_GRAPHS</span> tag is set to <span class="doxyComputerOutput">YES</span> then Doxygen will generate a graph for groups, showing the direct groups dependencies. Explicit enabling a group dependency graph, when <span class="doxyComputerOutput">GROUP_GRAPHS</span> is set to <span class="doxyComputerOutput">NO</span>, can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmdgroupgraph">\groupgraph</a>. Disabling a directory graph can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmdhidegroupgraph">\hidegroupgraph</a>.</p>

<p>See also the chapter <a href="/web-doxygen/docs/pages/grouping">Grouping</a> in the manual.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p>This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_uml_look"></a></p>
</dd>
<dt><span class="doxyComputerOutput">UML_LOOK</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">UML_LOOK</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will generate inheritance and collaboration diagrams in a style similar to the OMG's Unified Modeling Language.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_uml_limit_num_fields"></a></p>
</dd>
<dt><span class="doxyComputerOutput">UML_LIMIT_NUM_FIELDS</span></dt>
<dd>
<p>If the <a href="#cfg_uml_look">UML_LOOK</a> tag is enabled, the fields and methods are shown inside the class node. If there are many fields or methods and many nodes the graph may become too big to be useful. The <span class="doxyComputerOutput">UML_LIMIT_NUM_FIELDS</span> threshold limits the number of items for each type to make the size more manageable. Set this to 0 for no limit. Note that the threshold may be exceeded by 50% before the limit is enforced. So when you set the threshold to 10, up to 15 fields may appear, but if the number exceeds 15, the total amount of fields shown is limited to 10.</p>

<p>Minimum value: <span class="doxyComputerOutput">0</span>, maximum value: <span class="doxyComputerOutput">100</span>, default value: <span class="doxyComputerOutput">10</span>.</p>

<p>This tag requires that the tag <a href="#cfg_uml_look">UML_LOOK</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_uml_max_edge_labels"></a></p>
</dd>
<dt><span class="doxyComputerOutput">UML_MAX_EDGE_LABELS</span></dt>
<dd>
<p>If the <a href="#cfg_uml_look">UML_LOOK</a> tag is enabled, field labels are shown along the edge between two class nodes. If there are many fields and many nodes the graph may become too cluttered. The <span class="doxyComputerOutput">UML_MAX_EDGE_LABELS</span> threshold limits the number of items to make the size more manageable. Set this to 0 for no limit.</p>

<p>Minimum value: <span class="doxyComputerOutput">0</span>, maximum value: <span class="doxyComputerOutput">100</span>, default value: <span class="doxyComputerOutput">10</span>.</p>

<p>This tag requires that the tag <a href="#cfg_uml_look">UML_LOOK</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_dot_uml_details"></a></p>
</dd>
<dt><span class="doxyComputerOutput">DOT_UML_DETAILS</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">DOT_UML_DETAILS</span> tag is set to <span class="doxyComputerOutput">NO</span>, Doxygen will show attributes and methods without types and arguments in the UML graphs. If the <span class="doxyComputerOutput">DOT_UML_DETAILS</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will add type and arguments for attributes and methods in the UML graphs. If the <span class="doxyComputerOutput">DOT_UML_DETAILS</span> tag is set to <span class="doxyComputerOutput">NONE</span>, Doxygen will not generate fields with class member information in the UML graphs. The class diagrams will look similar to the default class diagrams but using UML notation for the relationships.</p>

<p>Possible values are: <span class="doxyComputerOutput">NO</span>, <span class="doxyComputerOutput">YES</span> and <span class="doxyComputerOutput">NONE</span>.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_uml_look">UML_LOOK</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_dot_wrap_threshold"></a></p>
</dd>
<dt><span class="doxyComputerOutput">DOT_WRAP_THRESHOLD</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">DOT_WRAP_THRESHOLD</span> tag can be used to set the maximum number of characters to display on a single line. If the actual line length exceeds this threshold significantly it will be wrapped across multiple lines. Some heuristics are applied to avoid ugly line breaks.</p>

<p>Minimum value: <span class="doxyComputerOutput">0</span>, maximum value: <span class="doxyComputerOutput">1000</span>, default value: <span class="doxyComputerOutput">17</span>.</p>

<p>This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_template_relations"></a></p>
</dd>
<dt><span class="doxyComputerOutput">TEMPLATE_RELATIONS</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">TEMPLATE_RELATIONS</span> tag is set to <span class="doxyComputerOutput">YES</span> then the inheritance and collaboration graphs will show the relations between templates and their instances.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_include_graph"></a></p>
</dd>
<dt><span class="doxyComputerOutput">INCLUDE_GRAPH</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">INCLUDE_GRAPH</span>, <a href="#cfg_enable_preprocessing">ENABLE_PREPROCESSING</a> and <a href="#cfg_search_includes">SEARCH_INCLUDES</a> tags are set to <span class="doxyComputerOutput">YES</span> then Doxygen will generate a graph for each documented file showing the direct and indirect include dependencies of the file with other documented files. Explicit enabling an include graph, when <span class="doxyComputerOutput">INCLUDE_GRAPH</span> is is set to <span class="doxyComputerOutput">NO</span>, can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmdincludegraph">\includegraph</a>. Disabling an include graph can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmdhideincludegraph">\hideincludegraph</a>.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p>This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_included_by_graph"></a></p>
</dd>
<dt><span class="doxyComputerOutput">INCLUDED_BY_GRAPH</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">INCLUDED_BY_GRAPH</span>, <a href="#cfg_enable_preprocessing">ENABLE_PREPROCESSING</a> and <a href="#cfg_search_includes">SEARCH_INCLUDES</a> tags are set to <span class="doxyComputerOutput">YES</span> then Doxygen will generate a graph for each documented file showing the direct and indirect include dependencies of the file with other documented files. Explicit enabling an included by graph, when <span class="doxyComputerOutput">INCLUDED_BY_GRAPH</span> is set to <span class="doxyComputerOutput">NO</span>, can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmdincludedbygraph">\includedbygraph</a>. Disabling an included by graph can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmdhideincludedbygraph">\hideincludedbygraph</a>.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p>This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_call_graph"></a></p>
</dd>
<dt><span class="doxyComputerOutput">CALL_GRAPH</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">CALL_GRAPH</span> tag is set to <span class="doxyComputerOutput">YES</span> then Doxygen will generate a call dependency graph for every global function or class method. 
<br/>
Note that enabling this option will significantly increase the time of a run. So in most cases it will be better to enable call graphs for selected functions only using the <a href="/web-doxygen/docs/pages/commands/#cmdcallgraph">\callgraph</a> command. Disabling a call graph can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmdhidecallgraph">\hidecallgraph</a>.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_caller_graph"></a></p>
</dd>
<dt><span class="doxyComputerOutput">CALLER_GRAPH</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">CALLER_GRAPH</span> tag is set to <span class="doxyComputerOutput">YES</span> then Doxygen will generate a caller dependency graph for every global function or class method. 
<br/>
Note that enabling this option will significantly increase the time of a run. So in most cases it will be better to enable caller graphs for selected functions only using the <a href="/web-doxygen/docs/pages/commands/#cmdcallergraph">\callergraph</a> command. Disabling a caller graph can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmdhidecallergraph">\hidecallergraph</a>.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_graphical_hierarchy"></a></p>
</dd>
<dt><span class="doxyComputerOutput">GRAPHICAL_HIERARCHY</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">GRAPHICAL_HIERARCHY</span> tag is set to <span class="doxyComputerOutput">YES</span> then Doxygen will graphical hierarchy of all classes instead of a textual one.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p>This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_directory_graph"></a></p>
</dd>
<dt><span class="doxyComputerOutput">DIRECTORY_GRAPH</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">DIRECTORY_GRAPH</span> tag is set to <span class="doxyComputerOutput">YES</span> then Doxygen will show the dependencies a directory has on other directories in a graphical way. The dependency relations are determined by the <span class="doxyComputerOutput">#include</span> relations between the files in the directories. Explicit enabling a directory graph, when <span class="doxyComputerOutput">DIRECTORY_GRAPH</span> is set to <span class="doxyComputerOutput">NO</span>, can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmddirectorygraph">\directorygraph</a>. Disabling a directory graph can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmdhidedirectorygraph">\hidedirectorygraph</a>.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p>This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_dir_graph_max_depth"></a></p>
</dd>
<dt><span class="doxyComputerOutput">DIR_GRAPH_MAX_DEPTH</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">DIR_GRAPH_MAX_DEPTH</span> tag can be used to limit the maximum number of levels of child directories generated in directory dependency graphs by <span class="doxyComputerOutput">dot</span>.</p>

<p>Minimum value: <span class="doxyComputerOutput">1</span>, maximum value: <span class="doxyComputerOutput">25</span>, default value: <span class="doxyComputerOutput">1</span>.</p>

<p>This tag requires that the tag <a href="#cfg_directory_graph">DIRECTORY_GRAPH</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_dot_image_format"></a></p>
</dd>
<dt><span class="doxyComputerOutput">DOT_IMAGE_FORMAT</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">DOT_IMAGE_FORMAT</span> tag can be used to set the image format of the images generated by <span class="doxyComputerOutput">dot</span>. For an explanation of the image formats see the section output formats in the documentation of the <span class="doxyComputerOutput">dot</span> tool (<a href="https://www.graphviz.org/">Graphviz</a>). 
<br/>
Note the formats <span class="doxyComputerOutput">svg:cairo</span> and <span class="doxyComputerOutput">svg:cairo:cairo</span> cannot be used in combination with <a href="#cfg_interactive_svg">INTERACTIVE_SVG</a> (the <a href="#cfg_interactive_svg">INTERACTIVE_SVG</a> will be set to <span class="doxyComputerOutput">NO</span>).</p>

<p>Possible values are: <span class="doxyComputerOutput">png</span>, <span class="doxyComputerOutput">jpg</span>, <span class="doxyComputerOutput">gif</span>, <span class="doxyComputerOutput">svg</span>, <span class="doxyComputerOutput">png:gd</span>, <span class="doxyComputerOutput">png:gd:gd</span>, <span class="doxyComputerOutput">png:cairo</span>, <span class="doxyComputerOutput">png:cairo:gd</span>, <span class="doxyComputerOutput">png:cairo:cairo</span>, <span class="doxyComputerOutput">png:cairo:gdiplus</span>, <span class="doxyComputerOutput">png:gdiplus</span>, <span class="doxyComputerOutput">png:gdiplus:gdiplus</span>, <span class="doxyComputerOutput">svg:cairo</span>, <span class="doxyComputerOutput">svg:cairo:cairo</span>, <span class="doxyComputerOutput">svg:svg</span>, <span class="doxyComputerOutput">svg:svg:core</span>, <span class="doxyComputerOutput">gif:cairo</span>, <span class="doxyComputerOutput">gif:cairo:gd</span>, <span class="doxyComputerOutput">gif:cairo:gdiplus</span>, <span class="doxyComputerOutput">gif:gdiplus</span>, <span class="doxyComputerOutput">gif:gdiplus:gdiplus</span>, <span class="doxyComputerOutput">gif:gd</span>, <span class="doxyComputerOutput">gif:gd:gd</span>, <span class="doxyComputerOutput">jpg:cairo</span>, <span class="doxyComputerOutput">jpg:cairo:gd</span>, <span class="doxyComputerOutput">jpg:cairo:gdiplus</span>, <span class="doxyComputerOutput">jpg:gd</span>, <span class="doxyComputerOutput">jpg:gd:gd</span>, <span class="doxyComputerOutput">jpg:gdiplus</span> and <span class="doxyComputerOutput">jpg:gdiplus:gdiplus</span>.</p>

<p>The default value is: <span class="doxyComputerOutput">png</span>.</p>

<p>This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_interactive_svg"></a></p>
</dd>
<dt><span class="doxyComputerOutput">INTERACTIVE_SVG</span></dt>
<dd>
<p>If <a href="#cfg_dot_image_format">DOT_IMAGE_FORMAT</a> is set to <span class="doxyComputerOutput">svg</span> or <span class="doxyComputerOutput">svg:svg</span> or <span class="doxyComputerOutput">svg:svg:core</span>, then this option can be set to <span class="doxyComputerOutput">YES</span> to enable generation of interactive SVG images that allow zooming and panning. 
<br/>
Note that this requires a modern browser other than Internet Explorer. Tested and working are Firefox, Chrome, Safari, and Opera. 
<br/>
Note This option will be automatically disabled when <a href="#cfg_dot_image_format">DOT_IMAGE_FORMAT</a> is set to <span class="doxyComputerOutput">svg:cairo</span> or <span class="doxyComputerOutput">svg:cairo:cairo</span>.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_dot_path"></a></p>
</dd>
<dt><span class="doxyComputerOutput">DOT_PATH</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">DOT_PATH</span> tag can be used to specify the path where the <span class="doxyComputerOutput">dot</span> tool can be found. If left blank, it is assumed the <span class="doxyComputerOutput">dot</span> tool can be found in the <span class="doxyComputerOutput">path</span>.</p>

<p>This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_dotfile_dirs"></a></p>
</dd>
<dt><span class="doxyComputerOutput">DOTFILE_DIRS</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">DOTFILE_DIRS</span> tag can be used to specify one or more directories that contain dot files that are included in the documentation (see the <a href="/web-doxygen/docs/pages/commands/#cmddotfile">\dotfile</a> command).</p>

<p>This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_dia_path"></a></p>
</dd>
<dt><span class="doxyComputerOutput">DIA_PATH</span></dt>
<dd>
<p>You can include diagrams made with dia in Doxygen documentation. Doxygen will then run dia to produce the diagram and insert it in the documentation. The DIA_PATH tag allows you to specify the directory where the dia binary resides. If left empty dia is assumed to be found in the default search path.</p>

<p><a id="cfg_diafile_dirs"></a></p>
</dd>
<dt><span class="doxyComputerOutput">DIAFILE_DIRS</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">DIAFILE_DIRS</span> tag can be used to specify one or more directories that contain dia files that are included in the documentation (see the <a href="/web-doxygen/docs/pages/commands/#cmddiafile">\diafile</a> command).</p>

<p><a id="cfg_plantuml_jar_path"></a></p>
</dd>
<dt><span class="doxyComputerOutput">PLANTUML_JAR_PATH</span></dt>
<dd>
<p>When using PlantUML, the <span class="doxyComputerOutput">PLANTUML_JAR_PATH</span> tag should be used to specify the path where java can find the <span class="doxyComputerOutput">plantuml.jar</span> file or to the filename of <span class="doxyComputerOutput">jar</span> file to be used. If left blank, it is assumed PlantUML is not used or called during a preprocessing step. Doxygen will generate a warning when it encounters a <a href="/web-doxygen/docs/pages/commands/#cmdstartuml">\startuml</a> command in this case and will not generate output for the diagram.</p>

<p><a id="cfg_plantuml_cfg_file"></a></p>
</dd>
<dt><span class="doxyComputerOutput">PLANTUML_CFG_FILE</span></dt>
<dd>
<p>When using PlantUML, the <span class="doxyComputerOutput">PLANTUML_CFG_FILE</span> tag can be used to specify a configuration file for PlantUML.</p>

<p><a id="cfg_plantuml_include_path"></a></p>
</dd>
<dt><span class="doxyComputerOutput">PLANTUML_INCLUDE_PATH</span></dt>
<dd>
<p>When using PlantUML, the specified paths are searched for files specified by the <span class="doxyComputerOutput">!include</span> statement in a PlantUML block.</p>

<p><a id="cfg_plantumlfile_dirs"></a></p>
</dd>
<dt><span class="doxyComputerOutput">PLANTUMLFILE_DIRS</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">PLANTUMLFILE_DIRS</span> tag can be used to specify one or more directories that contain PlantUml files that are included in the documentation (see the <a href="/web-doxygen/docs/pages/commands/#cmdplantumlfile">\plantumlfile</a> command).</p>

<p><a id="cfg_dot_graph_max_nodes"></a></p>
</dd>
<dt><span class="doxyComputerOutput">DOT_GRAPH_MAX_NODES</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">DOT_GRAPH_MAX_NODES</span> tag can be used to set the maximum number of nodes that will be shown in the graph. If the number of nodes in a graph becomes larger than this value, Doxygen will truncate the graph, which is visualized by representing a node as a red box. Note that if the number of direct children of the root node in a graph is already larger than <span class="doxyComputerOutput">DOT_GRAPH_MAX_NODES</span> then the graph will not be shown at all. Also note that the size of a graph can be further restricted by <a href="#cfg_max_dot_graph_depth">MAX_DOT_GRAPH_DEPTH</a>.</p>

<p>Minimum value: <span class="doxyComputerOutput">0</span>, maximum value: <span class="doxyComputerOutput">10000</span>, default value: <span class="doxyComputerOutput">50</span>.</p>

<p>This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_max_dot_graph_depth"></a></p>
</dd>
<dt><span class="doxyComputerOutput">MAX_DOT_GRAPH_DEPTH</span></dt>
<dd>
<p>The <span class="doxyComputerOutput">MAX_DOT_GRAPH_DEPTH</span> tag can be used to set the maximum depth of the graphs generated by <span class="doxyComputerOutput">dot</span>. A depth value of 3 means that only nodes reachable from the root by following a path via at most 3 edges will be shown. Nodes that lay further from the root node will be omitted. Note that setting this option to 1 or 2 may greatly reduce the computation time needed for large code bases. Also note that the size of a graph can be further restricted by <a href="#cfg_dot_graph_max_nodes">DOT_GRAPH_MAX_NODES</a>. Using a depth of 0 means no depth restriction.</p>

<p>Minimum value: <span class="doxyComputerOutput">0</span>, maximum value: <span class="doxyComputerOutput">1000</span>, default value: <span class="doxyComputerOutput">0</span>.</p>

<p>This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_dot_multi_targets"></a></p>
</dd>
<dt><span class="doxyComputerOutput">DOT_MULTI_TARGETS</span></dt>
<dd>
<p>Set the <span class="doxyComputerOutput">DOT_MULTI_TARGETS</span> tag to <span class="doxyComputerOutput">YES</span> to allow dot to generate multiple output files in one run (i.e. multiple -o and -T options on the command line). This makes <span class="doxyComputerOutput">dot</span> run faster, but since only newer versions of <span class="doxyComputerOutput">dot</span> (&gt;1.8.10) support this, this feature is disabled by default.</p>

<p>The default value is: <span class="doxyComputerOutput">NO</span>.</p>

<p>This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_generate_legend"></a></p>
</dd>
<dt><span class="doxyComputerOutput">GENERATE_LEGEND</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">GENERATE_LEGEND</span> tag is set to <span class="doxyComputerOutput">YES</span> Doxygen will generate a legend page explaining the meaning of the various boxes and arrows in the dot generated graphs.</p>



:::info
<p>This tag requires that <a href="#cfg_uml_look">UML_LOOK</a> isn't set, i.e. the Doxygen internal graphical representation for inheritance and collaboration diagrams is used.</p>
:::


<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p>This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <span class="doxyComputerOutput">YES</span>. <a id="cfg_dot_cleanup"></a></p>
</dd>
<dt><span class="doxyComputerOutput">DOT_CLEANUP</span></dt>
<dd>
<p>If the <span class="doxyComputerOutput">DOT_CLEANUP</span> tag is set to <span class="doxyComputerOutput">YES</span>, Doxygen will remove the intermediate files that are used to generate the various graphs. 
<br/>
Note: This setting is not only used for dot files but also for msc temporary files.</p>

<p>The default value is: <span class="doxyComputerOutput">YES</span>.</p>

<p><a id="cfg_mscgen_tool"></a></p>
</dd>
<dt><span class="doxyComputerOutput">MSCGEN_TOOL</span></dt>
<dd>
<p>You can define message sequence charts within Doxygen comments using the <a href="/web-doxygen/docs/pages/commands/#cmdmsc">\msc</a> command. If the <span class="doxyComputerOutput">MSCGEN_TOOL</span> tag is left empty (the default), then Doxygen will use a built-in version of mscgen tool to produce the charts. Alternatively, the <span class="doxyComputerOutput">MSCGEN_TOOL</span> tag can also specify the name an external tool. For instance, specifying <span class="doxyComputerOutput">prog</span> as the value, Doxygen will call the tool as <span class="doxyComputerOutput">prog -T &lt;outfile_format&gt; -o &lt;outputfile&gt; &lt;inputfile&gt;</span>. The external tool should support output file formats "png", "eps", "svg", and "ismap".</p>

<p><a id="cfg_mscfile_dirs"></a></p>
</dd>
<dt><span class="doxyComputerOutput">MSCFILE_DIRS</span></dt>
<dd><p>The <span class="doxyComputerOutput">MSCFILE_DIRS</span> tag can be used to specify one or more directories that contain msc files that are included in the documentation (see the <a href="/web-doxygen/docs/pages/commands/#cmdmscfile">\mscfile</a> command).</p></dd>
</dl>

## Examples {#config_examples}


<p>Suppose you have a simple project consisting of two files: a source file <span class="doxyComputerOutput">example.cc</span> and a header file <span class="doxyComputerOutput">example.h</span>. Then a minimal configuration file is as simple as:</p>



<pre><code>INPUT            = example.cc example.h
</code></pre>


<p>Assuming the example makes use of Qt classes and <span class="doxyComputerOutput">perl</span> is located in <span class="doxyComputerOutput">/usr/bin</span>, a more realistic configuration file would be:</p>



<pre><code>PROJECT_NAME     = Example
INPUT            = example.cc example.h
WARNINGS         = YES
TAGFILES         = qt.tag
SEARCHENGINE     = NO
</code></pre>


<p>To generate the documentation for the <a href="https://sourceforge.net/projects/qdbttabular/">QdbtTabular</a> package I have used the following configuration file:</p>



<pre><code>PROJECT_NAME     = QdbtTabular
OUTPUT_DIRECTORY = html
WARNINGS         = YES
INPUT            = examples/examples.doc src
FILE_PATTERNS    = *.cc *.h
INCLUDE_PATH     = examples
TAGFILES         = qt.tag
SEARCHENGINE     = YES
</code></pre>


<p>To regenerate the Qt-1.44 documentation from the sources, you could use the following configuration file:</p>



<pre><code>PROJECT_NAME         = Qt
OUTPUT_DIRECTORY     = qt_docs
HIDE_UNDOC_MEMBERS   = YES
HIDE_UNDOC_CLASSES   = YES
ENABLE_PREPROCESSING = YES
MACRO_EXPANSION      = YES
EXPAND_ONLY_PREDEF   = YES
SEARCH_INCLUDES      = YES
FULL_PATH_NAMES      = YES
STRIP_FROM_PATH      = $(QTDIR)/
PREDEFINED           = USE_TEMPLATECLASS Q_EXPORT= \
                       QArrayT:=QArray \
                       QListT:=QList \
                       QDictT:=QDict \
                       QQueueT:=QQueue \
                       QVectorT:=QVector \
                       QPtrDictT:=QPtrDict \
                       QIntDictT:=QIntDict \
                       QStackT:=QStack \
                       QDictIteratorT:=QDictIterator \
                       QListIteratorT:=QListIterator \
                       QCacheT:=QCache \
                       QCacheIteratorT:=QCacheIterator \
                       QIntCacheT:=QIntCache \
                       QIntCacheIteratorT:=QIntCacheIterator \
                       QIntDictIteratorT:=QIntDictIterator \
                       QPtrDictIteratorT:=QPtrDictIterator
INPUT                = $(QTDIR)/doc \
                       $(QTDIR)/src/widgets \
                       $(QTDIR)/src/kernel \
                       $(QTDIR)/src/dialogs \
                       $(QTDIR)/src/tools
FILE_PATTERNS        = *.cpp *.h q*.doc
INCLUDE_PATH         = $(QTDIR)/include
RECURSIVE            = YES
</code></pre>


<p>For the Qt-2.1 sources I recommend to use the following settings:</p>



<pre><code>PROJECT_NAME          = Qt
PROJECT_NUMBER        = 2.1
HIDE_UNDOC_MEMBERS    = YES
HIDE_UNDOC_CLASSES    = YES
SOURCE_BROWSER        = YES
INPUT                 = $(QTDIR)/src
FILE_PATTERNS         = *.cpp *.h q*.doc
RECURSIVE             = YES
EXCLUDE_PATTERNS      = *codec.cpp moc_* */compat/* */3rdparty/*
ALPHABETICAL_INDEX    = YES
IGNORE_PREFIX         = Q
ENABLE_PREPROCESSING  = YES
MACRO_EXPANSION       = YES
INCLUDE_PATH          = $(QTDIR)/include
PREDEFINED            = Q_PROPERTY(x)= \
                        Q_OVERRIDE(x)= \
                        Q_EXPORT= \
                        Q_ENUMS(x)= \
                        "QT_STATIC_CONST=static const " \
                        _WS_X11_ \
                        INCLUDE_MENUITEM_DEF
EXPAND_ONLY_PREDEF    = YES
EXPAND_AS_DEFINED     = Q_OBJECT_FAKE Q_OBJECT ACTIVATE_SIGNAL_WITH_PARAM \
                        Q_VARIANT_AS
</code></pre>


<p>Here Doxygen's preprocessor is used to substitute some macro names that are normally substituted by the C preprocessor, but without doing full macro expansion.</p>

 
Go to the <a href="/docs/pages/commands/">next</a> section or return to the
 <a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
