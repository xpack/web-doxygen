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


A configuration file is a free-form ASCII text file with a structure that is similar to that of a <code>Makefile</code>, with the default name <code>Doxyfile</code>. It is parsed by <code>doxygen</code>. The file may contain tabs and newlines for formatting purposes. The statements in the file are case-sensitive.

The configuration file essentially consists of a list of assignment statements. Each statement consists of a <code>TAG\_NAME</code> written in capitals, followed by the equal sign (<code>=</code>) and one or more values. If the same tag is assigned more than once, the last assignment overwrites any earlier assignment. For tags that take a list as their argument, the <code>+=</code> operator can be used instead of <code>=</code> to append new values to the list. Values are sequences of non-blanks. If the value should contain one or more blanks it must be surrounded by quotes (<code>"..."</code>). Multiple lines can be concatenated by inserting a backslash (<code>\\</code>) as the last non-whitespace character of a line.

Comments begin with the hash character (<code>#</code>) and end at the end of the line. Comments may be placed anywhere within the file (except within quotes). Comments beginning with two hash characters (<code>##</code>) are kept while updating the configuration file when they are placed in front of a <code>TAG\_NAME</code>, or at the beginning or end of the configuration file.

Environment variables can be expanded using the pattern <code>$(ENV\_VARIABLE\_NAME)</code>. A small example:


<pre><code>DOT_PATH      = $(YOUR_DOT_PATH)
</code></pre>


You can also include part of a configuration file from another configuration file using a <code>@INCLUDE</code> tag as follows:


<pre><code>@INCLUDE = config_file_name
</code></pre>


The include file is searched in the current working directory. You can also specify a list of directories that should be searched before looking in the current working directory. Do this by putting a <code>@INCLUDE\_PATH</code> tag with these paths before the <code>@INCLUDE</code> tag, e.g.:


<pre><code>@INCLUDE_PATH = my_config_dir
</code></pre>


The configuration options can be divided into several categories. Below is an alphabetical index of the tags that are recognized followed by the descriptions of the tags grouped by category.


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


<a id="cfg_doxyfile_encoding"></a>

<dl class="doxyVariableList">
<dt><code>DOXYFILE_ENCODING</code></dt>
<dd>This tag specifies the encoding used for all characters in the configuration file that follow. The default is UTF-8 which is also the encoding used for all text before the first occurrence of this tag. Doxygen uses <code>libiconv</code> (or the iconv built into <code>libc</code>) for the transcoding. See <a href="https://www.gnu.org/software/libiconv/">https://www.gnu.org/software/libiconv/</a> for the list of possible encodings.
The default value is: <code>UTF-8</code>.
<a id="cfg_project_name"></a></dd>
<dt><code>PROJECT_NAME</code></dt>
<dd>The <code>PROJECT_NAME</code> tag is a single word (or a sequence of words surrounded by double-quotes, unless you are using Doxywizard) that should identify the project for which the documentation is generated. This name is used in the title of most generated pages and in a few other places.
The default value is: <code>My Project</code>.
<a id="cfg_project_number"></a></dd>
<dt><code>PROJECT_NUMBER</code></dt>
<dd>The <code>PROJECT_NUMBER</code> tag can be used to enter a project or revision number. This could be handy for archiving the generated documentation or if some version control system is used.
<a id="cfg_project_brief"></a></dd>
<dt><code>PROJECT_BRIEF</code></dt>
<dd>Using the <code>PROJECT_BRIEF</code> tag one can provide an optional one line description for a project that appears at the top of each page and should give viewers a quick idea about the purpose of the project. Keep the description short.
<a id="cfg_project_logo"></a></dd>
<dt><code>PROJECT_LOGO</code></dt>
<dd>With the <code>PROJECT_LOGO</code> tag one can specify a logo or an icon that is included in the documentation. The maximum height of the logo should not exceed 55 pixels and the maximum width should not exceed 200 pixels. Doxygen will copy the logo to the output directory.
<a id="cfg_project_icon"></a></dd>
<dt><code>PROJECT_ICON</code></dt>
<dd>With the <code>PROJECT_ICON</code> tag one can specify an icon that is included in the tabs when the HTML document is shown. Doxygen will copy the logo to the output directory.
<a id="cfg_output_directory"></a></dd>
<dt><code>OUTPUT_DIRECTORY</code></dt>
<dd>The <code>OUTPUT_DIRECTORY</code> tag is used to specify the (relative or absolute) path into which the generated documentation will be written. If a relative path is entered, it will be relative to the location where Doxygen was started. If left blank the current directory will be used.
<a id="cfg_create_subdirs"></a></dd>
<dt><code>CREATE_SUBDIRS</code></dt>
<dd>If the <code>CREATE_SUBDIRS</code> tag is set to <code>YES</code> then Doxygen will create up to 4096 sub-directories (in 2 levels) under the output directory of each output format and will distribute the generated files over these directories. Enabling this option can be useful when feeding Doxygen a huge amount of source files, where putting all generated files in the same directory would otherwise cause performance problems for the file system. Adapt <code>CREATE_SUBDIRS_LEVEL</code> to control the number of sub-directories.
The default value is: <code>NO</code>.
<a id="cfg_create_subdirs_level"></a></dd>
<dt><code>CREATE_SUBDIRS_LEVEL</code></dt>
<dd>Controls the number of sub-directories that will be created when <code>CREATE_SUBDIRS</code> tag is set to <code>YES</code>. Level 0 represents 16 directories, and every level increment doubles the number of directories, resulting in 4096 directories at level 8 which is the default and also the maximum value. The sub-directories are organized in 2 levels, the first level always has a fixed number of 16 directories.
Minimum value: <code>0</code>, maximum value: <code>8</code>, default value: <code>8</code>.
This tag requires that the tag <a href="#cfg_create_subdirs">CREATE_SUBDIRS</a> is set to <code>YES</code>. <a id="cfg_allow_unicode_names"></a></dd>
<dt><code>ALLOW_UNICODE_NAMES</code></dt>
<dd>If the <code>ALLOW_UNICODE_NAMES</code> tag is set to <code>YES</code>, Doxygen will allow non-ASCII characters to appear in the names of generated files. If set to <code>NO</code>, non-ASCII characters will be escaped, for example _xE3_x81_x84 will be used for Unicode U+3044.
The default value is: <code>NO</code>.
<a id="cfg_output_language"></a></dd>
<dt><code>OUTPUT_LANGUAGE</code></dt>
<dd>The <code>OUTPUT_LANGUAGE</code> tag is used to specify the language in which all documentation generated by Doxygen is written. Doxygen will use this information to generate all constant output in the proper language.
Possible values are: <code>Afrikaans</code>, <code>Arabic</code>, <code>Armenian</code>, <code>Brazilian</code>, <code>Bulgarian</code>, <code>Catalan</code>, <code>Chinese</code>, <code>Chinese-Traditional</code>, <code>Croatian</code>, <code>Czech</code>, <code>Danish</code>, <code>Dutch</code>, <code>English</code> (United States), <code>Esperanto</code>, <code>Farsi</code> (Persian), <code>Finnish</code>, <code>French</code>, <code>German</code>, <code>Greek</code>, <code>Hindi</code>, <code>Hungarian</code>, <code>Indonesian</code>, <code>Italian</code>, <code>Japanese</code>, <code>Japanese-en</code> (Japanese with English messages), <code>Korean</code>, <code>Korean-en</code> (Korean with English messages), <code>Latvian</code>, <code>Lithuanian</code>, <code>Macedonian</code>, <code>Norwegian</code>, <code>Persian</code> (Farsi), <code>Polish</code>, <code>Portuguese</code>, <code>Romanian</code>, <code>Russian</code>, <code>Serbian</code>, <code>Serbian-Cyrillic</code>, <code>Slovak</code>, <code>Slovene</code>, <code>Spanish</code>, <code>Swedish</code>, <code>Turkish</code>, <code>Ukrainian</code> and <code>Vietnamese</code>.
The default value is: <code>English</code>.
<a id="cfg_brief_member_desc"></a></dd>
<dt><code>BRIEF_MEMBER_DESC</code></dt>
<dd>If the <code>BRIEF_MEMBER_DESC</code> tag is set to <code>YES</code>, Doxygen will include brief member descriptions after the members that are listed in the file and class documentation (similar to <code>Javadoc</code>). Set to <code>NO</code> to disable this.
The default value is: <code>YES</code>.
<a id="cfg_repeat_brief"></a></dd>
<dt><code>REPEAT_BRIEF</code></dt>
<dd>If the <code>REPEAT_BRIEF</code> tag is set to <code>YES</code>, Doxygen will prepend the brief description of a member or function before the detailed description 
<br/>
Note: If both <a href="#cfg_hide_undoc_members">HIDE_UNDOC_MEMBERS</a> and <a href="#cfg_brief_member_desc">BRIEF_MEMBER_DESC</a> are set to <code>NO</code>, the brief descriptions will be completely suppressed.
The default value is: <code>YES</code>.
<a id="cfg_abbreviate_brief"></a></dd>
<dt><code>ABBREVIATE_BRIEF</code></dt>
<dd>This tag implements a quasi-intelligent brief description abbreviator that is used to form the text in various listings. Each string in this list, if found as the leading text of the brief description, will be stripped from the text and the result, after processing the whole list, is used as the annotated text. Otherwise, the brief description is used as-is. If left blank, the following values are used (<code>$name</code> is automatically replaced with the name of the entity): <code>The $name class</code>, <code>The $name widget</code>, <code>The $name file</code>, <code>is</code>, <code>provides</code>, <code>specifies</code>, <code>contains</code>, <code>represents</code>, <code>a</code>, <code>an</code> and <code>the</code>.
<a id="cfg_always_detailed_sec"></a></dd>
<dt><code>ALWAYS_DETAILED_SEC</code></dt>
<dd>If the <code>ALWAYS_DETAILED_SEC</code> and <a href="#cfg_repeat_brief">REPEAT_BRIEF</a> tags are both set to <code>YES</code> then Doxygen will generate a detailed section even if there is only a brief description.
The default value is: <code>NO</code>.
<a id="cfg_inline_inherited_memb"></a></dd>
<dt><code>INLINE_INHERITED_MEMB</code></dt>
<dd>If the <code>INLINE_INHERITED_MEMB</code> tag is set to <code>YES</code>, Doxygen will show all inherited members of a class in the documentation of that class as if those members were ordinary class members. Constructors, destructors and assignment operators of the base classes will not be shown.
The default value is: <code>NO</code>.
<a id="cfg_full_path_names"></a></dd>
<dt><code>FULL_PATH_NAMES</code></dt>
<dd>If the <code>FULL_PATH_NAMES</code> tag is set to <code>YES</code>, Doxygen will prepend the full path before files name in the file list and in the header files. If set to <code>NO</code> the shortest path that makes the file name unique will be used
The default value is: <code>YES</code>.
<a id="cfg_strip_from_path"></a></dd>
<dt><code>STRIP_FROM_PATH</code></dt>
<dd>The <code>STRIP_FROM_PATH</code> tag can be used to strip a user-defined part of the path. Stripping is only done if one of the specified strings matches the left-hand part of the path. The tag can be used to show relative paths in the file list. If left blank the directory from which Doxygen is run is used as the path to strip. 
<br/>
Note that you can specify absolute paths here, but also relative paths, which will be relative from the directory where Doxygen is started.
This tag requires that the tag <a href="#cfg_full_path_names">FULL_PATH_NAMES</a> is set to <code>YES</code>. <a id="cfg_strip_from_inc_path"></a></dd>
<dt><code>STRIP_FROM_INC_PATH</code></dt>
<dd>The <code>STRIP_FROM_INC_PATH</code> tag can be used to strip a user-defined part of the path mentioned in the documentation of a class, which tells the reader which header file to include in order to use a class. If left blank only the name of the header file containing the class definition is used. Otherwise one should specify the list of include paths that are normally passed to the compiler using the <code>-I</code> flag.
<a id="cfg_short_names"></a></dd>
<dt><code>SHORT_NAMES</code></dt>
<dd>If the <code>SHORT_NAMES</code> tag is set to <code>YES</code>, Doxygen will generate much shorter (but less readable) file names. This can be useful if your file system doesn't support long names like on DOS, Mac, or CD-ROM.
The default value is: <code>NO</code>.
<a id="cfg_javadoc_autobrief"></a></dd>
<dt><code>JAVADOC_AUTOBRIEF</code></dt>
<dd>If the <code>JAVADOC_AUTOBRIEF</code> tag is set to <code>YES</code> then Doxygen will interpret the first line (until the first dot, question mark or exclamation mark) of a Javadoc-style comment as the brief description. If set to <code>NO</code>, the Javadoc-style will behave just like regular Qt-style comments (thus requiring an explicit <a href="/web-doxygen/docs/pages/commands/#cmdbrief">@brief</a> command for a brief description.)
The default value is: <code>NO</code>.
<a id="cfg_javadoc_banner"></a></dd>
<dt><code>JAVADOC_BANNER</code></dt>
<dd>If the <code>JAVADOC_BANNER</code> tag is set to <code>YES</code> then Doxygen will interpret a line such as
<pre><code>/***************
</code></pre>
as being the beginning of a Javadoc-style comment "banner". If set to <code>NO</code>, the Javadoc-style will behave just like regular comments and it will not be interpreted by Doxygen.
The default value is: <code>NO</code>.
<a id="cfg_qt_autobrief"></a></dd>
<dt><code>QT_AUTOBRIEF</code></dt>
<dd>If the <code>QT_AUTOBRIEF</code> tag is set to <code>YES</code> then Doxygen will interpret the first line (until the first dot, question mark or exclamation mark) of a Qt-style comment as the brief description. If set to <code>NO</code>, the Qt-style will behave just like regular Qt-style comments (thus requiring an explicit <a href="/web-doxygen/docs/pages/commands/#cmdbrief">\brief</a> command for a brief description.)
The default value is: <code>NO</code>.
<a id="cfg_multiline_cpp_is_brief"></a></dd>
<dt><code>MULTILINE_CPP_IS_BRIEF</code></dt>
<dd>The <code>MULTILINE_CPP_IS_BRIEF</code> tag can be set to <code>YES</code> to make Doxygen treat a multi-line C++ special comment block (i.e. a block of <code>//!</code> or <code>///</code> comments) as a brief description. This used to be the default behavior. The new default is to treat a multi-line C++ comment block as a detailed description. Set this tag to <code>YES</code> if you prefer the old behavior instead. 
<br/>
Note that setting this tag to <code>YES</code> also means that rational rose comments are not recognized any more.
The default value is: <code>NO</code>.
<a id="cfg_python_docstring"></a></dd>
<dt><code>PYTHON_DOCSTRING</code></dt>
<dd>By default Python docstrings are displayed as preformatted text and Doxygen's special commands cannot be used. By setting <code>PYTHON_DOCSTRING</code> to <code>NO</code> the Doxygen's special commands can be used and the contents of the docstring documentation blocks is shown as Doxygen documentation.
The default value is: <code>YES</code>.
<a id="cfg_inherit_docs"></a></dd>
<dt><code>INHERIT_DOCS</code></dt>
<dd>If the <code>INHERIT_DOCS</code> tag is set to <code>YES</code> then an undocumented member inherits the documentation from any documented member that it re-implements.
The default value is: <code>YES</code>.
<a id="cfg_separate_member_pages"></a></dd>
<dt><code>SEPARATE_MEMBER_PAGES</code></dt>
<dd>If the <code>SEPARATE_MEMBER_PAGES</code> tag is set to <code>YES</code> then Doxygen will produce a new page for each member. If set to <code>NO</code>, the documentation of a member will be part of the file/class/namespace that contains it.
The default value is: <code>NO</code>.
<a id="cfg_tab_size"></a></dd>
<dt><code>TAB_SIZE</code></dt>
<dd>The <code>TAB_SIZE</code> tag can be used to set the number of spaces in a tab. Doxygen uses this value to replace tabs by spaces in code fragments.
Minimum value: <code>1</code>, maximum value: <code>16</code>, default value: <code>4</code>.
<a id="cfg_aliases"></a></dd>
<dt><code>ALIASES</code></dt>
<dd>This tag can be used to specify a number of aliases that act as commands in the documentation. An alias has the form:
<pre><code> name=value
</code></pre>
For example adding
<pre><code> "sideeffect=@par Side Effects:^^"
</code></pre>
will allow you to put the command <code>\sideeffect</code> (or <code>@sideeffect</code>) in the documentation, which will result in a user-defined paragraph with heading "Side Effects:". Note that you cannot put <a href="/web-doxygen/docs/pages/commands/#cmdn">\n</a>'s in the value part of an alias to insert newlines (in the resulting output). You can put <code>^^</code> in the value part of an alias to insert a newline as if a physical newline was in the original file. When you need a literal <code>{</code> or <code>}</code> or <code>,</code> in the value part of an alias you have to escape them by means of a backslash (<code>\</code>), this can lead to conflicts with the commands <code>\{</code> and <code>\}</code> for these it is advised to use the version <code>@{</code> and <code>@}</code> or use a double escape (<code>\\{</code> and <code>\\}</code>)
<a id="cfg_optimize_output_for_c"></a></dd>
<dt><code>OPTIMIZE_OUTPUT_FOR_C</code></dt>
<dd>Set the <code>OPTIMIZE_OUTPUT_FOR_C</code> tag to <code>YES</code> if your project consists of C sources only. Doxygen will then generate output that is more tailored for C. For instance, some of the names that are used will be different. The list of all members will be omitted, etc.
The default value is: <code>NO</code>.
<a id="cfg_optimize_output_java"></a></dd>
<dt><code>OPTIMIZE_OUTPUT_JAVA</code></dt>
<dd>Set the <code>OPTIMIZE_OUTPUT_JAVA</code> tag to <code>YES</code> if your project consists of Java or Python sources only. Doxygen will then generate output that is more tailored for that language. For instance, namespaces will be presented as packages, qualified scopes will look different, etc.
The default value is: <code>NO</code>.
<a id="cfg_optimize_for_fortran"></a></dd>
<dt><code>OPTIMIZE_FOR_FORTRAN</code></dt>
<dd>Set the <code>OPTIMIZE_FOR_FORTRAN</code> tag to <code>YES</code> if your project consists of Fortran sources. Doxygen will then generate output that is tailored for Fortran.
The default value is: <code>NO</code>.
<a id="cfg_optimize_output_vhdl"></a></dd>
<dt><code>OPTIMIZE_OUTPUT_VHDL</code></dt>
<dd>Set the <code>OPTIMIZE_OUTPUT_VHDL</code> tag to <code>YES</code> if your project consists of VHDL sources. Doxygen will then generate output that is tailored for VHDL.
The default value is: <code>NO</code>.
<a id="cfg_optimize_output_slice"></a></dd>
<dt><code>OPTIMIZE_OUTPUT_SLICE</code></dt>
<dd>Set the <code>OPTIMIZE_OUTPUT_SLICE</code> tag to <code>YES</code> if your project consists of Slice sources only. Doxygen will then generate output that is more tailored for that language. For instance, namespaces will be presented as modules, types will be separated into more groups, etc.
The default value is: <code>NO</code>.
<a id="cfg_extension_mapping"></a></dd>
<dt><code>EXTENSION_MAPPING</code></dt>
<dd>Doxygen selects the parser to use depending on the extension of the files it parses. With this tag you can assign which parser to use for a given extension. Doxygen has a built-in mapping, but you can override or extend it using this tag. The format is <code>ext=language</code>, where <code>ext</code> is a file extension, and language is one of the parsers supported by Doxygen: IDL, Java, JavaScript, Csharp (C#), C, C++, Lex, D, PHP, md (Markdown), Objective-C, Python, Slice, VHDL, Fortran (fixed format Fortran: FortranFixed, free formatted Fortran: FortranFree, unknown formatted Fortran: Fortran. In the later case the parser tries to guess whether the code is fixed or free formatted code, this is the default for Fortran type files).
For instance to make Doxygen treat <code>.inc</code> files as Fortran files (default is PHP), and <code>.f</code> files as C (default is Fortran), use: <code>inc=Fortran f=C</code>.
<br/>
Note: For files without extension you can use <code>no_extension</code> as a placeholder. 
<br/>
Note that for custom extensions you also need to set <a href="#cfg_file_patterns">FILE_PATTERNS</a> otherwise the files are not read by Doxygen. When specifying <code>no_extension</code> you should add <code>*</code> to the <a href="#cfg_file_patterns">FILE_PATTERNS</a>. 
<br/>
Note see also the list of <a href="/web-doxygen/docs/pages/starting/#default_file_extension_mapping">default file extension mappings</a>.
<a id="cfg_markdown_support"></a></dd>
<dt><code>MARKDOWN_SUPPORT</code></dt>
<dd>If the <code>MARKDOWN_SUPPORT</code> tag is enabled then Doxygen pre-processes all comments according to the Markdown format, which allows for more readable documentation. See <a href="https://daringfireball.net/projects/markdown/">https://daringfireball.net/projects/markdown/</a> for details. The output of markdown processing is further processed by Doxygen, so you can mix Doxygen, HTML, and XML commands with Markdown formatting. Disable only in case of backward compatibilities issues.
The default value is: <code>YES</code>.
<a id="cfg_toc_include_headings"></a></dd>
<dt><code>TOC_INCLUDE_HEADINGS</code></dt>
<dd>When the <code>TOC_INCLUDE_HEADINGS</code> tag is set to a non-zero value, all headings up to that level are automatically included in the table of contents, even if they do not have an id attribute.
:::info
This feature currently applies only to Markdown headings.
:::
Minimum value: <code>0</code>, maximum value: <code>99</code>, default value: <code>6</code>.
This tag requires that the tag <a href="#cfg_markdown_support">MARKDOWN_SUPPORT</a> is set to <code>YES</code>. <a id="cfg_markdown_id_style"></a></dd>
<dt><code>MARKDOWN_ID_STYLE</code></dt>
<dd>The <code>MARKDOWN_ID_STYLE</code> tag can be used to specify the algorithm used to generate identifiers for the Markdown headings. Note: Every identifier is unique.
Possible values are: <code>DOXYGEN</code> use a fixed 'autotoc_md' string followed by a sequence number starting at 0 and <code>GITHUB</code> use the lower case version of title with any whitespace replaced by '-' and punctuation characters removed.
The default value is: <code>DOXYGEN</code>.
This tag requires that the tag <a href="#cfg_markdown_support">MARKDOWN_SUPPORT</a> is set to <code>YES</code>. <a id="cfg_autolink_support"></a></dd>
<dt><code>AUTOLINK_SUPPORT</code></dt>
<dd>When enabled Doxygen tries to link words that correspond to documented classes, or namespaces to their corresponding documentation. Such a link can be prevented in individual cases by putting a <code>%</code> sign in front of the word or globally by setting <code>AUTOLINK_SUPPORT</code> to <code>NO</code>. Words listed in the <code>AUTOLINK_IGNORE_WORDS</code> tag are excluded from automatic linking.
The default value is: <code>YES</code>.
<a id="cfg_autolink_ignore_words"></a></dd>
<dt><code>AUTOLINK_IGNORE_WORDS</code></dt>
<dd>This tag specifies a list of words that, when matching the start of a word in the documentation, will suppress auto links generation, if it is enabled via AUTOLINK_SUPPORT. This list does not affect links explicitly created using # or the <a href="/web-doxygen/docs/pages/commands/#cmdlink">\link</a> or <a href="/web-doxygen/docs/pages/commands/#cmdref">\ref</a> commands.
This tag requires that the tag <a href="#cfg_autolink_support">AUTOLINK_SUPPORT</a> is set to <code>YES</code>. <a id="cfg_builtin_stl_support"></a></dd>
<dt><code>BUILTIN_STL_SUPPORT</code></dt>
<dd>If you use STL classes (i.e. <code>std::string</code>, <code>std::vector</code>, etc.) but do not want to include (a tag file for) the STL sources as input, then you should set this tag to <code>YES</code> in order to let Doxygen match functions declarations and definitions whose arguments contain STL classes (e.g. <code>func(std::string</code>); versus <code>func(std::string) {}</code>). This also makes the inheritance and collaboration diagrams that involve STL classes more complete and accurate.
The default value is: <code>NO</code>.
<a id="cfg_cpp_cli_support"></a></dd>
<dt><code>CPP_CLI_SUPPORT</code></dt>
<dd>If you use Microsoft's C++/CLI language, you should set this option to <code>YES</code> to enable parsing support.
The default value is: <code>NO</code>.
<a id="cfg_sip_support"></a></dd>
<dt><code>SIP_SUPPORT</code></dt>
<dd>Set the <code>SIP_SUPPORT</code> tag to <code>YES</code> if your project consists of <a href="https://www.riverbankcomputing.com/software">sip</a> sources only. Doxygen will parse them like normal C++ but will assume all classes use public instead of private inheritance when no explicit protection keyword is present.
The default value is: <code>NO</code>.
<a id="cfg_idl_property_support"></a></dd>
<dt><code>IDL_PROPERTY_SUPPORT</code></dt>
<dd>For Microsoft's IDL there are <code>propget</code> and <code>propput</code> attributes to indicate getter and setter methods for a property. Setting this option to <code>YES</code> will make Doxygen to replace the get and set methods by a property in the documentation. This will only work if the methods are indeed getting or setting a simple type. If this is not the case, or you want to show the methods anyway, you should set this option to <code>NO</code>.
The default value is: <code>YES</code>.
<a id="cfg_distribute_group_doc"></a></dd>
<dt><code>DISTRIBUTE_GROUP_DOC</code></dt>
<dd>If member grouping is used in the documentation and the <code>DISTRIBUTE_GROUP_DOC</code> tag is set to <code>YES</code> then Doxygen will reuse the documentation of the first member in the group (if any) for the other members of the group. By default all members of a group must be documented explicitly.
The default value is: <code>NO</code>.
<a id="cfg_group_nested_compounds"></a></dd>
<dt><code>GROUP_NESTED_COMPOUNDS</code></dt>
<dd>If one adds a struct or class to a group and this option is enabled, then also any nested class or struct is added to the same group. By default this option is disabled and one has to add nested compounds explicitly via <a href="/web-doxygen/docs/pages/commands/#cmdingroup">\ingroup</a>.
The default value is: <code>NO</code>.
<a id="cfg_subgrouping"></a></dd>
<dt><code>SUBGROUPING</code></dt>
<dd>Set the <code>SUBGROUPING</code> tag to <code>YES</code> to allow class member groups of the same type (for instance a group of public functions) to be put as a subgroup of that type (e.g. under the Public Functions section). Set it to <code>NO</code> to prevent subgrouping. Alternatively, this can be done per class using the <a href="/web-doxygen/docs/pages/commands/#cmdnosubgrouping">\nosubgrouping</a> command.
The default value is: <code>YES</code>.
<a id="cfg_inline_grouped_classes"></a></dd>
<dt><code>INLINE_GROUPED_CLASSES</code></dt>
<dd>When the <code>INLINE_GROUPED_CLASSES</code> tag is set to <code>YES</code>, classes, structs and unions are shown inside the group in which they are included (e.g. using <a href="/web-doxygen/docs/pages/commands/#cmdingroup">\ingroup</a>) instead of on a separate page (for HTML and Man pages) or section (for <code>$\mbox{\LaTeX}$</code> and RTF). 
<br/>
Note that this feature does not work in combination with <a href="#cfg_separate_member_pages">SEPARATE_MEMBER_PAGES</a>.
The default value is: <code>NO</code>.
<a id="cfg_inline_simple_structs"></a></dd>
<dt><code>INLINE_SIMPLE_STRUCTS</code></dt>
<dd>When the <code>INLINE_SIMPLE_STRUCTS</code> tag is set to <code>YES</code>, structs, classes, and unions with only public data fields or simple typedef fields will be shown inline in the documentation of the scope in which they are defined (i.e. file, namespace, or group documentation), provided this scope is documented. If set to <code>NO</code>, structs, classes, and unions are shown on a separate page (for HTML and Man pages) or section (for <code>$\mbox{\LaTeX}$</code> and RTF).
The default value is: <code>NO</code>.
<a id="cfg_typedef_hides_struct"></a></dd>
<dt><code>TYPEDEF_HIDES_STRUCT</code></dt>
<dd>When <code>TYPEDEF_HIDES_STRUCT</code> tag is enabled, a typedef of a struct, union, or enum is documented as struct, union, or enum with the name of the typedef. So <code>typedef struct TypeS {} TypeT</code>, will appear in the documentation as a struct with name <code>TypeT</code>. When disabled the typedef will appear as a member of a file, namespace, or class. And the struct will be named <code>TypeS</code>. This can typically be useful for C code in case the coding convention dictates that all compound types are typedef'ed and only the typedef is referenced, never the tag name.
The default value is: <code>NO</code>.
<a id="cfg_lookup_cache_size"></a></dd>
<dt><code>LOOKUP_CACHE_SIZE</code></dt>
<dd>The size of the symbol lookup cache can be set using <code>LOOKUP_CACHE_SIZE</code>. This cache is used to resolve symbols given their name and scope. Since this can be an expensive process and often the same symbol appears multiple times in the code, Doxygen keeps a cache of pre-resolved symbols. If the cache is too small Doxygen will become slower. If the cache is too large, memory is wasted. The cache size is given by this formula: <code>$2^{(16+\mbox{LOOKUP\_CACHE\_SIZE})}$</code>. The valid range is 0..9, the default is 0, corresponding to a cache size of <code>$2^{16} = 65536$</code> symbols. At the end of a run Doxygen will report the cache usage and suggest the optimal cache size from a speed point of view.
Minimum value: <code>0</code>, maximum value: <code>9</code>, default value: <code>0</code>.
<a id="cfg_num_proc_threads"></a></dd>
<dt><code>NUM_PROC_THREADS</code></dt>
<dd>The <code>NUM_PROC_THREADS</code> specifies the number of threads Doxygen is allowed to use during processing. When set to <code>0</code> Doxygen will based this on the number of cores available in the system. You can set it explicitly to a value larger than 0 to get more control over the balance between CPU load and processing speed. At this moment only the input processing can be done using multiple threads. Since this is still an experimental feature the default is set to 1, which effectively disables parallel processing. Please report any issues you encounter. Generating dot graphs in parallel is controlled by the <code>DOT_NUM_THREADS</code> setting.
Minimum value: <code>0</code>, maximum value: <code>32</code>, default value: <code>1</code>.
<a id="cfg_timestamp"></a></dd>
<dt><code>TIMESTAMP</code></dt>
<dd>If the <code>TIMESTAMP</code> tag is set different from <code>NO</code> then each generated page will contain the date or date and time when the page was generated. Setting this to <code>NO</code> can help when comparing the output of multiple runs.
Possible values are: <code>YES</code>, <code>NO</code>, <code>DATETIME</code> and <code>DATE</code>.
The default value is: <code>NO</code>.</dd>
</dl>

## Build related configuration options {#config_build}


<a id="cfg_extract_all"></a>

<dl class="doxyVariableList">
<dt><code>EXTRACT_ALL</code></dt>
<dd>If the <code>EXTRACT_ALL</code> tag is set to <code>YES</code>, Doxygen will assume all entities in documentation are documented, even if no documentation was available. Private class members and static file members will be hidden unless the <a href="#cfg_extract_private">EXTRACT_PRIVATE</a> respectively <a href="#cfg_extract_static">EXTRACT_STATIC</a> tags are set to <code>YES</code>.
:::info
This will also disable the warnings about undocumented members that are normally produced when <a href="#cfg_warnings">WARNINGS</a> is set to <code>YES</code>.
:::
The default value is: <code>NO</code>.
<a id="cfg_extract_private"></a></dd>
<dt><code>EXTRACT_PRIVATE</code></dt>
<dd>If the <code>EXTRACT_PRIVATE</code> tag is set to <code>YES</code>, all private members of a class will be included in the documentation.
The default value is: <code>NO</code>.
<a id="cfg_extract_priv_virtual"></a></dd>
<dt><code>EXTRACT_PRIV_VIRTUAL</code></dt>
<dd>If the <code>EXTRACT_PRIV_VIRTUAL</code> tag is set to <code>YES</code>, documented private virtual methods of a class will be included in the documentation.
The default value is: <code>NO</code>.
<a id="cfg_extract_package"></a></dd>
<dt><code>EXTRACT_PACKAGE</code></dt>
<dd>If the <code>EXTRACT_PACKAGE</code> tag is set to <code>YES</code>, all members with package or internal scope will be included in the documentation.
The default value is: <code>NO</code>.
<a id="cfg_extract_static"></a></dd>
<dt><code>EXTRACT_STATIC</code></dt>
<dd>If the <code>EXTRACT_STATIC</code> tag is set to <code>YES</code>, all static members of a file will be included in the documentation.
The default value is: <code>NO</code>.
<a id="cfg_extract_local_classes"></a></dd>
<dt><code>EXTRACT_LOCAL_CLASSES</code></dt>
<dd>If the <code>EXTRACT_LOCAL_CLASSES</code> tag is set to <code>YES</code>, classes (and structs) defined locally in source files will be included in the documentation. If set to <code>NO</code>, only classes defined in header files are included. Does not have any effect for Java sources.
The default value is: <code>YES</code>.
<a id="cfg_extract_local_methods"></a></dd>
<dt><code>EXTRACT_LOCAL_METHODS</code></dt>
<dd>This flag is only useful for Objective-C code. If set to <code>YES</code>, local methods, which are defined in the implementation section but not in the interface are included in the documentation. If set to <code>NO</code>, only methods in the interface are included.
The default value is: <code>NO</code>.
<a id="cfg_extract_anon_nspaces"></a></dd>
<dt><code>EXTRACT_ANON_NSPACES</code></dt>
<dd>If this flag is set to <code>YES</code>, the members of anonymous namespaces will be extracted and appear in the documentation as a namespace called 'anonymous_namespace{file}', where file will be replaced with the base name of the file that contains the anonymous namespace. By default anonymous namespace are hidden.
The default value is: <code>NO</code>.
<a id="cfg_resolve_unnamed_params"></a></dd>
<dt><code>RESOLVE_UNNAMED_PARAMS</code></dt>
<dd>If this flag is set to <code>YES</code>, the name of an unnamed parameter in a declaration will be determined by the corresponding definition. By default unnamed parameters remain unnamed in the output.
The default value is: <code>YES</code>.
<a id="cfg_hide_undoc_members"></a></dd>
<dt><code>HIDE_UNDOC_MEMBERS</code></dt>
<dd>If the <code>HIDE_UNDOC_MEMBERS</code> tag is set to <code>YES</code>, Doxygen will hide all undocumented members inside documented classes or files. If set to <code>NO</code> these members will be included in the various overviews, but no documentation section is generated. This option has no effect if <a href="#cfg_extract_all">EXTRACT_ALL</a> is enabled.
The default value is: <code>NO</code>.
<a id="cfg_hide_undoc_classes"></a></dd>
<dt><code>HIDE_UNDOC_CLASSES</code></dt>
<dd>If the <code>HIDE_UNDOC_CLASSES</code> tag is set to <code>YES</code>, Doxygen will hide all undocumented classes that are normally visible in the class hierarchy. If set to <code>NO</code>, these classes will be included in the various overviews. This option will also hide undocumented C++ concepts if enabled. This option has no effect if <a href="#cfg_extract_all">EXTRACT_ALL</a> is enabled.
The default value is: <code>NO</code>.
<a id="cfg_hide_undoc_namespaces"></a></dd>
<dt><code>HIDE_UNDOC_NAMESPACES</code></dt>
<dd>If the <code>HIDE_UNDOC_NAMESPACES</code> tag is set to <code>YES</code>, Doxygen will hide all undocumented namespaces that are normally visible in the namespace hierarchy. If set to <code>NO</code>, these namespaces will be included in the various overviews. This option has no effect if <a href="#cfg_extract_all">EXTRACT_ALL</a> is enabled.
The default value is: <code>YES</code>.
<a id="cfg_hide_friend_compounds"></a></dd>
<dt><code>HIDE_FRIEND_COMPOUNDS</code></dt>
<dd>If the <code>HIDE_FRIEND_COMPOUNDS</code> tag is set to <code>YES</code>, Doxygen will hide all friend declarations. If set to <code>NO</code>, these declarations will be included in the documentation.
The default value is: <code>NO</code>.
<a id="cfg_hide_in_body_docs"></a></dd>
<dt><code>HIDE_IN_BODY_DOCS</code></dt>
<dd>If the <code>HIDE_IN_BODY_DOCS</code> tag is set to <code>YES</code>, Doxygen will hide any documentation blocks found inside the body of a function. If set to <code>NO</code>, these blocks will be appended to the function's detailed documentation block.
The default value is: <code>NO</code>.
<a id="cfg_internal_docs"></a></dd>
<dt><code>INTERNAL_DOCS</code></dt>
<dd>The <code>INTERNAL_DOCS</code> tag determines if documentation that is typed after a <a href="/web-doxygen/docs/pages/commands/#cmdinternal">\internal</a> command is included. If the tag is set to <code>NO</code> then the documentation will be excluded. Set it to <code>YES</code> to include the internal documentation.
The default value is: <code>NO</code>.
<a id="cfg_case_sense_names"></a></dd>
<dt><code>CASE_SENSE_NAMES</code></dt>
<dd>With the correct setting of option <code>CASE_SENSE_NAMES</code> Doxygen will better be able to match the capabilities of the underlying filesystem.
In case the filesystem is case sensitive (i.e. it supports files in the same directory whose names only differ in casing), the option must be set to <code>YES</code> to properly deal with such files in case they appear in the input.
For filesystems that are not case sensitive the option should be set to <code>NO</code> to properly deal with output files written for symbols that only differ in casing, such as for two classes, one named <code>CLASS</code> and the other named <code>Class</code>, and to also support references to files without having to specify the exact matching casing.
On Windows (including Cygwin) and macOS, users should typically set this option to <code>NO</code>, whereas on Linux or other Unix flavors it should typically be set to <code>YES</code>.
Possible values are: <code>SYSTEM</code>, <code>NO</code> and <code>YES</code>.
The default value is: <code>SYSTEM</code>.
<a id="cfg_hide_scope_names"></a></dd>
<dt><code>HIDE_SCOPE_NAMES</code></dt>
<dd>If the <code>HIDE_SCOPE_NAMES</code> tag is set to <code>NO</code> then Doxygen will show members with their full class and namespace scopes in the documentation. If set to <code>YES</code>, the scope will be hidden.
The default value is: <code>NO</code>.
<a id="cfg_hide_compound_reference"></a></dd>
<dt><code>HIDE_COMPOUND_REFERENCE</code></dt>
<dd>If the <code>HIDE_COMPOUND_REFERENCE</code> tag is set to <code>NO</code> (default) then Doxygen will append additional text to a page's title, such as Class Reference. If set to <code>YES</code> the compound reference will be hidden.
The default value is: <code>NO</code>.
<a id="cfg_show_headerfile"></a></dd>
<dt><code>SHOW_HEADERFILE</code></dt>
<dd>If the <code>SHOW_HEADERFILE</code> tag is set to <code>YES</code> then the documentation for a class will show which file needs to be included to use the class.
The default value is: <code>YES</code>.
<a id="cfg_show_include_files"></a></dd>
<dt><code>SHOW_INCLUDE_FILES</code></dt>
<dd>If the <code>SHOW_INCLUDE_FILES</code> tag is set to <code>YES</code> then Doxygen will put a list of the files that are included by a file in the documentation of that file.
The default value is: <code>YES</code>.
<a id="cfg_show_grouped_memb_inc"></a></dd>
<dt><code>SHOW_GROUPED_MEMB_INC</code></dt>
<dd>If the <code>SHOW_GROUPED_MEMB_INC</code> tag is set to <code>YES</code> then Doxygen will add for each grouped member an include statement to the documentation, telling the reader which file to include in order to use the member.
The default value is: <code>NO</code>.
<a id="cfg_force_local_includes"></a></dd>
<dt><code>FORCE_LOCAL_INCLUDES</code></dt>
<dd>If the <code>FORCE_LOCAL_INCLUDES</code> tag is set to <code>YES</code> then Doxygen will list include files with double quotes in the documentation rather than with sharp brackets.
The default value is: <code>NO</code>.
<a id="cfg_inline_info"></a></dd>
<dt><code>INLINE_INFO</code></dt>
<dd>If the <code>INLINE_INFO</code> tag is set to <code>YES</code> then a tag [inline] is inserted in the documentation for inline members.
The default value is: <code>YES</code>.
<a id="cfg_sort_member_docs"></a></dd>
<dt><code>SORT_MEMBER_DOCS</code></dt>
<dd>If the <code>SORT_MEMBER_DOCS</code> tag is set to <code>YES</code> then Doxygen will sort the (detailed) documentation of file and class members alphabetically by member name. If set to <code>NO</code>, the members will appear in declaration order.
The default value is: <code>YES</code>.
<a id="cfg_sort_brief_docs"></a></dd>
<dt><code>SORT_BRIEF_DOCS</code></dt>
<dd>If the <code>SORT_BRIEF_DOCS</code> tag is set to <code>YES</code> then Doxygen will sort the brief descriptions of file, namespace and class members alphabetically by member name. If set to <code>NO</code>, the members will appear in declaration order. Note that this will also influence the order of the classes in the class list.
The default value is: <code>NO</code>.
<a id="st"></a></dd>
<dt><code>SORT_MEMBERS_CTORS_1ST</code></dt>
<dd>If the <code>SORT_MEMBERS_CTORS_1ST</code> tag is set to <code>YES</code> then Doxygen will sort the (brief and detailed) documentation of class members so that constructors and destructors are listed first. If set to <code>NO</code> the constructors will appear in the respective orders defined by <a href="#cfg_sort_brief_docs">SORT_BRIEF_DOCS</a> and <a href="#cfg_sort_member_docs">SORT_MEMBER_DOCS</a>.
:::info
If <a href="#cfg_sort_brief_docs">SORT\_BRIEF\_DOCS</a> is set to <code>NO</code> this option is ignored for sorting brief member documentation.
:::
:::info
If <a href="#cfg_sort_member_docs">SORT\_MEMBER\_DOCS</a> is set to <code>NO</code> this option is ignored for sorting detailed member documentation.
:::
The default value is: <code>NO</code>.
<a id="cfg_sort_group_names"></a></dd>
<dt><code>SORT_GROUP_NAMES</code></dt>
<dd>If the <code>SORT_GROUP_NAMES</code> tag is set to <code>YES</code> then Doxygen will sort the hierarchy of group names into alphabetical order. If set to <code>NO</code> the group names will appear in their defined order.
The default value is: <code>NO</code>.
<a id="cfg_sort_by_scope_name"></a></dd>
<dt><code>SORT_BY_SCOPE_NAME</code></dt>
<dd>If the <code>SORT_BY_SCOPE_NAME</code> tag is set to <code>YES</code>, the class list will be sorted by fully-qualified names, including namespaces. If set to <code>NO</code>, the class list will be sorted only by class name, not including the namespace part.
:::info
This option is not very useful if <a href="#cfg_hide_scope_names">HIDE\_SCOPE\_NAMES</a> is set to <code>YES</code>.
:::
:::info
This option applies only to the class list, not to the alphabetical list.
:::
The default value is: <code>NO</code>.
<a id="cfg_strict_proto_matching"></a></dd>
<dt><code>STRICT_PROTO_MATCHING</code></dt>
<dd>If the <code>STRICT_PROTO_MATCHING</code> option is enabled and Doxygen fails to do proper type resolution of all parameters of a function it will reject a match between the prototype and the implementation of a member function even if there is only one candidate or it is obvious which candidate to choose by doing a simple string match. By disabling <code>STRICT_PROTO_MATCHING</code> Doxygen will still accept a match between prototype and implementation in such cases.
The default value is: <code>NO</code>.
<a id="cfg_generate_todolist"></a></dd>
<dt><code>GENERATE_TODOLIST</code></dt>
<dd>The <code>GENERATE_TODOLIST</code> tag can be used to enable (<code>YES</code>) or disable (<code>NO</code>) the todo list. This list is created by putting <a href="/web-doxygen/docs/pages/commands/#cmdtodo">\todo</a> commands in the documentation.
The default value is: <code>YES</code>.
<a id="cfg_generate_testlist"></a></dd>
<dt><code>GENERATE_TESTLIST</code></dt>
<dd>The <code>GENERATE_TESTLIST</code> tag can be used to enable (<code>YES</code>) or disable (<code>NO</code>) the test list. This list is created by putting <a href="/web-doxygen/docs/pages/commands/#cmdtest">\test</a> commands in the documentation.
The default value is: <code>YES</code>.
<a id="cfg_generate_buglist"></a></dd>
<dt><code>GENERATE_BUGLIST</code></dt>
<dd>The <code>GENERATE_BUGLIST</code> tag can be used to enable (<code>YES</code>) or disable (<code>NO</code>) the bug list. This list is created by putting <a href="/web-doxygen/docs/pages/commands/#cmdbug">\bug</a> commands in the documentation.
The default value is: <code>YES</code>.
<a id="cfg_generate_deprecatedlist"></a></dd>
<dt><code>GENERATE_DEPRECATEDLIST</code></dt>
<dd>The <code>GENERATE_DEPRECATEDLIST</code> tag can be used to enable (<code>YES</code>) or disable (<code>NO</code>) the deprecated list. This list is created by putting <a href="/web-doxygen/docs/pages/commands/#cmddeprecated">\deprecated</a> commands in the documentation.
The default value is: <code>YES</code>.
<a id="cfg_enabled_sections"></a></dd>
<dt><code>ENABLED_SECTIONS</code></dt>
<dd>The <code>ENABLED_SECTIONS</code> tag can be used to enable conditional documentation sections, marked by <a href="/web-doxygen/docs/pages/commands/#cmdif">\if</a> &lt;section_label&gt; ... <a href="/web-doxygen/docs/pages/commands/#cmdendif">\endif</a> and <a href="/web-doxygen/docs/pages/commands/#cmdcond">\cond</a> &lt;section_label&gt; ... <a href="/web-doxygen/docs/pages/commands/#cmdendcond">\endcond</a> blocks.
<a id="cfg_max_initializer_lines"></a></dd>
<dt><code>MAX_INITIALIZER_LINES</code></dt>
<dd>The <code>MAX_INITIALIZER_LINES</code> tag determines the maximum number of lines that the initial value of a variable or macro / define can have for it to appear in the documentation. If the initializer consists of more lines than specified here it will be hidden. Use a value of 0 to hide initializers completely. The appearance of the value of individual variables and macros / defines can be controlled using <a href="/web-doxygen/docs/pages/commands/#cmdshowinitializer">\showinitializer</a> or <a href="/web-doxygen/docs/pages/commands/#cmdhideinitializer">\hideinitializer</a> command in the documentation regardless of this setting.
Minimum value: <code>0</code>, maximum value: <code>10000</code>, default value: <code>30</code>.
<a id="cfg_show_used_files"></a></dd>
<dt><code>SHOW_USED_FILES</code></dt>
<dd>Set the <code>SHOW_USED_FILES</code> tag to <code>NO</code> to disable the list of files generated at the bottom of the documentation of classes and structs. If set to <code>YES</code>, the list will mention the files that were used to generate the documentation.
The default value is: <code>YES</code>.
<a id="cfg_show_files"></a></dd>
<dt><code>SHOW_FILES</code></dt>
<dd>Set the <code>SHOW_FILES</code> tag to <code>NO</code> to disable the generation of the Files page. This will remove the Files entry from the Quick Index and from the Folder Tree View (if specified).
The default value is: <code>YES</code>.
<a id="cfg_show_namespaces"></a></dd>
<dt><code>SHOW_NAMESPACES</code></dt>
<dd>Set the <code>SHOW_NAMESPACES</code> tag to <code>NO</code> to disable the generation of the Namespaces page. This will remove the Namespaces entry from the Quick Index and from the Folder Tree View (if specified).
The default value is: <code>YES</code>.
<a id="cfg_file_version_filter"></a></dd>
<dt><code>FILE_VERSION_FILTER</code></dt>
<dd>The <code>FILE_VERSION_FILTER</code> tag can be used to specify a program or script that Doxygen should invoke to get the current version for each file (typically from the version control system). Doxygen will invoke the program by executing (via <code>popen()</code>) the command <code>command input-file</code>, where <code>command</code> is the value of the <code>FILE_VERSION_FILTER</code> tag, and <code>input-file</code> is the name of an input file provided by Doxygen. Whatever the program writes to standard output is used as the file version.
<br/>
<br/>
 Example of using a shell script as a filter for Unix:
<pre><code> FILE_VERSION_FILTER = "/bin/sh versionfilter.sh"
</code></pre>
<br/>
 Example shell script for CVS:
<pre><code>#!/bin/sh
cvs status $1 | sed -n 's/^[ \]*Working revision:[ \t]*\([0-9][0-9\.]*\).*/\1/p'
</code></pre>
<br/>
 Example shell script for Subversion:
<pre><code>#!/bin/sh
svn stat -v $1 | sed -n 's/^[ A-Z?\*|!]\{1,15\}/r/;s/ \{1,15\}/\/r/;s/ .*//p'
</code></pre>
<br/>
 Example filter for ClearCase:
<pre><code>FILE_VERSION_FILTER = "cleartool desc -fmt \%Vn"
</code></pre>
<a id="cfg_layout_file"></a></dd>
<dt><code>LAYOUT_FILE</code></dt>
<dd>The <code>LAYOUT_FILE</code> tag can be used to specify a layout file which will be parsed by Doxygen. The layout file controls the global structure of the generated output files in an output format independent way. To create the layout file that represents Doxygen's defaults, run Doxygen with the <code>-l</code> option. You can optionally specify a file name after the option, if omitted <code>DoxygenLayout.xml</code> will be used as the name of the layout file. See also section <a href="/web-doxygen/docs/pages/customize/#layout">Changing the layout of pages</a> for information. 
<br/>
Note that if you run Doxygen from a directory containing a file called <code>DoxygenLayout.xml</code>, Doxygen will parse it automatically even if the <code>LAYOUT_FILE</code> tag is left empty.
<a id="cfg_cite_bib_files"></a></dd>
<dt><code>CITE_BIB_FILES</code></dt>
<dd>The <code>CITE_BIB_FILES</code> tag can be used to specify one or more <code>bib</code> files containing the reference definitions. This must be a list of <code>.bib</code> files. The <code>.bib</code> extension is automatically appended if omitted. This requires the <code>bibtex</code> tool to be installed. See also <a href="https://en.wikipedia.org/wiki/BibTeX">https://en.wikipedia.org/wiki/BibTeX</a> for more info. For <code>$\mbox{\LaTeX}$</code> the style of the bibliography can be controlled using <a href="#cfg_latex_bib_style">LATEX_BIB_STYLE</a>. To use this feature you need <code>bibtex</code> and <code>perl</code> available in the search path. See also <a href="/web-doxygen/docs/pages/commands/#cmdcite">\cite</a> for info how to create references.
<a id="cfg_external_tool_path"></a></dd>
<dt><code>EXTERNAL_TOOL_PATH</code></dt>
<dd>The <code>EXTERNAL_TOOL_PATH</code> tag can be used to extend the search path (PATH environment variable) so that external tools such as <code>latex</code> and <code>gs</code> can be found.
:::info
Directories specified with EXTERNAL\_TOOL\_PATH are added in front of the path already specified by the PATH variable, and are added in the order specified.
:::
:::info
This option is particularly useful for macOS version 14 (Sonoma) and higher, when running Doxygen from Doxywizard, because in this case any user-defined changes to the PATH are ignored. A typical example on macOS is to set
<pre><code>EXTERNAL_TOOL_PATH = /Library/TeX/texbin /usr/local/bin
</code></pre>
together with the standard path, the full search path used by doxygen when launching external tools will then become
<pre><code>PATH=/Library/TeX/texbin:/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin
</code></pre>
:::</dd>
</dl>

## Configuration options related to warning and progress messages {#config_messages}


<a id="cfg_quiet"></a>

<dl class="doxyVariableList">
<dt><code>QUIET</code></dt>
<dd>The <code>QUIET</code> tag can be used to turn on/off the messages that are generated to standard output by Doxygen. If <code>QUIET</code> is set to <code>YES</code> this implies that the messages are off.
The default value is: <code>NO</code>.
<a id="cfg_warnings"></a></dd>
<dt><code>WARNINGS</code></dt>
<dd>The <code>WARNINGS</code> tag can be used to turn on/off the warning messages that are generated to standard error (<code>stderr</code>) by Doxygen. If <code>WARNINGS</code> is set to <code>YES</code> this implies that the warnings are on. 
<br/>
 <b>Tip:</b> Turn warnings on while writing the documentation.
The default value is: <code>YES</code>.
<a id="cfg_warn_if_undocumented"></a></dd>
<dt><code>WARN_IF_UNDOCUMENTED</code></dt>
<dd>If the <code>WARN_IF_UNDOCUMENTED</code> tag is set to <code>YES</code> then Doxygen will generate warnings for undocumented members. If <a href="#cfg_extract_all">EXTRACT_ALL</a> is set to <code>YES</code> then this flag will automatically be disabled.
The default value is: <code>YES</code>.
<a id="cfg_warn_if_doc_error"></a></dd>
<dt><code>WARN_IF_DOC_ERROR</code></dt>
<dd>If the <code>WARN_IF_DOC_ERROR</code> tag is set to <code>YES</code>, Doxygen will generate warnings for potential errors in the documentation, such as documenting some parameters in a documented function twice, or documenting parameters that don't exist or using markup commands wrongly.
The default value is: <code>YES</code>.
<a id="cfg_warn_if_incomplete_doc"></a></dd>
<dt><code>WARN_IF_INCOMPLETE_DOC</code></dt>
<dd>If <code>WARN_IF_INCOMPLETE_DOC</code> is set to <code>YES</code>, Doxygen will warn about incomplete function parameter documentation. If set to <code>NO</code>, Doxygen will accept that some parameters have no documentation without warning.
The default value is: <code>YES</code>.
<a id="cfg_warn_no_paramdoc"></a></dd>
<dt><code>WARN_NO_PARAMDOC</code></dt>
<dd>This <code>WARN_NO_PARAMDOC</code> option can be enabled to get warnings for functions that are documented, but have no documentation for their parameters or return value. If set to <code>NO</code>, Doxygen will only warn about wrong parameter documentation, but not about the absence of documentation. If <a href="#cfg_extract_all">EXTRACT_ALL</a> is set to <code>YES</code> then this flag will automatically be disabled. See also <a href="#cfg_warn_if_incomplete_doc">WARN_IF_INCOMPLETE_DOC</a>
The default value is: <code>NO</code>.
<a id="cfg_warn_if_undoc_enum_val"></a></dd>
<dt><code>WARN_IF_UNDOC_ENUM_VAL</code></dt>
<dd>If <code>WARN_IF_UNDOC_ENUM_VAL</code> option is set to <code>YES</code>, Doxygen will warn about undocumented enumeration values. If set to <code>NO</code>, Doxygen will accept undocumented enumeration values. If <a href="#cfg_extract_all">EXTRACT_ALL</a> is set to <code>YES</code> then this flag will automatically be disabled.
The default value is: <code>NO</code>.
<a id="cfg_warn_layout_file"></a></dd>
<dt><code>WARN_LAYOUT_FILE</code></dt>
<dd>If <code>WARN_LAYOUT_FILE</code> option is set to <code>YES</code>, Doxygen will warn about issues found while parsing the user defined layout file, such as missing or wrong elements. See also <a href="#cfg_layout_file">LAYOUT_FILE</a> for details. If set to <code>NO</code>, problems with the layout file will be suppressed.
The default value is: <code>YES</code>.
<a id="cfg_warn_as_error"></a></dd>
<dt><code>WARN_AS_ERROR</code></dt>
<dd>If the <code>WARN_AS_ERROR</code> tag is set to <code>YES</code> then Doxygen will immediately stop when a warning is encountered. If the <code>WARN_AS_ERROR</code> tag is set to <code>FAIL_ON_WARNINGS</code> then Doxygen will continue running as if <code>WARN_AS_ERROR</code> tag is set to <code>NO</code>, but at the end of the Doxygen process Doxygen will return with a non-zero status. If the <code>WARN_AS_ERROR</code> tag is set to <code>FAIL_ON_WARNINGS_PRINT</code> then Doxygen behaves like <code>FAIL_ON_WARNINGS</code> but in case no <a href="#cfg_warn_logfile">WARN_LOGFILE</a> is defined Doxygen will not write the warning messages in between other messages but write them at the end of a run, in case a <a href="#cfg_warn_logfile">WARN_LOGFILE</a> is defined the warning messages will be besides being in the defined file also be shown at the end of a run, unless the <a href="#cfg_warn_logfile">WARN_LOGFILE</a> is defined as <code>-</code> i.e. standard output (<code>stdout</code>) in that case the behavior will remain as with the setting <code>FAIL_ON_WARNINGS</code>.
Possible values are: <code>NO</code>, <code>YES</code>, <code>FAIL_ON_WARNINGS</code> and <code>FAIL_ON_WARNINGS_PRINT</code>.
The default value is: <code>NO</code>.
<a id="cfg_warn_format"></a></dd>
<dt><code>WARN_FORMAT</code></dt>
<dd>The <code>WARN_FORMAT</code> tag determines the format of the warning messages that Doxygen can produce. The string should contain the <code>$file</code>, <code>$line</code>, and <code>$text</code> tags, which will be replaced by the file and line number from which the warning originated and the warning text. Optionally the format may contain <code>$version</code>, which will be replaced by the version of the file (if it could be obtained via <a href="#cfg_file_version_filter">FILE_VERSION_FILTER</a>)
<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><a href="#cfg_warn_line_format">WARN_LINE_FORMAT</a></dd>
</dl>
The default value is: <code>$file:$line: $text</code>.
<a id="cfg_warn_line_format"></a></dd>
<dt><code>WARN_LINE_FORMAT</code></dt>
<dd>In the <code>$text</code> part of the <a href="#cfg_warn_format">WARN_FORMAT</a> command it is possible that a reference to a more specific place is given. To make it easier to jump to this place (outside of Doxygen) the user can define a custom "cut" / "paste" string.
Example:
<pre><code>  WARN_LINE_FORMAT = "'vi $file +$line'"
</code></pre>
<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><a href="#cfg_warn_format">WARN_FORMAT</a></dd>
</dl>
The default value is: <code>at line $line of file $file</code>.
<a id="cfg_warn_logfile"></a></dd>
<dt><code>WARN_LOGFILE</code></dt>
<dd>The <code>WARN_LOGFILE</code> tag can be used to specify a file to which warning and error messages should be written. If left blank the output is written to standard error (<code>stderr</code>). In case the file specified cannot be opened for writing the warning and error messages are written to standard error. When as file <code>-</code> is specified the warning and error messages are written to standard output (<code>stdout</code>).</dd>
</dl>

## Configuration options related to the input files {#config_input}


<a id="cfg_input"></a>

<dl class="doxyVariableList">
<dt><code>INPUT</code></dt>
<dd>The <code>INPUT</code> tag is used to specify the files and/or directories that contain documented source files. You may enter file names like <code>myfile.cpp</code> or directories like <code>/usr/src/myproject</code>. Separate the files or directories with spaces. See also <a href="#cfg_file_patterns">FILE_PATTERNS</a> and <a href="#cfg_extension_mapping">EXTENSION_MAPPING</a>
:::info
If this tag is empty the current directory is searched.
:::
<a id="cfg_input_encoding"></a></dd>
<dt><code>INPUT_ENCODING</code></dt>
<dd>This tag can be used to specify the character encoding of the source files that Doxygen parses. Internally Doxygen uses the UTF-8 encoding. Doxygen uses <code>libiconv</code> (or the <code>iconv</code> built into <code>libc</code>) for the transcoding. See <a href="https://www.gnu.org/software/libiconv/">the libiconv documentation</a> for the list of possible encodings.
<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><a href="#cfg_input_file_encoding">INPUT_FILE_ENCODING</a></dd>
</dl>
The default value is: <code>UTF-8</code>.
<a id="cfg_input_file_encoding"></a></dd>
<dt><code>INPUT_FILE_ENCODING</code></dt>
<dd>This tag can be used to specify the character encoding of the source files that Doxygen parses. The <code>INPUT_FILE_ENCODING</code> tag can be used to specify character encoding on a per file pattern basis. Doxygen will compare the file name with each pattern and apply the encoding instead of the default <a href="#cfg_input_encoding">INPUT_ENCODING</a> if there is a match. The character encodings are a list of the form: pattern=encoding (like <code>*.php=ISO-8859-1</code>).
<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><a href="#cfg_input_encoding">INPUT_ENCODING</a> for further information on supported encodings.</dd>
</dl>
<a id="cfg_file_patterns"></a></dd>
<dt><code>FILE_PATTERNS</code></dt>
<dd>If the value of the <a href="#cfg_input">INPUT</a> tag contains directories, you can use the <code>FILE_PATTERNS</code> tag to specify one or more wildcard patterns (like <code>*.cpp</code> and <code>*.h</code>) to filter out the source-files in the directories.
<br/>
 Note that for custom extensions or not directly supported extensions you also need to set <a href="#cfg_extension_mapping">EXTENSION_MAPPING</a> for the extension otherwise the files are not read by Doxygen.
<br/>
 Note the list of default checked file patterns might differ from the list of <a href="/web-doxygen/docs/pages/starting/#default_file_extension_mapping">default file extension mappings</a>.
<br/>
 If left blank the following patterns are tested: <code>*.c</code>, <code>*.cc</code>, <code>*.cxx</code>, <code>*.cxxm</code>, <code>*.cpp</code>, <code>*.cppm</code>, <code>*.ccm</code>, <code>*.c++</code>, <code>*.c++m</code>, <code>*.java</code>, <code>*.ii</code>, <code>*.ixx</code>, <code>*.ipp</code>, <code>*.i++</code>, <code>*.inl</code>, <code>*.idl</code>, <code>*.ddl</code>, <code>*.odl</code>, <code>*.h</code>, <code>*.hh</code>, <code>*.hxx</code>, <code>*.hpp</code>, <code>*.h++</code>, <code>*.l</code>, <code>*.cs</code>, <code>*.d</code>, <code>*.php</code>, <code>*.php4</code>, <code>*.php5</code>, <code>*.phtml</code>, <code>*.inc</code>, <code>*.m</code>, <code>*.markdown</code>, <code>*.md</code>, <code>*.mm</code>, <code>*.dox</code> (to be provided as Doxygen C comment), <code>*.py</code>, <code>*.pyw</code>, <code>*.f90</code>, <code>*.f95</code>, <code>*.f03</code>, <code>*.f08</code>, <code>*.f18</code>, <code>*.f</code>, <code>*.for</code>, <code>*.vhd</code>, <code>*.vhdl</code>, <code>*.ucf</code>, <code>*.qsf</code> and <code>*.ice</code>.
<a id="cfg_recursive"></a></dd>
<dt><code>RECURSIVE</code></dt>
<dd>The <code>RECURSIVE</code> tag can be used to specify whether or not subdirectories should be searched for input files as well.
The default value is: <code>NO</code>.
<a id="cfg_exclude"></a></dd>
<dt><code>EXCLUDE</code></dt>
<dd>The <code>EXCLUDE</code> tag can be used to specify files and/or directories that should be excluded from the <a href="#cfg_input">INPUT</a> source files. This way you can easily exclude a subdirectory from a directory tree whose root is specified with the <a href="#cfg_input">INPUT</a> tag. 
<br/>
Note that relative paths are relative to the directory from which Doxygen is run.
<a id="cfg_exclude_symlinks"></a></dd>
<dt><code>EXCLUDE_SYMLINKS</code></dt>
<dd>The <code>EXCLUDE_SYMLINKS</code> tag can be used to select whether or not files or directories that are symbolic links (a Unix file system feature) are excluded from the input.
The default value is: <code>NO</code>.
<a id="cfg_exclude_patterns"></a></dd>
<dt><code>EXCLUDE_PATTERNS</code></dt>
<dd>If the value of the <a href="#cfg_input">INPUT</a> tag contains directories, you can use the <code>EXCLUDE_PATTERNS</code> tag to specify one or more wildcard patterns to exclude certain files from those directories. 
<br/>
Note that the wildcards are matched against the file with absolute path, so to exclude all test directories for example use the pattern <code>*</code><code>/test/</code><code>*</code>
<a id="cfg_exclude_symbols"></a></dd>
<dt><code>EXCLUDE_SYMBOLS</code></dt>
<dd>The <code>EXCLUDE_SYMBOLS</code> tag can be used to specify one or more symbol names (namespaces, classes, functions, etc.) that should be excluded from the output. The symbol name can be a fully qualified name, a word, or if the wildcard <code>*</code> is used, a substring. Examples: <code>ANamespace</code>, <code>AClass</code>, <code>ANamespace::AClass</code>, <code>ANamespace::*Test</code>
<a id="cfg_example_path"></a></dd>
<dt><code>EXAMPLE_PATH</code></dt>
<dd>The <code>EXAMPLE_PATH</code> tag can be used to specify one or more files or directories that contain example code fragments that are included (see the <a href="/web-doxygen/docs/pages/commands/#cmdinclude">\include</a> command).
<a id="cfg_example_patterns"></a></dd>
<dt><code>EXAMPLE_PATTERNS</code></dt>
<dd>If the value of the <a href="#cfg_example_path">EXAMPLE_PATH</a> tag contains directories, you can use the <code>EXAMPLE_PATTERNS</code> tag to specify one or more wildcard pattern (like <code>*.cpp</code> and <code>*.h</code>) to filter out the source-files in the directories. If left blank all files are included.
<a id="cfg_example_recursive"></a></dd>
<dt><code>EXAMPLE_RECURSIVE</code></dt>
<dd>If the <code>EXAMPLE_RECURSIVE</code> tag is set to <code>YES</code> then subdirectories will be searched for input files to be used with the <a href="/web-doxygen/docs/pages/commands/#cmdinclude">\include</a> or <a href="/web-doxygen/docs/pages/commands/#cmddontinclude">\dontinclude</a> commands irrespective of the value of the <a href="#cfg_recursive">RECURSIVE</a> tag.
The default value is: <code>NO</code>.
<a id="cfg_image_path"></a></dd>
<dt><code>IMAGE_PATH</code></dt>
<dd>The <code>IMAGE_PATH</code> tag can be used to specify one or more files or directories that contain images that are to be included in the documentation (see the <a href="/web-doxygen/docs/pages/commands/#cmdimage">\image</a> command).
<a id="cfg_input_filter"></a></dd>
<dt><code>INPUT_FILTER</code></dt>
<dd>The <code>INPUT_FILTER</code> tag can be used to specify a program that Doxygen should invoke to filter for each input file. Doxygen will invoke the filter program by executing (via <code>popen()</code>) the command: 
<br/>
 <code>&lt;filter&gt; &lt;input-file&gt;</code> 
<br/>
 where <code>&lt;filter&gt;</code> is the value of the <code>INPUT_FILTER</code> tag, and <code>&lt;input-file&gt;</code> is the name of an input file. Doxygen will then use the output that the filter program writes to standard output. If <a href="#cfg_filter_patterns">FILTER_PATTERNS</a> is specified, this tag will be ignored. 
<br/>
Note that the filter must not add or remove lines; it is applied before the code is scanned, but not when the output code is generated. If lines are added or removed, the anchors will not be placed correctly. 
<br/>
Note that Doxygen will use the data processed and written to standard output for further processing, therefore nothing else, like debug statements or used commands (so in case of a Windows batch file always use <code>@echo OFF</code>), should be written to standard output. 
<br/>
Note that for custom extensions or not directly supported extensions you also need to set <a href="#cfg_extension_mapping">EXTENSION_MAPPING</a> for the extension otherwise the files are not properly processed by Doxygen.
<br/>
<a id="cfg_filter_patterns"></a></dd>
<dt><code>FILTER_PATTERNS</code></dt>
<dd>The <code>FILTER_PATTERNS</code> tag can be used to specify filters on a per file pattern basis. Doxygen will compare the file name with each pattern and apply the filter if there is a match. The filters are a list of the form: pattern=filter (like <code>*.cpp=my_cpp_filter</code>). See <a href="#cfg_input_filter">INPUT_FILTER</a> for further information on how filters are used. If the <code>FILTER_PATTERNS</code> tag is empty or if none of the patterns match the file name, <a href="#cfg_input_filter">INPUT_FILTER</a> is applied. 
<br/>
Note that for custom extensions or not directly supported extensions you also need to set <a href="#cfg_extension_mapping">EXTENSION_MAPPING</a> for the extension otherwise the files are not properly processed by Doxygen.
<br/>
<a id="cfg_filter_source_files"></a></dd>
<dt><code>FILTER_SOURCE_FILES</code></dt>
<dd>If the <code>FILTER_SOURCE_FILES</code> tag is set to <code>YES</code>, the input filter (if set using <a href="#cfg_input_filter">INPUT_FILTER</a>) will also be used to filter the input files that are used for producing the source files to browse (i.e. when <a href="#cfg_source_browser">SOURCE_BROWSER</a> is set to <code>YES</code>).
The default value is: <code>NO</code>.
<a id="cfg_filter_source_patterns"></a></dd>
<dt><code>FILTER_SOURCE_PATTERNS</code></dt>
<dd>The <code>FILTER_SOURCE_PATTERNS</code> tag can be used to specify source filters per file pattern. A pattern will override the setting for <a href="#cfg_filter_patterns">FILTER_PATTERN</a> (if any) and it is also possible to disable source filtering for a specific pattern using <code>*.ext=</code> (so without naming a filter).
This tag requires that the tag <a href="#cfg_filter_source_files">FILTER_SOURCE_FILES</a> is set to <code>YES</code>. <a id="cfg_use_mdfile_as_mainpage"></a></dd>
<dt><code>USE_MDFILE_AS_MAINPAGE</code></dt>
<dd>If the <code>USE_MDFILE_AS_MAINPAGE</code> tag refers to the name of a markdown file that is part of the input, its contents will be placed on the main page (<code>index.html</code>). This can be useful if you have a project on for instance GitHub and want to reuse the introduction page also for the Doxygen output.
<a id="cfg_implicit_dir_docs"></a></dd>
<dt><code>IMPLICIT_DIR_DOCS</code></dt>
<dd>If the <code>IMPLICIT_DIR_DOCS</code> tag is set to <code>YES</code>, any <code>README.md</code> file found in sub-directories of the project's root, is used as the documentation for that sub-directory, except when the <code>README.md</code> starts with a <a href="/web-doxygen/docs/pages/commands/#cmddir">\dir</a>, <a href="/web-doxygen/docs/pages/commands/#cmdpage">\page</a> or <a href="/web-doxygen/docs/pages/commands/#cmdmainpage">\mainpage</a> command. If set to <code>NO</code>, the <code>README.md</code> file needs to start with an explicit <a href="/web-doxygen/docs/pages/commands/#cmddir">\dir</a> command in order to be used as directory documentation.
The default value is: <code>YES</code>.
<a id="cfg_fortran_comment_after"></a></dd>
<dt><code>FORTRAN_COMMENT_AFTER</code></dt>
<dd>The Fortran standard specifies that for fixed formatted Fortran code all characters from position 72 are to be considered as comment. A common extension is to allow longer lines before the automatic comment starts. The setting <code>FORTRAN_COMMENT_AFTER</code> will also make it possible that longer lines can be processed before the automatic comment starts.
Minimum value: <code>7</code>, maximum value: <code>10000</code>, default value: <code>72</code>.</dd>
</dl>

## Configuration options related to source browsing {#config_source_browser}


<a id="cfg_source_browser"></a>

<dl class="doxyVariableList">
<dt><code>SOURCE_BROWSER</code></dt>
<dd>If the <code>SOURCE_BROWSER</code> tag is set to <code>YES</code> then a list of source files will be generated. Documented entities will be cross-referenced with these sources. 
<br/>
Note: To get rid of all source code in the generated output, make sure that also <a href="#cfg_verbatim_headers">VERBATIM_HEADERS</a> is set to <code>NO</code>.
The default value is: <code>NO</code>.
<a id="cfg_inline_sources"></a></dd>
<dt><code>INLINE_SOURCES</code></dt>
<dd>Setting the <code>INLINE_SOURCES</code> tag to <code>YES</code> will include the body of functions, multi-line macros, enums or list initialized variables directly into the documentation.
The default value is: <code>NO</code>.
<a id="cfg_strip_code_comments"></a></dd>
<dt><code>STRIP_CODE_COMMENTS</code></dt>
<dd>Setting the <code>STRIP_CODE_COMMENTS</code> tag to <code>YES</code> will instruct Doxygen to hide any special comment blocks from generated source code fragments. Normal C, C++ and Fortran comments will always remain visible.
The default value is: <code>YES</code>.
<a id="cfg_referenced_by_relation"></a></dd>
<dt><code>REFERENCED_BY_RELATION</code></dt>
<dd>If the <code>REFERENCED_BY_RELATION</code> tag is set to <code>YES</code> then for each documented entity all documented functions referencing it will be listed.
The default value is: <code>NO</code>.
<a id="cfg_references_relation"></a></dd>
<dt><code>REFERENCES_RELATION</code></dt>
<dd>If the <code>REFERENCES_RELATION</code> tag is set to <code>YES</code> then for each documented function all documented entities called/used by that function will be listed.
The default value is: <code>NO</code>.
<a id="cfg_references_link_source"></a></dd>
<dt><code>REFERENCES_LINK_SOURCE</code></dt>
<dd>If the <code>REFERENCES_LINK_SOURCE</code> tag is set to <code>YES</code> and <a href="#cfg_source_browser">SOURCE_BROWSER</a> tag is set to <code>YES</code> then the hyperlinks from functions in <a href="#cfg_references_relation">REFERENCES_RELATION</a> and <a href="#cfg_referenced_by_relation">REFERENCED_BY_RELATION</a> lists will link to the source code. Otherwise they will link to the documentation.
The default value is: <code>YES</code>.
<a id="cfg_source_tooltips"></a></dd>
<dt><code>SOURCE_TOOLTIPS</code></dt>
<dd>If <code>SOURCE_TOOLTIPS</code> is enabled (the default) then hovering a hyperlink in the source code will show a tooltip with additional information such as prototype, brief description and links to the definition and documentation. Since this will make the HTML file larger and loading of large files a bit slower, you can opt to disable this feature.
The default value is: <code>YES</code>.
This tag requires that the tag <a href="#cfg_source_browser">SOURCE_BROWSER</a> is set to <code>YES</code>. <a id="cfg_use_htags"></a></dd>
<dt><code>USE_HTAGS</code></dt>
<dd>If the <code>USE_HTAGS</code> tag is set to <code>YES</code> then the references to source code will point to the HTML generated by the <code>htags(1)</code> tool instead of Doxygen built-in source browser. The <code>htags</code> tool is part of GNU's global source tagging system (see <a href="https://www.gnu.org/software/global/global.html">https://www.gnu.org/software/global/global.html</a>). You will need version 4.8.6 or higher. 
<br/>
 To use it do the following:
<ol class="doxyList" type="1">
<li>Install the latest version of <code>global</code></li>
<li>Enable <a href="#cfg_source_browser">SOURCE_BROWSER</a> and <code>USE_HTAGS</code> in the configuration file</li>
<li>Make sure the <a href="#cfg_input">INPUT</a> points to the root of the source tree</li>
<li>Run <code>doxygen</code> as normal 
<br/>
 Doxygen will invoke <code>htags</code> (and that will in turn invoke <code>gtags</code>), so these tools must be available from the command line (i.e. in the search path). 
<br/>
 The result: instead of the source browser generated by Doxygen, the links to source code will now point to the output of <code>htags</code>.</li>
</ol>
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_source_browser">SOURCE_BROWSER</a> is set to <code>YES</code>. <a id="cfg_verbatim_headers"></a></dd>
<dt><code>VERBATIM_HEADERS</code></dt>
<dd>If the <code>VERBATIM_HEADERS</code> tag is set the <code>YES</code> then Doxygen will generate a verbatim copy of the header file for each class for which an include is specified. Set to <code>NO</code> to disable this.
<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>Section <a href="/web-doxygen/docs/pages/commands/#cmdclass">\class</a>.</dd>
</dl>
The default value is: <code>YES</code>.
<a id="cfg_clang_assisted_parsing"></a></dd>
<dt><code>CLANG_ASSISTED_PARSING</code></dt>
<dd>If the <code>CLANG_ASSISTED_PARSING</code> tag is set to <code>YES</code> then Doxygen will use the <a href="http://clang.llvm.org/">clang parser</a> for more accurate parsing at the cost of reduced performance. This can be particularly helpful with template rich C++ code for which Doxygen's built-in parser lacks the necessary type information.
:::info
The availability of this option depends on whether or not Doxygen was generated with the <code>-Duse\_libclang=ON</code> option for CMake.
:::
The default value is: <code>NO</code>.
<a id="cfg_clang_add_inc_paths"></a></dd>
<dt><code>CLANG_ADD_INC_PATHS</code></dt>
<dd>If the <code>CLANG_ASSISTED_PARSING</code> tag is set to <code>YES</code> and the <code>CLANG_ADD_INC_PATHS</code> tag is set to <code>YES</code> then Doxygen will add the directory of each input to the include path.
The default value is: <code>YES</code>.
This tag requires that the tag <a href="#cfg_clang_assisted_parsing">CLANG_ASSISTED_PARSING</a> is set to <code>YES</code>. <a id="cfg_clang_options"></a></dd>
<dt><code>CLANG_OPTIONS</code></dt>
<dd>If clang assisted parsing is enabled you can provide the compiler with command line options that you would normally use when invoking the compiler. Note that the include paths will already be set by Doxygen for the files and directories specified with <a href="#cfg_input">INPUT</a> and <a href="#cfg_include_path">INCLUDE_PATH</a>.
This tag requires that the tag <a href="#cfg_clang_assisted_parsing">CLANG_ASSISTED_PARSING</a> is set to <code>YES</code>. <a id="cfg_clang_database_path"></a></dd>
<dt><code>CLANG_DATABASE_PATH</code></dt>
<dd>If clang assisted parsing is enabled you can provide the clang parser with the path to the directory containing a file called <code>compile_commands.json</code>. This file is the <a href="http://clang.llvm.org/docs/HowToSetupToolingForLLVM.html">compilation database</a> containing the options used when the source files were built. This is equivalent to specifying the <code>-p</code> option to a clang tool, such as <code>clang-check</code>. These options will then be passed to the parser. Any options specified with <a href="#cfg_clang_options">CLANG_OPTIONS</a> will be added as well.
:::info
The availability of this option depends on whether or not Doxygen was generated with the <code>-Duse\_libclang=ON</code> option for CMake.
:::</dd>
</dl>

## Configuration options related to the alphabetical class index {#config_index}


<a id="cfg_alphabetical_index"></a>

<dl class="doxyVariableList">
<dt><code>ALPHABETICAL_INDEX</code></dt>
<dd>If the <code>ALPHABETICAL_INDEX</code> tag is set to <code>YES</code>, an alphabetical index of all compounds will be generated. Enable this if the project contains a lot of classes, structs, unions or interfaces.
The default value is: <code>YES</code>.
<a id="cfg_ignore_prefix"></a></dd>
<dt><code>IGNORE_PREFIX</code></dt>
<dd>The <code>IGNORE_PREFIX</code> tag can be used to specify a prefix (or a list of prefixes) that should be ignored while generating the index headers. The <code>IGNORE_PREFIX</code> tag works for classes, function and member names. The entity will be placed in the alphabetical list under the first letter of the entity name that remains after removing the prefix.
This tag requires that the tag <a href="#cfg_alphabetical_index">ALPHABETICAL_INDEX</a> is set to <code>YES</code>.</dd>
</dl>

## Configuration options related to the HTML output {#config_html}


<a id="cfg_generate_html"></a>

<dl class="doxyVariableList">
<dt><code>GENERATE_HTML</code></dt>
<dd>If the <code>GENERATE_HTML</code> tag is set to <code>YES</code>, Doxygen will generate HTML output
The default value is: <code>YES</code>.
<a id="cfg_html_output"></a></dd>
<dt><code>HTML_OUTPUT</code></dt>
<dd>The <code>HTML_OUTPUT</code> tag is used to specify where the HTML docs will be put. If a relative path is entered the value of <a href="#cfg_output_directory">OUTPUT_DIRECTORY</a> will be put in front of it.
The default directory is: <code>html</code>.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_html_file_extension"></a></dd>
<dt><code>HTML_FILE_EXTENSION</code></dt>
<dd>The <code>HTML_FILE_EXTENSION</code> tag can be used to specify the file extension for each generated HTML page (for example: <code>.htm, .php, .asp</code>).
The default value is: <code>.html</code>.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_html_header"></a></dd>
<dt><code>HTML_HEADER</code></dt>
<dd>The <code>HTML_HEADER</code> tag can be used to specify a user-defined HTML header file for each generated HTML page. If the tag is left blank Doxygen will generate a standard header. 
<br/>
 To get valid HTML the header file that includes any scripts and style sheets that Doxygen needs, which is dependent on the configuration options used (e.g. the setting <a href="#cfg_generate_treeview">GENERATE_TREEVIEW</a>). It is highly recommended to start with a default header using
<pre><code>doxygen -w html new_header.html new_footer.html new_stylesheet.css YourConfigFile
</code></pre>
and then modify the file <code>new_header.html</code>.
See also section <a href="/web-doxygen/docs/pages/doxygen-usage">Doxygen usage</a> for information on how to generate the default header that Doxygen normally uses.
:::info
The header is subject to change so you typically have to regenerate the default header when upgrading to a newer version of Doxygen. The following markers have a special meaning inside the header and footer:
<dl class="doxyVariableList">
<dt><code>$title</code></dt>
<dd>will be replaced with the title of the page.</dd>
<dt><code>$datetime</code></dt>
<dd>will be replaced with the current date and time.</dd>
<dt><code>$date</code></dt>
<dd>will be replaced with the current date.</dd>
<dt><code>$time</code></dt>
<dd>will be replaced with the current time.</dd>
<dt><code>$year</code></dt>
<dd>will be replaces with the current year.</dd>
<dt><code>$showdate(&lt;format&gt;)</code></dt>
<dd>will be replaced with the current date and time according to the format as specified by <code>&lt;format&gt;</code>. The <code>&lt;format&gt;</code> follows the rules as specified for the <a href="/web-doxygen/docs/pages/commands/#cmdshowdate">\showdate</a> command with the exception that no <code>)</code> is allowed in the <code>&lt;format&gt;</code>.</dd>
<dt><code>$doxygenversion</code></dt>
<dd>will be replaced with the version of Doxygen</dd>
<dt><code>$projectname</code></dt>
<dd>will be replaced with the name of the project (see <a href="#cfg_project_name">PROJECT_NAME</a>)</dd>
<dt><code>$projectnumber</code></dt>
<dd>will be replaced with the project number (see <a href="#cfg_project_number">PROJECT_NUMBER</a>)</dd>
<dt><code>$projectbrief</code></dt>
<dd>will be replaced with the project brief description (see <a href="#cfg_project_brief">PROJECT_BRIEF</a>)</dd>
<dt><code>$projectlogo</code></dt>
<dd>will be replaced with the project logo (see <a href="#cfg_project_logo">PROJECT_LOGO</a>)</dd>
<dt><code>$generatedby</code></dt>
<dd>will be replaced with the output language dependent version of the text "Generated by" or when the <a href="#cfg_timestamp">TIMESTAMP</a> is set by the output language dependent version of the text "Generated on <code>$datetime</code> for <code>$projectname</code> by".</dd>
<dt><code>$stylesheet</code></dt>
<dd>will be replaced with the setting of <a href="#cfg_html_stylesheet">HTML_STYLESHEET</a> unless it is empty or the file in which case it is replaced by the default setting <code>doxygen.css</code>.</dd>
<dt><code>$extrastylesheet</code></dt>
<dd>will be replaced with the setting of <a href="#cfg_html_extra_stylesheet">HTML_EXTRA_STYLESHEET</a> including the required HTML tags for each extra stylesheet.</dd>
<dt><code>$treeview</code></dt>
<dd>will be replaced with links to the JavaScript and style sheets needed for the navigation tree (or an empty string when <a href="#cfg_generate_treeview">GENERATE_TREEVIEW</a> is disabled).</dd>
<dt><code>$search</code></dt>
<dd>will be replaced with a links to the JavaScript and style sheets needed for the search engine (or an empty string when <a href="#cfg_searchengine">SEARCHENGINE</a> is disabled).</dd>
<dt><code>$searchbox</code></dt>
<dd>will be replaced with the HTML code needed for the search box to be shown (or an empty string when <a href="#cfg_searchengine">SEARCHENGINE</a> is disabled).</dd>
<dt><code>$mathjax</code></dt>
<dd>will be replaced with a links to the JavaScript and style sheets needed for the MathJax feature (or an empty string when <a href="#cfg_use_mathjax">USE_MATHJAX</a> is disabled).</dd>
<dt><code>$relpath^</code></dt>
<dd>If <a href="#cfg_create_subdirs">CREATE_SUBDIRS</a> is enabled, the command <code>$relpath^</code> can be used to produce a relative path to the root of the HTML output directory, e.g. use <code>$relpath^doxygen.css</code>, to refer to the standard style sheet.</dd>
<dt><code>$navpath</code></dt>
<dd>will be replaced with a path as required by <a href="#cfg_generate_treeview">GENERATE_TREEVIEW</a></dd>
</dl>
:::
To cope with differences in the layout of the header and footer that depend on configuration settings, the header can also contain special blocks that will be copied to the output or skipped depending on the configuration. Such blocks have the following form:
<pre><code> &lt;!--BEGIN BLOCKNAME--&gt;
 Some context copied when condition BLOCKNAME holds
 &lt;!--END BLOCKNAME--&gt;
 &lt;!--BEGIN !BLOCKNAME--&gt;
 Some context copied when condition BLOCKNAME does not hold
 &lt;!--END !BLOCKNAME--&gt;
</code></pre>
The following block names are supported:
<dl class="doxyVariableList">
<dt><code>DISABLE_INDEX</code></dt>
<dd>Content within this block is copied to the output if the <a href="#cfg_disable_index">DISABLE_INDEX</a> option is enabled (so when the index is disabled).</dd>
<dt><code>GENERATE_TREEVIEW</code></dt>
<dd>Content within this block is copied to the output if the <a href="#cfg_generate_treeview">GENERATE_TREEVIEW</a> option is enabled.</dd>
<dt><code>SEARCHENGINE</code></dt>
<dd>Content within this block is copied to the output if the <a href="#cfg_searchengine">SEARCHENGINE</a> option is enabled.</dd>
<dt><code>PROJECT_NAME</code></dt>
<dd>Content within the block is copied to the output if the <a href="#cfg_project_name">PROJECT_NAME</a> option is not empty.</dd>
<dt><code>PROJECT_NUMBER</code></dt>
<dd>Content within the block is copied to the output if the <a href="#cfg_project_number">PROJECT_NUMBER</a> option is not empty.</dd>
<dt><code>PROJECT_BRIEF</code></dt>
<dd>Content within the block is copied to the output if the <a href="#cfg_project_brief">PROJECT_BRIEF</a> option is not empty.</dd>
<dt><code>PROJECT_LOGO</code></dt>
<dd>Content within the block is copied to the output if the <a href="#cfg_project_logo">PROJECT_LOGO</a> option is not empty.</dd>
<dt><code>FULL_SIDEBAR</code></dt>
<dd>Content within the block is copied to the output if the <a href="#cfg_full_sidebar">FULL_SIDEBAR</a>, <a href="#cfg_disable_index">DISABLE_INDEX</a> and <a href="#cfg_generate_treeview">GENERATE_TREEVIEW</a> options are all enabled.</dd>
<dt><code>TITLEAREA</code></dt>
<dd>Content within this block is copied to the output if a title is visible at the top of each page. This is the case if either <a href="#cfg_project_name">PROJECT_NAME</a>, <a href="#cfg_project_brief">PROJECT_BRIEF</a>, <a href="#cfg_project_logo">PROJECT_LOGO</a> is filled in or if both <a href="#cfg_disable_index">DISABLE_INDEX</a> and <a href="#cfg_searchengine">SEARCHENGINE</a> are enabled.</dd>
</dl>
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_html_footer"></a></dd>
<dt><code>HTML_FOOTER</code></dt>
<dd>The <code>HTML_FOOTER</code> tag can be used to specify a user-defined HTML footer for each generated HTML page. If the tag is left blank Doxygen will generate a standard footer.
See <a href="#cfg_html_header">HTML_HEADER</a> for more information on how to generate a default footer and what special commands can be used inside the footer.
See also section <a href="/web-doxygen/docs/pages/doxygen-usage">Doxygen usage</a> for information on how to generate the default footer that Doxygen normally uses.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_html_stylesheet"></a></dd>
<dt><code>HTML_STYLESHEET</code></dt>
<dd>The <code>HTML_STYLESHEET</code> tag can be used to specify a user-defined cascading style sheet that is used by each HTML page. It can be used to fine-tune the look of the HTML output. If left blank Doxygen will generate a default style sheet.
See also section <a href="/web-doxygen/docs/pages/doxygen-usage">Doxygen usage</a> for information on how to generate the style sheet that Doxygen normally uses.
:::info
It is recommended to use <a href="#cfg_html_extra_stylesheet">HTML\_EXTRA\_STYLESHEET</a> instead of this tag, as it is more robust and this tag (<code>HTML\_STYLESHEET</code>) will in the future become obsolete.
:::
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_html_extra_stylesheet"></a></dd>
<dt><code>HTML_EXTRA_STYLESHEET</code></dt>
<dd>The <code>HTML_EXTRA_STYLESHEET</code> tag can be used to specify additional user-defined cascading style sheets that are included after the standard style sheets created by Doxygen. Using this option one can overrule certain style aspects. This is preferred over using <a href="#cfg_html_stylesheet">HTML_STYLESHEET</a> since it does not replace the standard style sheet and is therefore more robust against future updates. Doxygen will copy the style sheet files to the output directory.
:::info
The order of the extra style sheet files is of importance (e.g. the last style sheet in the list overrules the setting of the previous ones in the list).
:::
:::info
Since the styling of scrollbars can currently not be overruled in Webkit/Chromium, the styling will be left out of the default doxygen.css if one or more extra stylesheets have been specified. So if scrollbar customization is desired it has to be added explicitly. Here is an example style sheet that gives the contents area a fixed width:
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
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_html_extra_files"></a></dd>
<dt><code>HTML_EXTRA_FILES</code></dt>
<dd>The <code>HTML_EXTRA_FILES</code> tag can be used to specify one or more extra images or other source files which should be copied to the HTML output directory. Note that these files will be copied to the base HTML output directory. Use the <code>$relpath^</code> marker in the <a href="#cfg_html_header">HTML_HEADER</a> and/or <a href="#cfg_html_footer">HTML_FOOTER</a> files to load these files. In the <a href="#cfg_html_stylesheet">HTML_STYLESHEET</a> file, use the file name only. Also note that the files will be copied as-is; there are no commands or markers available.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_html_colorstyle"></a></dd>
<dt><code>HTML_COLORSTYLE</code></dt>
<dd>The <code>HTML_COLORSTYLE</code> tag can be used to specify if the generated HTML output should be rendered with a dark or light theme.
Possible values are: <code>LIGHT</code> always generates light mode output, <code>DARK</code> always generates dark mode output, <code>AUTO_LIGHT</code> automatically sets the mode according to the user preference, uses light mode if no preference is set (the default), <code>AUTO_DARK</code> automatically sets the mode according to the user preference, uses dark mode if no preference is set and <code>TOGGLE</code> allows a user to switch between light and dark mode via a button.
The default value is: <code>AUTO_LIGHT</code>.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_html_colorstyle_hue"></a></dd>
<dt><code>HTML_COLORSTYLE_HUE</code></dt>
<dd>The <code>HTML_COLORSTYLE_HUE</code> tag controls the color of the HTML output. Doxygen will adjust the colors in the style sheet and background images according to this color. Hue is specified as an angle on a color-wheel, see <a href="https://en.wikipedia.org/wiki/Hue">https://en.wikipedia.org/wiki/Hue</a> for more information. For instance the value 0 represents red, 60 is yellow, 120 is green, 180 is cyan, 240 is blue, 300 purple, and 360 is red again.
Minimum value: <code>0</code>, maximum value: <code>359</code>, default value: <code>220</code>.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_html_colorstyle_sat"></a></dd>
<dt><code>HTML_COLORSTYLE_SAT</code></dt>
<dd>The <code>HTML_COLORSTYLE_SAT</code> tag controls the purity (or saturation) of the colors in the HTML output. For a value of 0 the output will use gray-scales only. A value of 255 will produce the most vivid colors.
Minimum value: <code>0</code>, maximum value: <code>255</code>, default value: <code>100</code>.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_html_colorstyle_gamma"></a></dd>
<dt><code>HTML_COLORSTYLE_GAMMA</code></dt>
<dd>The <code>HTML_COLORSTYLE_GAMMA</code> tag controls the gamma correction applied to the luminance component of the colors in the HTML output. Values below 100 gradually make the output lighter, whereas values above 100 make the output darker. The value divided by 100 is the actual gamma applied, so 80 represents a gamma of 0.8, The value 220 represents a gamma of 2.2, and 100 does not change the gamma.
Minimum value: <code>40</code>, maximum value: <code>240</code>, default value: <code>80</code>.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_html_dynamic_menus"></a></dd>
<dt><code>HTML_DYNAMIC_MENUS</code></dt>
<dd>If the <code>HTML_DYNAMIC_MENUS</code> tag is set to <code>YES</code> then the generated HTML documentation will contain a main index with vertical navigation menus that are dynamically created via JavaScript. If disabled, the navigation index will consists of multiple levels of tabs that are statically embedded in every HTML page. Disable this option to support browsers that do not have JavaScript, like the Qt help browser.
The default value is: <code>YES</code>.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_html_dynamic_sections"></a></dd>
<dt><code>HTML_DYNAMIC_SECTIONS</code></dt>
<dd>If the <code>HTML_DYNAMIC_SECTIONS</code> tag is set to <code>YES</code> then the generated HTML documentation will contain sections that can be hidden and shown after the page has loaded.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_html_code_folding"></a></dd>
<dt><code>HTML_CODE_FOLDING</code></dt>
<dd>If the <code>HTML_CODE_FOLDING</code> tag is set to <code>YES</code> then classes and functions can be dynamically folded and expanded in the generated HTML source code.
The default value is: <code>YES</code>.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_html_copy_clipboard"></a></dd>
<dt><code>HTML_COPY_CLIPBOARD</code></dt>
<dd>If the <code>HTML_COPY_CLIPBOARD</code> tag is set to <code>YES</code> then Doxygen will show an icon in the top right corner of code and text fragments that allows the user to copy its content to the clipboard. Note this only works if supported by the browser and the web page is served via a <a href="https://www.w3.org/TR/secure-contexts/">secure context</a>, i.e. using the https: or file: protocol.
The default value is: <code>YES</code>.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_html_project_cookie"></a></dd>
<dt><code>HTML_PROJECT_COOKIE</code></dt>
<dd>Doxygen stores a couple of settings persistently in the browser (via e.g. cookies). By default these settings apply to all HTML pages generated by Doxygen across all projects. The <code>HTML_PROJECT_COOKIE</code> tag can be used to store the settings under a project specific key, such that the user preferences will be stored separately.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_html_index_num_entries"></a></dd>
<dt><code>HTML_INDEX_NUM_ENTRIES</code></dt>
<dd>With <code>HTML_INDEX_NUM_ENTRIES</code> one can control the preferred number of entries shown in the various tree structured indices initially; the user can expand and collapse entries dynamically later on. Doxygen will expand the tree to such a level that at most the specified number of entries are visible (unless a fully collapsed tree already exceeds this amount). So setting the number of entries 1 will produce a full collapsed tree by default. 0 is a special value representing an infinite number of entries and will result in a full expanded tree by default.
Minimum value: <code>0</code>, maximum value: <code>9999</code>, default value: <code>100</code>.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_generate_docset"></a></dd>
<dt><code>GENERATE_DOCSET</code></dt>
<dd>If the <code>GENERATE_DOCSET</code> tag is set to <code>YES</code>, additional index files will be generated that can be used as input for <a href="https://developer.apple.com/xcode/">Apple's Xcode 3 integrated development environment</a>, introduced with OSX 10.5 (Leopard). To create a documentation set, Doxygen will generate a Makefile in the HTML output directory. Running <code>make</code> will produce the docset in that directory and running <code>make install</code> will install the docset in <code>~/Library/Developer/Shared/Documentation/DocSets</code> so that Xcode will find it at startup. See <a href="https://developer.apple.com/library/archive/featuredarticles/DoxygenXcode/_index.html">https://developer.apple.com/library/archive/featuredarticles/DoxygenXcode/_index.html</a> for more information.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_docset_feedname"></a></dd>
<dt><code>DOCSET_FEEDNAME</code></dt>
<dd>This tag determines the name of the docset feed. A documentation feed provides an umbrella under which multiple documentation sets from a single provider (such as a company or product suite) can be grouped.
The default value is: <code>Doxygen generated docs</code>.
This tag requires that the tag <a href="#cfg_generate_docset">GENERATE_DOCSET</a> is set to <code>YES</code>. <a id="cfg_docset_feedurl"></a></dd>
<dt><code>DOCSET_FEEDURL</code></dt>
<dd>This tag determines the URL of the docset feed. A documentation feed provides an umbrella under which multiple documentation sets from a single provider (such as a company or product suite) can be grouped.
This tag requires that the tag <a href="#cfg_generate_docset">GENERATE_DOCSET</a> is set to <code>YES</code>. <a id="cfg_docset_bundle_id"></a></dd>
<dt><code>DOCSET_BUNDLE_ID</code></dt>
<dd>This tag specifies a string that should uniquely identify the documentation set bundle. This should be a reverse domain-name style string, e.g. <code>com.mycompany.MyDocSet</code>. Doxygen will append <code>.docset</code> to the name.
The default value is: <code>org.doxygen.Project</code>.
This tag requires that the tag <a href="#cfg_generate_docset">GENERATE_DOCSET</a> is set to <code>YES</code>. <a id="cfg_docset_publisher_id"></a></dd>
<dt><code>DOCSET_PUBLISHER_ID</code></dt>
<dd>The <code>DOCSET_PUBLISHER_ID</code> tag specifies a string that should uniquely identify the documentation publisher. This should be a reverse domain-name style string, e.g. <code>com.mycompany.MyDocSet.documentation</code>.
The default value is: <code>org.doxygen.Publisher</code>.
This tag requires that the tag <a href="#cfg_generate_docset">GENERATE_DOCSET</a> is set to <code>YES</code>. <a id="cfg_docset_publisher_name"></a></dd>
<dt><code>DOCSET_PUBLISHER_NAME</code></dt>
<dd>The <code>DOCSET_PUBLISHER_NAME</code> tag identifies the documentation publisher.
The default value is: <code>Publisher</code>.
This tag requires that the tag <a href="#cfg_generate_docset">GENERATE_DOCSET</a> is set to <code>YES</code>. <a id="cfg_generate_htmlhelp"></a></dd>
<dt><code>GENERATE_HTMLHELP</code></dt>
<dd>If the <code>GENERATE_HTMLHELP</code> tag is set to <code>YES</code> then Doxygen generates three additional HTML index files: <code>index.hhp</code>, <code>index.hhc</code>, and <code>index.hhk</code>. The <code>index.hhp</code> is a project file that can be read by Microsoft's HTML Help Workshop on Windows. In the beginning of 2021 Microsoft took the original page, with a.o. the download links, offline (the HTML help workshop was already many years in maintenance mode). You can download the HTML help workshop from the web archives at <a href="http://web.archive.org/web/20160201063255/http://download.microsoft.com/download/0/A/9/0A939EF6-E31C-430F-A3DF-DFAE7960D564/htmlhelp.exe">Installation executable</a>. 
<br/>
 The HTML Help Workshop contains a compiler that can convert all HTML output generated by Doxygen into a single compiled HTML file (<code>.chm</code>). Compiled HTML files are now used as the Windows 98 help format, and will replace the old Windows help format (<code>.hlp</code>) on all Windows platforms in the future. Compressed HTML files also contain an index, a table of contents, and you can search for words in the documentation. The HTML workshop also contains a viewer for compressed HTML files.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_chm_file"></a></dd>
<dt><code>CHM_FILE</code></dt>
<dd>The <code>CHM_FILE</code> tag can be used to specify the file name of the resulting <code>.chm</code> file. You can add a path in front of the file if the result should not be written to the html output directory.
This tag requires that the tag <a href="#cfg_generate_htmlhelp">GENERATE_HTMLHELP</a> is set to <code>YES</code>. <a id="cfg_hhc_location"></a></dd>
<dt><code>HHC_LOCATION</code></dt>
<dd>The <code>HHC_LOCATION</code> tag can be used to specify the location (absolute path including file name) of the HTML help compiler (<code>hhc.exe</code>). If non-empty, Doxygen will try to run the HTML help compiler on the generated <code>index.hhp</code>.
The file has to be specified with full path.
This tag requires that the tag <a href="#cfg_generate_htmlhelp">GENERATE_HTMLHELP</a> is set to <code>YES</code>. <a id="cfg_generate_chi"></a></dd>
<dt><code>GENERATE_CHI</code></dt>
<dd>The <code>GENERATE_CHI</code> flag controls if a separate <code>.chi</code> index file is generated (<code>YES</code>) or that it should be included in the main <code>.chm</code> file (<code>NO</code>).
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_generate_htmlhelp">GENERATE_HTMLHELP</a> is set to <code>YES</code>. <a id="cfg_chm_index_encoding"></a></dd>
<dt><code>CHM_INDEX_ENCODING</code></dt>
<dd>The <code>CHM_INDEX_ENCODING</code> is used to encode HtmlHelp index (<code>hhk</code>), content (<code>hhc</code>) and project file content.
This tag requires that the tag <a href="#cfg_generate_htmlhelp">GENERATE_HTMLHELP</a> is set to <code>YES</code>. <a id="cfg_binary_toc"></a></dd>
<dt><code>BINARY_TOC</code></dt>
<dd>The <code>BINARY_TOC</code> flag controls whether a binary table of contents is generated (<code>YES</code>) or a normal table of contents (<code>NO</code>) in the <code>.chm</code> file. Furthermore it enables the <code>Previous</code> and <code>Next</code> buttons.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_generate_htmlhelp">GENERATE_HTMLHELP</a> is set to <code>YES</code>. <a id="cfg_toc_expand"></a></dd>
<dt><code>TOC_EXPAND</code></dt>
<dd>The <code>TOC_EXPAND</code> flag can be set to <code>YES</code> to add extra items for group members to the table of contents of the HTML help documentation and to the tree view.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_generate_htmlhelp">GENERATE_HTMLHELP</a> is set to <code>YES</code>. <a id="cfg_sitemap_url"></a></dd>
<dt><code>SITEMAP_URL</code></dt>
<dd>The <code>SITEMAP_URL</code> tag is used to specify the full URL of the place where the generated documentation will be placed on the server by the user during the deployment of the documentation. The generated sitemap is called <code>sitemap.xml</code> and placed on the directory specified by <a href="#cfg_html_output">HTML_OUTPUT</a>. In case no <code>SITEMAP_URL</code> is specified no sitemap is generated. For information about the sitemap protocol see <a href="https://www.sitemaps.org">https://www.sitemaps.org</a>
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_generate_qhp"></a></dd>
<dt><code>GENERATE_QHP</code></dt>
<dd>If the <code>GENERATE_QHP</code> tag is set to <code>YES</code> and both <a href="#cfg_qhp_namespace">QHP_NAMESPACE</a> and <a href="#cfg_qhp_virtual_folder">QHP_VIRTUAL_FOLDER</a> are set, an additional index file will be generated that can be used as input for Qt's qhelpgenerator to generate a Qt Compressed Help (<code>.qch</code>) of the generated HTML documentation.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_qch_file"></a></dd>
<dt><code>QCH_FILE</code></dt>
<dd>If the <a href="#cfg_qhg_location">QHG_LOCATION</a> tag is specified, the <code>QCH_FILE</code> tag can be used to specify the file name of the resulting <code>.qch</code> file. The path specified is relative to the HTML output folder.
This tag requires that the tag <a href="#cfg_generate_qhp">GENERATE_QHP</a> is set to <code>YES</code>. <a id="cfg_qhp_namespace"></a></dd>
<dt><code>QHP_NAMESPACE</code></dt>
<dd>The <code>QHP_NAMESPACE</code> tag specifies the namespace to use when generating Qt Help Project output. For more information please see <a href="https://doc.qt.io/archives/qt-4.8/qthelpproject.html#namespace">Qt Help Project / Namespace</a>.
The default value is: <code>org.doxygen.Project</code>.
This tag requires that the tag <a href="#cfg_generate_qhp">GENERATE_QHP</a> is set to <code>YES</code>. <a id="cfg_qhp_virtual_folder"></a></dd>
<dt><code>QHP_VIRTUAL_FOLDER</code></dt>
<dd>The <code>QHP_VIRTUAL_FOLDER</code> tag specifies the namespace to use when generating Qt Help Project output. For more information please see <a href="https://doc.qt.io/archives/qt-4.8/qthelpproject.html#virtual-folders">Qt Help Project / Virtual Folders</a>.
The default value is: <code>doc</code>.
This tag requires that the tag <a href="#cfg_generate_qhp">GENERATE_QHP</a> is set to <code>YES</code>. <a id="cfg_qhp_cust_filter_name"></a></dd>
<dt><code>QHP_CUST_FILTER_NAME</code></dt>
<dd>If the <code>QHP_CUST_FILTER_NAME</code> tag is set, it specifies the name of a custom filter to add. For more information please see <a href="https://doc.qt.io/archives/qt-4.8/qthelpproject.html#custom-filters">Qt Help Project / Custom Filters</a>.
This tag requires that the tag <a href="#cfg_generate_qhp">GENERATE_QHP</a> is set to <code>YES</code>. <a id="cfg_qhp_cust_filter_attrs"></a></dd>
<dt><code>QHP_CUST_FILTER_ATTRS</code></dt>
<dd>The <code>QHP_CUST_FILTER_ATTRS</code> tag specifies the list of the attributes of the custom filter to add. For more information please see <a href="https://doc.qt.io/archives/qt-4.8/qthelpproject.html#custom-filters">Qt Help Project / Custom Filters</a>.
This tag requires that the tag <a href="#cfg_generate_qhp">GENERATE_QHP</a> is set to <code>YES</code>. <a id="cfg_qhp_sect_filter_attrs"></a></dd>
<dt><code>QHP_SECT_FILTER_ATTRS</code></dt>
<dd>The <code>QHP_SECT_FILTER_ATTRS</code> tag specifies the list of the attributes this project's filter section matches. <a href="https://doc.qt.io/archives/qt-4.8/qthelpproject.html#filter-attributes">Qt Help Project / Filter Attributes</a>.
This tag requires that the tag <a href="#cfg_generate_qhp">GENERATE_QHP</a> is set to <code>YES</code>. <a id="cfg_qhg_location"></a></dd>
<dt><code>QHG_LOCATION</code></dt>
<dd>The <code>QHG_LOCATION</code> tag can be used to specify the location (absolute path including file name) of Qt's qhelpgenerator. If non-empty Doxygen will try to run qhelpgenerator on the generated <code>.qhp</code> file.
This tag requires that the tag <a href="#cfg_generate_qhp">GENERATE_QHP</a> is set to <code>YES</code>. <a id="cfg_generate_eclipsehelp"></a></dd>
<dt><code>GENERATE_ECLIPSEHELP</code></dt>
<dd>If the <code>GENERATE_ECLIPSEHELP</code> tag is set to <code>YES</code>, additional index files will be generated, together with the HTML files, they form an <code>Eclipse</code> help plugin.
To install this plugin and make it available under the help contents menu in <code>Eclipse</code>, the contents of the directory containing the HTML and XML files needs to be copied into the plugins directory of eclipse. The name of the directory within the plugins directory should be the same as the <a href="#cfg_eclipse_doc_id">ECLIPSE_DOC_ID</a> value.
After copying <code>Eclipse</code> needs to be restarted before the help appears.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_eclipse_doc_id"></a></dd>
<dt><code>ECLIPSE_DOC_ID</code></dt>
<dd>A unique identifier for the <code>Eclipse</code> help plugin. When installing the plugin the directory name containing the HTML and XML files should also have this name. Each documentation set should have its own identifier.
The default value is: <code>org.doxygen.Project</code>.
This tag requires that the tag <a href="#cfg_generate_eclipsehelp">GENERATE_ECLIPSEHELP</a> is set to <code>YES</code>. <a id="cfg_disable_index"></a></dd>
<dt><code>DISABLE_INDEX</code></dt>
<dd>If you want full control over the layout of the generated HTML pages it might be necessary to disable the index and replace it with your own. The <code>DISABLE_INDEX</code> tag can be used to turn on/off the condensed index (tabs) at top of each HTML page. A value of <code>NO</code> enables the index and the value <code>YES</code> disables it. Since the tabs in the index contain the same information as the navigation tree, you can set this option to <code>YES</code> if you also set <a href="#cfg_generate_treeview">GENERATE_TREEVIEW</a> to <code>YES</code>.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_generate_treeview"></a></dd>
<dt><code>GENERATE_TREEVIEW</code></dt>
<dd>The <code>GENERATE_TREEVIEW</code> tag is used to specify whether a tree-like index structure should be generated to display hierarchical information. If the tag value is set to <code>YES</code>, a side panel will be generated containing a tree-like index structure (just like the one that is generated for HTML Help). For this to work a browser that supports JavaScript, DHTML, CSS and frames is required (i.e. any modern browser). Windows users are probably better off using the HTML help feature.
Via custom style sheets (see <a href="#cfg_html_extra_stylesheet">HTML_EXTRA_STYLESHEET</a>) one can further fine tune the look of the index (see <a href="/web-doxygen/docs/pages/doxygen-usage/#doxygen_finetune">Fine-tuning the output</a>). As an example, the default style sheet generated by Doxygen has an example that shows how to put an image at the root of the tree instead of the <a href="#cfg_project_name">PROJECT_NAME</a>.
Since the tree basically has more details information than the tab index, you could consider setting <a href="#cfg_disable_index">DISABLE_INDEX</a> to <code>YES</code> when enabling this option.
The default value is: <code>YES</code>.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_page_outline_panel"></a></dd>
<dt><code>PAGE_OUTLINE_PANEL</code></dt>
<dd>When <a href="#cfg_generate_treeview">GENERATE_TREEVIEW</a> is set to <code>YES</code>, the <code>PAGE_OUTLINE_PANEL</code> option determines if an additional navigation panel is shown at the right hand side of the screen, displaying an outline of the contents of the main page, similar to e.g. <a href="https://developer.android.com/reference">https://developer.android.com/reference</a>
If <a href="#cfg_generate_treeview">GENERATE_TREEVIEW</a> is set to <code>NO</code>, this option has no effect.
The default value is: <code>YES</code>.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_full_sidebar"></a></dd>
<dt><code>FULL_SIDEBAR</code></dt>
<dd>When <a href="#cfg_generate_treeview">GENERATE_TREEVIEW</a> is set to <code>YES</code>, the <code>FULL_SIDEBAR</code> option determines if the side bar is limited to only the treeview area (value <code>NO</code>) or if it should extend to the full height of the window (value <code>YES</code>). Setting this to <code>YES</code> gives a layout similar to e.g. <a href="https://docs.readthedocs.io">https://docs.readthedocs.io</a> with more room for contents, but less room for the project logo, title, and description.
If <a href="#cfg_generate_treeview">GENERATE_TREEVIEW</a> is set to <code>NO</code>, this option has no effect.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_enum_values_per_line"></a></dd>
<dt><code>ENUM_VALUES_PER_LINE</code></dt>
<dd>The <code>ENUM_VALUES_PER_LINE</code> tag can be used to set the number of enum values that Doxygen will group on one line in the generated HTML documentation. 
<br/>
Note that a value of 0 will completely suppress the enum values from appearing in the overview section.
Minimum value: <code>0</code>, maximum value: <code>20</code>, default value: <code>4</code>.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_show_enum_values"></a></dd>
<dt><code>SHOW_ENUM_VALUES</code></dt>
<dd>When the <code>SHOW_ENUM_VALUES</code> tag is set doxygen will show the specified enumeration values besides the enumeration mnemonics.
The default value is: <code>NO</code>.
<a id="cfg_treeview_width"></a></dd>
<dt><code>TREEVIEW_WIDTH</code></dt>
<dd>If the treeview is enabled (see <a href="#cfg_generate_treeview">GENERATE_TREEVIEW</a>) then this tag can be used to set the initial width (in pixels) of the frame in which the tree is shown.
Minimum value: <code>0</code>, maximum value: <code>1500</code>, default value: <code>250</code>.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_ext_links_in_window"></a></dd>
<dt><code>EXT_LINKS_IN_WINDOW</code></dt>
<dd>If the <code>EXT_LINKS_IN_WINDOW</code> option is set to <code>YES</code>, Doxygen will open links to external symbols imported via tag files in a separate window.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_obfuscate_emails"></a></dd>
<dt><code>OBFUSCATE_EMAILS</code></dt>
<dd>If the <code>OBFUSCATE_EMAILS</code> tag is set to <code>YES</code>, Doxygen will obfuscate email addresses.
The default value is: <code>YES</code>.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_html_formula_format"></a></dd>
<dt><code>HTML_FORMULA_FORMAT</code></dt>
<dd>If the <code>HTML_FORMULA_FORMAT</code> option is set to <code>svg</code>, Doxygen will use the pdf2svg tool (see <a href="https://github.com/dawbarton/pdf2svg">https://github.com/dawbarton/pdf2svg</a>) or inkscape (see <a href="https://inkscape.org">https://inkscape.org</a>) to generate formulas as SVG images instead of PNGs for the HTML output. These images will generally look nicer at scaled resolutions.
Possible values are: <code>png</code> (the default) and <code>svg</code> (looks nicer but requires the pdf2svg or inkscape tool).
The default value is: <code>png</code>.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_formula_fontsize"></a></dd>
<dt><code>FORMULA_FONTSIZE</code></dt>
<dd>Use this tag to change the font size of <code>$\mbox{\LaTeX}$</code> formulas included as images in the HTML documentation. When you change the font size after a successful Doxygen run you need to manually remove any <code>form_*.png</code> images from the HTML output directory to force them to be regenerated.
Minimum value: <code>8</code>, maximum value: <code>50</code>, default value: <code>10</code>.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_formula_macrofile"></a></dd>
<dt><code>FORMULA_MACROFILE</code></dt>
<dd>The <code>FORMULA_MACROFILE</code> can contain <code>$\mbox{\LaTeX}$</code> <code>\newcommand</code> and <code>\renewcommand</code> commands to create new <code>$\mbox{\LaTeX}$</code> commands to be used in formulas as building blocks. See the section <a href="/web-doxygen/docs/pages/formulas">Including formulas</a> for details.
<a id="cfg_use_mathjax"></a></dd>
<dt><code>USE_MATHJAX</code></dt>
<dd>Enable the <code>USE_MATHJAX</code> option to render <code>$\mbox{\LaTeX}$</code> formulas using MathJax (see <a href="https://www.mathjax.org">https://www.mathjax.org</a>) which uses client side JavaScript for the rendering instead of using pre-rendered bitmaps. Use this if you do not have <code>$\mbox{\LaTeX}$</code> installed or if you want to formulas look prettier in the HTML output. When enabled you may also need to install MathJax separately and configure the path to it using the <a href="#cfg_mathjax_relpath">MATHJAX_RELPATH</a> option.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_mathjax_version"></a></dd>
<dt><code>MATHJAX_VERSION</code></dt>
<dd>With <code>MATHJAX_VERSION</code> it is possible to specify the MathJax version to be used. Note that the different versions of MathJax have different requirements with regards to the different settings, so it is possible that also other MathJax settings have to be changed when switching between the different MathJax versions.
Possible values are: <code>MathJax_2</code> and <code>MathJax_3</code>.
The default value is: <code>MathJax_2</code>.
This tag requires that the tag <a href="#cfg_use_mathjax">USE_MATHJAX</a> is set to <code>YES</code>. <a id="cfg_mathjax_format"></a></dd>
<dt><code>MATHJAX_FORMAT</code></dt>
<dd>When MathJax is enabled you can set the default output format to be used for the MathJax output. For more details about the output format see <a href="http://docs.mathjax.org/en/v2.7-latest/output.html">MathJax version 2</a> and <a href="http://docs.mathjax.org/en/latest/web/components/output.html">MathJax version 3</a>.
Possible values are: <code>HTML-CSS</code> (which is slower, but has the best compatibility. This is the name for Mathjax version 2, for MathJax version 3 this will be translated into <code>chtml</code>), <code>NativeMML</code> (i.e. MathML. Only supported for MathJax 2. For MathJax version 3 <code>chtml</code> will be used instead.), <code>chtml</code> (This is the name for Mathjax version 3, for MathJax version 2 this will be translated into <code>HTML-CSS</code>) and <code>SVG</code>.
The default value is: <code>HTML-CSS</code>.
This tag requires that the tag <a href="#cfg_use_mathjax">USE_MATHJAX</a> is set to <code>YES</code>. <a id="cfg_mathjax_relpath"></a></dd>
<dt><code>MATHJAX_RELPATH</code></dt>
<dd>When MathJax is enabled you need to specify the location relative to the HTML output directory using the <code>MATHJAX_RELPATH</code> option. The destination directory should contain the <code>MathJax.js</code> script. For instance, if the <code>mathjax</code> directory is located at the same level as the HTML output directory, then <code>MATHJAX_RELPATH</code> should be <code>../mathjax</code>. The default value points to the MathJax Content Delivery Network so you can quickly see the result without installing MathJax. However, it is strongly recommended to install a local copy of MathJax from <a href="https://www.mathjax.org">https://www.mathjax.org</a> before deployment.
The default value is:
<ul class="doxyList ">
<li>in case of MathJax version 2: <a href="https://cdn.jsdelivr.net/npm/mathjax@2">https://cdn.jsdelivr.net/npm/mathjax@2</a></li>
<li>in case of MathJax version 3: <a href="https://cdn.jsdelivr.net/npm/mathjax@3">https://cdn.jsdelivr.net/npm/mathjax@3</a></li>
</ul>
This tag requires that the tag <a href="#cfg_use_mathjax">USE_MATHJAX</a> is set to <code>YES</code>. <a id="cfg_mathjax_extensions"></a></dd>
<dt><code>MATHJAX_EXTENSIONS</code></dt>
<dd>The <code>MATHJAX_EXTENSIONS</code> tag can be used to specify one or more MathJax extension names that should be enabled during MathJax rendering. For example for MathJax version 2 (see <a href="https://docs.mathjax.org/en/v2.7-latest/tex.html#tex-and-latex-extensions">https://docs.mathjax.org/en/v2.7-latest/tex.html#tex-and-latex-extensions</a>):
<pre><code>MATHJAX_EXTENSIONS     = TeX/AMSmath TeX/AMSsymbols
</code></pre>
For example for MathJax version 3 (see <a href="http://docs.mathjax.org/en/latest/input/tex/extensions/index.html">http://docs.mathjax.org/en/latest/input/tex/extensions/index.html</a>):
<pre><code>MATHJAX_EXTENSIONS     = ams
</code></pre>
This tag requires that the tag <a href="#cfg_use_mathjax">USE_MATHJAX</a> is set to <code>YES</code>. <a id="cfg_mathjax_codefile"></a></dd>
<dt><code>MATHJAX_CODEFILE</code></dt>
<dd>The <code>MATHJAX_CODEFILE</code> tag can be used to specify a file with JavaScript pieces of code that will be used on startup of the MathJax code. See <a href="http://docs.mathjax.org/en/v2.7-latest/output.html">the MathJax site</a> for more details. As an example to disable the "Math Renderer" menu item in the "Math
 Settings" menu of MathJax:
<pre><code>MATHJAX_CODEFILE = disableRenderer.js
</code></pre>
with in the file <code>disableRenderer.js</code>:
<pre><code>  MathJax.Hub.Config({
   menuSettings: {
    showRenderer: false,
   }
  });
</code></pre>
This tag requires that the tag <a href="#cfg_use_mathjax">USE_MATHJAX</a> is set to <code>YES</code>. <a id="cfg_searchengine"></a></dd>
<dt><code>SEARCHENGINE</code></dt>
<dd>When the <code>SEARCHENGINE</code> tag is enabled Doxygen will generate a search box for the HTML output. The underlying search engine uses JavaScript and DHTML and should work on any modern browser. Note that when using HTML help (<a href="#cfg_generate_htmlhelp">GENERATE_HTMLHELP</a>), Qt help (<a href="#cfg_generate_qhp">GENERATE_QHP</a>), or docsets (<a href="#cfg_generate_docset">GENERATE_DOCSET</a>) there is already a search function so this one should typically be disabled. For large projects the JavaScript based search engine can be slow, then enabling <a href="#cfg_server_based_search">SERVER_BASED_SEARCH</a> may provide a better solution.
It is possible to search using the keyboard; to jump to the search box use <code>&lt;access key&gt; + S</code> (what the <code>&lt;access key&gt;</code> is depends on the OS and browser, but it is typically <code>&lt;CTRL&gt;</code>, <code>&lt;ALT&gt;</code>/<code>&lt;option&gt;</code>, or both). Inside the search box use the <code>&lt;cursor down key&gt;</code> to jump into the search results window, the results can be navigated using the <code>&lt;cursor keys&gt;</code>. Press <code>&lt;Enter&gt;</code> to select an item or <code>&lt;escape&gt;</code> to cancel the search. The filter options can be selected when the cursor is inside the search box by pressing <code>&lt;Shift&gt;+&lt;cursor down&gt;</code>. Also here use the <code>&lt;cursor keys&gt;</code> to select a filter and <code>&lt;Enter&gt;</code> or <code>&lt;escape&gt;</code> to activate or cancel the filter option.
The default value is: <code>YES</code>.
This tag requires that the tag <a href="#cfg_generate_html">GENERATE_HTML</a> is set to <code>YES</code>. <a id="cfg_server_based_search"></a></dd>
<dt><code>SERVER_BASED_SEARCH</code></dt>
<dd>When the <code>SERVER_BASED_SEARCH</code> tag is enabled the search engine will be implemented using a web server instead of a web client using JavaScript.
There are two flavors of web server based searching depending on the <a href="#cfg_external_search">EXTERNAL_SEARCH</a> setting. When disabled, Doxygen will generate a PHP script for searching and an index file used by the script. When <a href="#cfg_external_search">EXTERNAL_SEARCH</a> is enabled the indexing and searching needs to be provided by external tools. See the section <a href="/web-doxygen/docs/pages/extsearch">External Indexing and Searching</a> for details.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_searchengine">SEARCHENGINE</a> is set to <code>YES</code>. <a id="cfg_external_search"></a></dd>
<dt><code>EXTERNAL_SEARCH</code></dt>
<dd>When <code>EXTERNAL_SEARCH</code> tag is enabled Doxygen will no longer generate the PHP script for searching. Instead the search results are written to an XML file which needs to be processed by an external indexer. Doxygen will invoke an external search engine pointed to by the <a href="#cfg_searchengine_url">SEARCHENGINE_URL</a> option to obtain the search results. 
<br/>
Doxygen ships with an example indexer (<code>doxyindexer</code>) and search engine (<code>doxysearch.cgi</code>) which are based on the open source search engine library <a href="https://xapian.org/">Xapian</a>. 
<br/>
See the section <a href="/web-doxygen/docs/pages/extsearch">External Indexing and Searching</a> for details.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_searchengine">SEARCHENGINE</a> is set to <code>YES</code>. <a id="cfg_searchengine_url"></a></dd>
<dt><code>SEARCHENGINE_URL</code></dt>
<dd>The <code>SEARCHENGINE_URL</code> should point to a search engine hosted by a web server which will return the search results when <a href="#cfg_external_search">EXTERNAL_SEARCH</a> is enabled. 
<br/>
Doxygen ships with an example indexer (<code>doxyindexer</code>) and search engine (<code>doxysearch.cgi</code>) which are based on the open source search engine library <a href="https://xapian.org/">Xapian</a>. See the section <a href="/web-doxygen/docs/pages/extsearch">External Indexing and Searching</a> for details.
This tag requires that the tag <a href="#cfg_searchengine">SEARCHENGINE</a> is set to <code>YES</code>. <a id="cfg_searchdata_file"></a></dd>
<dt><code>SEARCHDATA_FILE</code></dt>
<dd>When <a href="#cfg_server_based_search">SERVER_BASED_SEARCH</a> and <a href="#cfg_external_search">EXTERNAL_SEARCH</a> are both enabled the unindexed search data is written to a file for indexing by an external tool. With the <code>SEARCHDATA_FILE</code> tag the name of this file can be specified.
The default file is: <code>searchdata.xml</code>.
This tag requires that the tag <a href="#cfg_searchengine">SEARCHENGINE</a> is set to <code>YES</code>. <a id="cfg_external_search_id"></a></dd>
<dt><code>EXTERNAL_SEARCH_ID</code></dt>
<dd>When <a href="#cfg_server_based_search">SERVER_BASED_SEARCH</a> and <a href="#cfg_external_search">EXTERNAL_SEARCH</a> are both enabled the <code>EXTERNAL_SEARCH_ID</code> tag can be used as an identifier for the project. This is useful in combination with <a href="#cfg_extra_search_mappings">EXTRA_SEARCH_MAPPINGS</a> to search through multiple projects and redirect the results back to the right project.
This tag requires that the tag <a href="#cfg_searchengine">SEARCHENGINE</a> is set to <code>YES</code>. <a id="cfg_extra_search_mappings"></a></dd>
<dt><code>EXTRA_SEARCH_MAPPINGS</code></dt>
<dd>The <code>EXTRA_SEARCH_MAPPINGS</code> tag can be used to enable searching through Doxygen projects other than the one defined by this configuration file, but that are all added to the same external search index. Each project needs to have a unique id set via <a href="#cfg_external_search_id">EXTERNAL_SEARCH_ID</a>. The search mapping then maps the id of to a relative location where the documentation can be found.
The format is:
<pre><code>EXTRA_SEARCH_MAPPINGS = tagname1=loc1 tagname2=loc2 ...
</code></pre>
This tag requires that the tag <a href="#cfg_searchengine">SEARCHENGINE</a> is set to <code>YES</code>.</dd>
</dl>

## Configuration options related to the LaTeX output {#config_latex}


<a id="cfg_generate_latex"></a>

<dl class="doxyVariableList">
<dt><code>GENERATE_LATEX</code></dt>
<dd>If the <code>GENERATE_LATEX</code> tag is set to <code>YES</code>, Doxygen will generate <code>$\mbox{\LaTeX}$</code> output.
The default value is: <code>YES</code>.
<a id="cfg_latex_output"></a></dd>
<dt><code>LATEX_OUTPUT</code></dt>
<dd>The <code>LATEX_OUTPUT</code> tag is used to specify where the <code>$\mbox{\LaTeX}$</code> docs will be put. If a relative path is entered the value of <a href="#cfg_output_directory">OUTPUT_DIRECTORY</a> will be put in front of it.
The default directory is: <code>latex</code>.
This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <code>YES</code>. <a id="cfg_latex_cmd_name"></a></dd>
<dt><code>LATEX_CMD_NAME</code></dt>
<dd>The <code>LATEX_CMD_NAME</code> tag can be used to specify the <code>$\mbox{\LaTeX}$</code> command name to be invoked. 
<br/>
Note that when not enabling <a href="#cfg_use_pdflatex">USE_PDFLATEX</a> the default is <code>latex</code> when enabling <a href="#cfg_use_pdflatex">USE_PDFLATEX</a> the default is <code>pdflatex</code> and when in the later case <code>latex</code> is chosen this is overwritten by <code>pdflatex</code>. For specific output languages the default can have been set differently, this depends on the implementation of the output language.
This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <code>YES</code>. <a id="cfg_makeindex_cmd_name"></a></dd>
<dt><code>MAKEINDEX_CMD_NAME</code></dt>
<dd>The <code>MAKEINDEX_CMD_NAME</code> tag can be used to specify the command name to generate index for <code>$\mbox{\LaTeX}$</code>.
:::info
This tag is used in the <code>Makefile</code> / <code>make.bat</code>.
:::
<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><a href="#cfg_latex_makeindex_cmd">LATEX_MAKEINDEX_CMD</a> for the part in the generated output file (<code>.tex</code>).</dd>
</dl>
The default file is: <code>makeindex</code>.
This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <code>YES</code>. <a id="cfg_latex_makeindex_cmd"></a></dd>
<dt><code>LATEX_MAKEINDEX_CMD</code></dt>
<dd>The <code>LATEX_MAKEINDEX_CMD</code> tag can be used to specify the command name to generate index for <code>$\mbox{\LaTeX}$</code>. In case there is no backslash (<code>\</code>) as first character it will be automatically added in the <code>$\mbox{\LaTeX}$</code> code.
:::info
This tag is used in the generated output file (<code>.tex</code>).
:::
<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><a href="#cfg_makeindex_cmd_name">MAKEINDEX_CMD_NAME</a> for the part in the <code>Makefile</code> / <code>make.bat</code>.</dd>
</dl>
The default value is: <code>makeindex</code>.
This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <code>YES</code>. <a id="cfg_compact_latex"></a></dd>
<dt><code>COMPACT_LATEX</code></dt>
<dd>If the <code>COMPACT_LATEX</code> tag is set to <code>YES</code>, Doxygen generates more compact <code>$\mbox{\LaTeX}$</code> documents. This may be useful for small projects and may help to save some trees in general.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <code>YES</code>. <a id="cfg_paper_type"></a></dd>
<dt><code>PAPER_TYPE</code></dt>
<dd>The <code>PAPER_TYPE</code> tag can be used to set the paper type that is used by the printer.
Possible values are: <code>a4</code> (210 x 297 mm), <code>letter</code> (8.5 x 11 inches), <code>legal</code> (8.5 x 14 inches) and <code>executive</code> (7.25 x 10.5 inches).
The default value is: <code>a4</code>.
This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <code>YES</code>. <a id="cfg_extra_packages"></a></dd>
<dt><code>EXTRA_PACKAGES</code></dt>
<dd>The <code>EXTRA_PACKAGES</code> tag can be used to specify one or more <code>$\mbox{\LaTeX}$</code> package names that should be included in the <code>$\mbox{\LaTeX}$</code> output. The package can be specified just by its name or with the correct syntax as to be used with the <code>$\mbox{\LaTeX}$</code> <code>\usepackage</code> command.
To get the <code>times</code> font for instance you can specify :
<pre><code>  EXTRA_PACKAGES=times
or
  EXTRA_PACKAGES={times}
</code></pre>
To use the option <code>intlimits</code> with the <code>amsmath</code> package you can specify:
<pre><code>   EXTRA_PACKAGES=[intlimits]{amsmath}
</code></pre>
If left blank no extra packages will be included.
This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <code>YES</code>. <a id="cfg_latex_header"></a></dd>
<dt><code>LATEX_HEADER</code></dt>
<dd>The <code>LATEX_HEADER</code> tag can be used to specify a user-defined <code>$\mbox{\LaTeX}$</code> header for the generated <code>$\mbox{\LaTeX}$</code> document. The header should contain everything until the first chapter. If it is left blank Doxygen will generate a standard header.
It is highly recommended to start with a default header using
<pre><code>doxygen -w latex new_header.tex new_footer.tex new_stylesheet.sty
</code></pre>
and then modify the file <code>new_header.tex</code>.
See also section <a href="/web-doxygen/docs/pages/doxygen-usage">Doxygen usage</a> for information on how to generate the default header that Doxygen normally uses.
<br/>
Note: Only use a user-defined header if you know what you are doing!
:::info
The header is subject to change so you typically have to regenerate the default header when upgrading to a newer version of Doxygen. The following commands have a special meaning inside the header (and footer):
<dl class="doxyVariableList">
<dt><code>$title</code></dt>
<dd>will be replaced with the project name.</dd>
<dt><code>$datetime</code></dt>
<dd>will be replaced with the current date and time.</dd>
<dt><code>$date</code></dt>
<dd>will be replaced with the current date.</dd>
<dt><code>$time</code></dt>
<dd>will be replaced with the current time.</dd>
<dt><code>$year</code></dt>
<dd>will be replaces with the current year.</dd>
<dt><code>$showdate(&lt;format&gt;)</code></dt>
<dd>will be replaced with the current date and time according to the format as specified by <code>&lt;format&gt;</code>. The <code>&lt;format&gt;</code> follows the rules as specified for the <a href="/web-doxygen/docs/pages/commands/#cmdshowdate">\showdate</a> command with the exception that no <code>)</code> is allowed in the <code>&lt;format&gt;</code>.</dd>
<dt><code>$doxygenversion</code></dt>
<dd>will be replaced with the version of Doxygen</dd>
<dt><code>$projectname</code></dt>
<dd>will be replaced with the name of the project (see <a href="#cfg_project_name">PROJECT_NAME</a>)</dd>
<dt><code>$projectnumber</code></dt>
<dd>will be replaced with the project number (see <a href="#cfg_project_number">PROJECT_NUMBER</a>)</dd>
<dt><code>$projectbrief</code></dt>
<dd>will be replaced with the project brief description (see <a href="#cfg_project_brief">PROJECT_BRIEF</a>)</dd>
<dt><code>$projectlogo</code></dt>
<dd>will be replaced with the project logo (see <a href="#cfg_project_logo">PROJECT_LOGO</a>)</dd>
<dt><code>$latexdocumentpre</code></dt>
<dd>will be replaced by an output language dependent setting e.g. embed the entire document in a special environment (for Chinese, Japanese etc.) Commonly used together with <code>$latexdocumentpost</code> in the footer.</dd>
<dt><code>$latexdocumentpost</code></dt>
<dd>will be replaced by an output language dependent setting e.g. embed the entire document in a special environment (for Chinese, Japanese etc.) Commonly used together with <code>$latexdocumentpre</code> in the header.</dd>
<dt><code>$generatedby</code></dt>
<dd>will be replaced with the output language dependent version of the text "Generated by" or when the <a href="#cfg_timestamp">TIMESTAMP</a> is set by the output language dependent version of the text "Generated on <code>$datetime</code> for <code>$projectname</code> by".</dd>
<dt><code>$latexcitereference</code></dt>
<dd>will be replaced by the output language dependent$ version of the word "Bibliography". This setting is typically used in combination with the block name <code>CITATIONS_PRESENT</code>.</dd>
<dt><code>$latexbibstyle</code></dt>
<dd>will be replaced with the latex bib style to be used as set by <a href="#cfg_latex_bib_style">LATEX_BIB_STYLE</a>, in case nothing is set the bib style <code>plain</code> is used. This setting is typically used in combination with the block name <code>CITATIONS_PRESENT</code>.</dd>
<dt><code>$latexbibfiles</code></dt>
<dd>will be replaced by the comma separated list of <code>bib</code>. files as set by <a href="#cfg_cite_bib_files">CITE_BIB_FILES</a> (when necessary a missing <code>.bib</code> is automatically added). This setting is typically used in combination with the block name <code>CITATIONS_PRESENT</code>.</dd>
<dt><code>$papertype</code></dt>
<dd>will be replaced by the paper type as set in <a href="#cfg_paper_type">PAPER_TYPE</a> and the word "paper" is directly appended to it to have a correct <code>$\mbox{\LaTeX}$</code> paper type.</dd>
<dt><code>$langISO</code></dt>
<dd>will be replaced by the ISO language name.</dd>
<dt><code>$languagesupport</code></dt>
<dd>will be replaced by an output language dependent setting of packages required for translating terms of the specified language.</dd>
<dt><code>$latexfontenc</code></dt>
<dd>will be replaced by an output language dependent setting of the fontencoding to be used. This setting is typically used in combination with the block name <code>LATEX_FONTENC</code>.</dd>
<dt><code>$latexfont</code></dt>
<dd>will be replaced by an output language dependent setting of the fonts to be used.</dd>
<dt><code>$latexemojidirectory</code></dt>
<dd>will be replaced by the directory as set in <a href="#cfg_latex_emoji_directory">LATEX_EMOJI_DIRECTORY</a> with the backslashes replaced by forward slashes (so usable by <code>$\mbox{\LaTeX}$</code>). In case the <a href="#cfg_latex_emoji_directory">LATEX_EMOJI_DIRECTORY</a> is empty, the current directory will be used.</dd>
<dt><code>$makeindex</code></dt>
<dd>will be replaced by the command as set in <a href="#cfg_latex_makeindex_cmd">LATEX_MAKEINDEX_CMD</a>. Then the command doesn't start with a backslash, a backslash is automatically prepended. In case the setting is empty the command <code>\makeindex</code> is used.</dd>
<dt><code>$extralatexpackages</code></dt>
<dd>will be replaced by commands for using the packages set in <a href="#cfg_extra_packages">EXTRA_PACKAGES</a>.</dd>
<dt><code>$extralatexstylesheet</code></dt>
<dd>will be replaced by commands for using the packages set in <a href="#cfg_latex_extra_stylesheet">LATEX_EXTRA_STYLESHEET</a> (when the extension is the default extension, <code>.sty</code>, this extension is stripped for the package name).</dd>
<dt><code>$latexspecialformulachars</code></dt>
<dd>will be replaced by the code for some special unicode characters that are commonly used (i.e. superscript minus, superscript 2 and superscript 3)</dd>
<dt><code>$formulamacrofile</code></dt>
<dd>will be replaced by the name of the file as set in <a href="#cfg_formula_macrofile">FORMULA_MACROFILE</a>. This setting is typically used in combination with the block name <code>FORMULA_MACROFILE</code>.</dd>
</dl>
:::
To cope with differences in the layout of the header and footer that depend on configuration settings, the header and footer can also contain special blocks that will be copied to the output or skipped depending on the configuration. Such blocks have the following form:
<pre><code> %%BEGIN BLOCKNAME
 Some context copied when condition BLOCKNAME holds
 %%END BLOCKNAME
 %%BEGIN !BLOCKNAME
 Some context copied when condition BLOCKNAME does not hold
 %%END !BLOCKNAME
</code></pre>
The following block names are set based on the used settings in the configuration file:
<dl class="doxyVariableList">
<dt><code>COMPACT_LATEX</code></dt>
<dd>Content within this block is copied to the output when the <a href="#cfg_compact_latex">COMPACT_LATEX</a> option is enabled.</dd>
<dt><code>PDF_HYPERLINKS</code></dt>
<dd>Content within this block is copied to the output when the <a href="#cfg_pdf_hyperlinks">PDF_HYPERLINKS</a> option is enabled.</dd>
<dt><code>USE_PDFLATEX</code></dt>
<dd>Content within this block is copied to the output when the <a href="#cfg_use_pdflatex">USE_PDFLATEX</a> option is enabled.</dd>
<dt><code>LATEX_BATCHMODE</code></dt>
<dd>Content within this block is copied to the output when the <a href="#cfg_latex_batchmode">LATEX_BATCHMODE</a> option is enabled.</dd>
<dt><code>TIMESTAMP</code></dt>
<dd>Content within this block is copied to the output when the <a href="#cfg_timestamp">TIMESTAMP</a> option is enabled.</dd>
</dl>
The following block names are set based on the fact whether or not the tag has a value in the used configuration file:
<dl class="doxyVariableList">
<dt><code>LATEX_FONTENC</code></dt>
<dd>Content within this block is copied to the output when the Doxygen latex translator function returns a value for the font encoding to be used. It is to be used in combination with the above mentioned <code>$latexfontenc</code>.</dd>
<dt><code>FORMULA_MACROFILE</code></dt>
<dd>Content within this block is copied to the output when the <a href="#cfg_formula_macrofile">FORMULA_MACROFILE</a> option is not empty. It is to be used in combination with the above mentioned <code>$formulamacrofile</code>.</dd>
</dl>
The following block name is set based on whether or not a feature is used in the documentation:
<dl class="doxyVariableList">
<dt><code>CITATIONS_PRESENT</code></dt>
<dd>Content within this block is copied to the output when in the documentation citations are present and the relevant .. are present. It is to be used in combination with the above mentioned <code>$latexcitereference</code>, <code>$latexbibstyle</code> and <code>$latexbibfiles</code>.</dd>
</dl>
This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <code>YES</code>. <a id="cfg_latex_footer"></a></dd>
<dt><code>LATEX_FOOTER</code></dt>
<dd>The <code>LATEX_FOOTER</code> tag can be used to specify a user-defined <code>$\mbox{\LaTeX}$</code> footer for the generated <code>$\mbox{\LaTeX}$</code> document. The footer should contain everything after the last chapter. If it is left blank Doxygen will generate a standard footer.
See <a href="#cfg_latex_header">LATEX_HEADER</a> for more information on how to generate a default footer and what special commands can be used inside the footer.
See also section <a href="/web-doxygen/docs/pages/doxygen-usage">Doxygen usage</a> for information on how to generate the default footer that Doxygen normally uses.
Note: Only use a user-defined footer if you know what you are doing!
This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <code>YES</code>. <a id="cfg_latex_extra_stylesheet"></a></dd>
<dt><code>LATEX_EXTRA_STYLESHEET</code></dt>
<dd>The <code>LATEX_EXTRA_STYLESHEET</code> tag can be used to specify additional user-defined <code>$\mbox{\LaTeX}$</code> style sheets that are included after the standard style sheets created by Doxygen. Using this option one can overrule certain style aspects. Doxygen will copy the style sheet files to the output directory.
:::info
The order of the extra style sheet files is of importance (e.g. the last style sheet in the list overrules the setting of the previous ones in the list).
:::
This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <code>YES</code>. <a id="cfg_latex_extra_files"></a></dd>
<dt><code>LATEX_EXTRA_FILES</code></dt>
<dd>The <code>LATEX_EXTRA_FILES</code> tag can be used to specify one or more extra images or other source files which should be copied to the <a href="#cfg_latex_output">LATEX_OUTPUT</a> output directory. Note that the files will be copied as-is; there are no commands or markers available.
This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <code>YES</code>. <a id="cfg_pdf_hyperlinks"></a></dd>
<dt><code>PDF_HYPERLINKS</code></dt>
<dd>If the <code>PDF_HYPERLINKS</code> tag is set to <code>YES</code>, the <code>$\mbox{\LaTeX}$</code> that is generated is prepared for conversion to PDF (using <code>ps2pdf</code> or <code>pdflatex</code>). The PDF file will contain links (just like the HTML output) instead of page references. This makes the output suitable for online browsing using a PDF viewer.
The default value is: <code>YES</code>.
This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <code>YES</code>. <a id="cfg_use_pdflatex"></a></dd>
<dt><code>USE_PDFLATEX</code></dt>
<dd>If the <code>USE_PDFLATEX</code> tag is set to <code>YES</code>, Doxygen will use the engine as specified with <a href="#cfg_latex_cmd_name">LATEX_CMD_NAME</a> to generate the PDF file directly from the <code>$\mbox{\LaTeX}$</code> files. Set this option to <code>YES</code>, to get a higher quality PDF documentation. 
<br/>
 See also section <a href="#cfg_latex_cmd_name">LATEX_CMD_NAME</a> for selecting the engine.
The default value is: <code>YES</code>.
This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <code>YES</code>. <a id="cfg_latex_batchmode"></a></dd>
<dt><code>LATEX_BATCHMODE</code></dt>
<dd>The <code>LATEX_BATCHMODE</code> tag signals the behavior of <code>$\mbox{\LaTeX}$</code> in case of an error.
Possible values are: <code>NO</code> same as ERROR_STOP, <code>YES</code> same as BATCH, <code>BATCH</code> In batch mode nothing is printed on the terminal, errors are scrolled as if &lt;return&gt; is hit at every error; missing files that TeX tries to input or request from keyboard input (\read on a not open input stream) cause the job to abort, <code>NON_STOP</code> In nonstop mode the diagnostic message will appear on the terminal, but there is no possibility of user interaction just like in batch mode, <code>SCROLL</code> In scroll mode, TeX will stop only for missing files to input or if keyboard input is necessary and <code>ERROR_STOP</code> In errorstop mode, TeX will stop at each error, asking for user intervention.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <code>YES</code>. <a id="cfg_latex_hide_indices"></a></dd>
<dt><code>LATEX_HIDE_INDICES</code></dt>
<dd>If the <code>LATEX_HIDE_INDICES</code> tag is set to <code>YES</code> then Doxygen will not include the index chapters (such as File Index, Compound Index, etc.) in the output.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <code>YES</code>. <a id="cfg_latex_bib_style"></a></dd>
<dt><code>LATEX_BIB_STYLE</code></dt>
<dd>The <code>LATEX_BIB_STYLE</code> tag can be used to specify the style to use for the bibliography, e.g. <code>plainnat</code>, or <code>ieeetr</code>. See <a href="https://en.wikipedia.org/wiki/BibTeX">https://en.wikipedia.org/wiki/BibTeX</a> and <a href="/web-doxygen/docs/pages/commands/#cmdcite">\cite</a> for more info.
The default value is: <code>plainnat</code>.
This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <code>YES</code>. <a id="cfg_latex_emoji_directory"></a></dd>
<dt><code>LATEX_EMOJI_DIRECTORY</code></dt>
<dd>The <code>LATEX_EMOJI_DIRECTORY</code> tag is used to specify the (relative or absolute) path from which the emoji images will be read. If a relative path is entered, it will be relative to the <a href="#cfg_latex_output">LATEX_OUTPUT</a> directory. If left blank the <a href="#cfg_latex_output">LATEX_OUTPUT</a> directory will be used.
This tag requires that the tag <a href="#cfg_generate_latex">GENERATE_LATEX</a> is set to <code>YES</code>.</dd>
</dl>

## Configuration options related to the RTF output {#config_rtf}


<a id="cfg_generate_rtf"></a>

<dl class="doxyVariableList">
<dt><code>GENERATE_RTF</code></dt>
<dd>If the <code>GENERATE_RTF</code> tag is set to <code>YES</code>, Doxygen will generate RTF output. The RTF output is optimized for Word 97 and may not look too pretty with other RTF readers/editors.
The default value is: <code>NO</code>.
<a id="cfg_rtf_output"></a></dd>
<dt><code>RTF_OUTPUT</code></dt>
<dd>The <code>RTF_OUTPUT</code> tag is used to specify where the RTF docs will be put. If a relative path is entered the value of <a href="#cfg_output_directory">OUTPUT_DIRECTORY</a> will be put in front of it.
The default directory is: <code>rtf</code>.
This tag requires that the tag <a href="#cfg_generate_rtf">GENERATE_RTF</a> is set to <code>YES</code>. <a id="cfg_compact_rtf"></a></dd>
<dt><code>COMPACT_RTF</code></dt>
<dd>If the <code>COMPACT_RTF</code> tag is set to <code>YES</code>, Doxygen generates more compact RTF documents. This may be useful for small projects and may help to save some trees in general.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_generate_rtf">GENERATE_RTF</a> is set to <code>YES</code>. <a id="cfg_rtf_hyperlinks"></a></dd>
<dt><code>RTF_HYPERLINKS</code></dt>
<dd>If the <code>RTF_HYPERLINKS</code> tag is set to <code>YES</code>, the RTF that is generated will contain hyperlink fields. The RTF file will contain links (just like the HTML output) instead of page references. This makes the output suitable for online browsing using Word or some other Word compatible readers that support those fields.
<br/>
Note: WordPad (write) and others do not support links.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_generate_rtf">GENERATE_RTF</a> is set to <code>YES</code>. <a id="cfg_rtf_stylesheet_file"></a></dd>
<dt><code>RTF_STYLESHEET_FILE</code></dt>
<dd>Load stylesheet definitions from file. Syntax is similar to Doxygen's configuration file, i.e. a series of assignments. You only have to provide replacements, missing definitions are set to their default value. 
<br/>
 See also section <a href="/web-doxygen/docs/pages/doxygen-usage">Doxygen usage</a> for information on how to generate the default style sheet that Doxygen normally uses.
This tag requires that the tag <a href="#cfg_generate_rtf">GENERATE_RTF</a> is set to <code>YES</code>. <a id="cfg_rtf_extensions_file"></a></dd>
<dt><code>RTF_EXTENSIONS_FILE</code></dt>
<dd>Set optional variables used in the generation of an RTF document. Syntax is similar to Doxygen's configuration file. A template extensions file can be generated using <code>doxygen -e rtf extensionFile</code>.
This tag requires that the tag <a href="#cfg_generate_rtf">GENERATE_RTF</a> is set to <code>YES</code>. <a id="cfg_rtf_extra_files"></a></dd>
<dt><code>RTF_EXTRA_FILES</code></dt>
<dd>The <code>RTF_EXTRA_FILES</code> tag can be used to specify one or more extra images or other source files which should be copied to the <a href="#cfg_rtf_output">RTF_OUTPUT</a> output directory. Note that the files will be copied as-is; there are no commands or markers available.
This tag requires that the tag <a href="#cfg_generate_rtf">GENERATE_RTF</a> is set to <code>YES</code>.</dd>
</dl>

## Configuration options related to the man page output {#config_man}


<a id="cfg_generate_man"></a>

<dl class="doxyVariableList">
<dt><code>GENERATE_MAN</code></dt>
<dd>If the <code>GENERATE_MAN</code> tag is set to <code>YES</code>, Doxygen will generate man pages for classes and files.
The default value is: <code>NO</code>.
<a id="cfg_man_output"></a></dd>
<dt><code>MAN_OUTPUT</code></dt>
<dd>The <code>MAN_OUTPUT</code> tag is used to specify where the man pages will be put. If a relative path is entered the value of <a href="#cfg_output_directory">OUTPUT_DIRECTORY</a> will be put in front of it. A directory <code>man3</code> will be created inside the directory specified by <code>MAN_OUTPUT</code>.
The default directory is: <code>man</code>.
This tag requires that the tag <a href="#cfg_generate_man">GENERATE_MAN</a> is set to <code>YES</code>. <a id="cfg_man_extension"></a></dd>
<dt><code>MAN_EXTENSION</code></dt>
<dd>The <code>MAN_EXTENSION</code> tag determines the extension that is added to the generated man pages. In case the manual section does not start with a number, the number 3 is prepended. The dot (.) at the beginning of the <code>MAN_EXTENSION</code> tag is optional.
The default value is: <code>0.3</code>.
This tag requires that the tag <a href="#cfg_generate_man">GENERATE_MAN</a> is set to <code>YES</code>. <a id="cfg_man_subdir"></a></dd>
<dt><code>MAN_SUBDIR</code></dt>
<dd>The <code>MAN_SUBDIR</code> tag determines the name of the directory created within <code>MAN_OUTPUT</code> in which the man pages are placed. If defaults to man followed by <code>MAN_EXTENSION</code> with the initial . removed.
This tag requires that the tag <a href="#cfg_generate_man">GENERATE_MAN</a> is set to <code>YES</code>. <a id="cfg_man_links"></a></dd>
<dt><code>MAN_LINKS</code></dt>
<dd>If the <code>MAN_LINKS</code> tag is set to <code>YES</code> and Doxygen generates man output, then it will generate one additional man file for each entity documented in the real man page(s). These additional files only source the real man page, but without them the <code>man</code> command would be unable to find the correct page.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_generate_man">GENERATE_MAN</a> is set to <code>YES</code>.</dd>
</dl>

## Configuration options related to the XML output {#config_xml}


<a id="cfg_generate_xml"></a>

<dl class="doxyVariableList">
<dt><code>GENERATE_XML</code></dt>
<dd>If the <code>GENERATE_XML</code> tag is set to <code>YES</code>, Doxygen will generate an XML file that captures the structure of the code including all documentation.
The default value is: <code>NO</code>.
<a id="cfg_xml_output"></a></dd>
<dt><code>XML_OUTPUT</code></dt>
<dd>The <code>XML_OUTPUT</code> tag is used to specify where the XML pages will be put. If a relative path is entered the value of <a href="#cfg_output_directory">OUTPUT_DIRECTORY</a> will be put in front of it.
The default directory is: <code>xml</code>.
This tag requires that the tag <a href="#cfg_generate_xml">GENERATE_XML</a> is set to <code>YES</code>. <a id="cfg_xml_programlisting"></a></dd>
<dt><code>XML_PROGRAMLISTING</code></dt>
<dd>If the <code>XML_PROGRAMLISTING</code> tag is set to <code>YES</code>, Doxygen will dump the program listings (including syntax highlighting and cross-referencing information) to the XML output. Note that enabling this will significantly increase the size of the XML output.
The default value is: <code>YES</code>.
This tag requires that the tag <a href="#cfg_generate_xml">GENERATE_XML</a> is set to <code>YES</code>. <a id="cfg_xml_ns_memb_file_scope"></a></dd>
<dt><code>XML_NS_MEMB_FILE_SCOPE</code></dt>
<dd>If the <code>XML_NS_MEMB_FILE_SCOPE</code> tag is set to <code>YES</code>, Doxygen will include namespace members in file scope as well, matching the HTML output.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_generate_xml">GENERATE_XML</a> is set to <code>YES</code>.</dd>
</dl>

## Configuration options related to the DOCBOOK output {#config_docbook}


<a id="cfg_generate_docbook"></a>

<dl class="doxyVariableList">
<dt><code>GENERATE_DOCBOOK</code></dt>
<dd>If the <code>GENERATE_DOCBOOK</code> tag is set to <code>YES</code>, Doxygen will generate Docbook files that can be used to generate PDF.
The default value is: <code>NO</code>.
<a id="cfg_docbook_output"></a></dd>
<dt><code>DOCBOOK_OUTPUT</code></dt>
<dd>The <code>DOCBOOK_OUTPUT</code> tag is used to specify where the Docbook pages will be put. If a relative path is entered the value of <a href="#cfg_output_directory">OUTPUT_DIRECTORY</a> will be put in front of it.
The default directory is: <code>docbook</code>.
This tag requires that the tag <a href="#cfg_generate_docbook">GENERATE_DOCBOOK</a> is set to <code>YES</code>.</dd>
</dl>

## Configuration options for the AutoGen Definitions output {#config_autogen}


<a id="cfg_generate_autogen_def"></a>

<dl class="doxyVariableList">
<dt><code>GENERATE_AUTOGEN_DEF</code></dt>
<dd>If the <code>GENERATE_AUTOGEN_DEF</code> tag is set to <code>YES</code>, Doxygen will generate an AutoGen Definitions (see <a href="https://autogen.sourceforge.net/">https://autogen.sourceforge.net/</a>) file that captures the structure of the code including all documentation. Note that this feature is still experimental and incomplete at the moment.
The default value is: <code>NO</code>.</dd>
</dl>

## Configuration options related to Sqlite3 output {#config_sqlite3}


<a id="cfg_generate_sqlite3"></a>

<dl class="doxyVariableList">
<dt><code>GENERATE_SQLITE3</code></dt>
<dd>If the <code>GENERATE_SQLITE3</code> tag is set to <code>YES</code> Doxygen will generate a <code>Sqlite3</code> database with symbols found by Doxygen stored in tables.
The default value is: <code>NO</code>.
<a id="cfg_sqlite3_output"></a></dd>
<dt><code>SQLITE3_OUTPUT</code></dt>
<dd>The <code>SQLITE3_OUTPUT</code> tag is used to specify where the <code>Sqlite3</code> database will be put. If a relative path is entered the value of <a href="#cfg_output_directory">OUTPUT_DIRECTORY</a> will be put in front of it.
The default directory is: <code>sqlite3</code>.
This tag requires that the tag <a href="#cfg_generate_sqlite3">GENERATE_SQLITE3</a> is set to <code>YES</code>. <a id="cfg_sqlite3_recreate_db"></a></dd>
<dt><code>SQLITE3_RECREATE_DB</code></dt>
<dd>The <code>SQLITE3_RECREATE_DB</code> tag is set to <code>YES</code>, the existing doxygen_sqlite3.db database file will be recreated with each Doxygen run. If set to <code>NO</code>, Doxygen will warn if a database file is already found and not modify it.
The default value is: <code>YES</code>.
This tag requires that the tag <a href="#cfg_generate_sqlite3">GENERATE_SQLITE3</a> is set to <code>YES</code>.</dd>
</dl>

## Configuration options related to the Perl module output {#config_perlmod}


<a id="cfg_generate_perlmod"></a>

<dl class="doxyVariableList">
<dt><code>GENERATE_PERLMOD</code></dt>
<dd>If the <code>GENERATE_PERLMOD</code> tag is set to <code>YES</code>, Doxygen will generate a Perl module file that captures the structure of the code including all documentation. 
<br/>
Note that this feature is still experimental and incomplete at the moment.
The default value is: <code>NO</code>.
<a id="cfg_perlmod_latex"></a></dd>
<dt><code>PERLMOD_LATEX</code></dt>
<dd>If the <code>PERLMOD_LATEX</code> tag is set to <code>YES</code>, Doxygen will generate the necessary <code>Makefile</code> rules, <code>Perl</code> scripts and <code>$\mbox{\LaTeX}$</code> code to be able to generate PDF and DVI output from the Perl module output.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_generate_perlmod">GENERATE_PERLMOD</a> is set to <code>YES</code>. <a id="cfg_perlmod_pretty"></a></dd>
<dt><code>PERLMOD_PRETTY</code></dt>
<dd>If the <code>PERLMOD_PRETTY</code> tag is set to <code>YES</code>, the Perl module output will be nicely formatted so it can be parsed by a human reader. This is useful if you want to understand what is going on. On the other hand, if this tag is set to <code>NO</code>, the size of the Perl module output will be much smaller and Perl will parse it just the same.
The default value is: <code>YES</code>.
This tag requires that the tag <a href="#cfg_generate_perlmod">GENERATE_PERLMOD</a> is set to <code>YES</code>. <a id="cfg_perlmod_makevar_prefix"></a></dd>
<dt><code>PERLMOD_MAKEVAR_PREFIX</code></dt>
<dd>The names of the make variables in the generated <code>doxyrules.make</code> file are prefixed with the string contained in <code>PERLMOD_MAKEVAR_PREFIX</code>. This is useful so different <code>doxyrules.make</code> files included by the same <code>Makefile</code> don't overwrite each other's variables.
This tag requires that the tag <a href="#cfg_generate_perlmod">GENERATE_PERLMOD</a> is set to <code>YES</code>.</dd>
</dl>

## Configuration options related to the preprocessor {#config_preprocessor}


<a id="cfg_enable_preprocessing"></a>

<dl class="doxyVariableList">
<dt><code>ENABLE_PREPROCESSING</code></dt>
<dd>If the <code>ENABLE_PREPROCESSING</code> tag is set to <code>YES</code>, Doxygen will evaluate all C-preprocessor directives found in the sources and include files.
The default value is: <code>YES</code>.
<a id="cfg_macro_expansion"></a></dd>
<dt><code>MACRO_EXPANSION</code></dt>
<dd>If the <code>MACRO_EXPANSION</code> tag is set to <code>YES</code>, Doxygen will expand all macro names in the source code. If set to <code>NO</code>, only conditional compilation will be performed. Macro expansion can be done in a controlled way by setting <a href="#cfg_expand_only_predef">EXPAND_ONLY_PREDEF</a> to <code>YES</code>.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_enable_preprocessing">ENABLE_PREPROCESSING</a> is set to <code>YES</code>. <a id="cfg_expand_only_predef"></a></dd>
<dt><code>EXPAND_ONLY_PREDEF</code></dt>
<dd>If the <code>EXPAND_ONLY_PREDEF</code> and <a href="#cfg_macro_expansion">MACRO_EXPANSION</a> tags are both set to <code>YES</code> then the macro expansion is limited to the macros specified with the <a href="#cfg_predefined">PREDEFINED</a> and <a href="#cfg_expand_as_defined">EXPAND_AS_DEFINED</a> tags.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_enable_preprocessing">ENABLE_PREPROCESSING</a> is set to <code>YES</code>. <a id="cfg_search_includes"></a></dd>
<dt><code>SEARCH_INCLUDES</code></dt>
<dd>If the <code>SEARCH_INCLUDES</code> tag is set to <code>YES</code>, the include files in the <a href="#cfg_include_path">INCLUDE_PATH</a> will be searched if a <code>#include</code> is found.
The default value is: <code>YES</code>.
This tag requires that the tag <a href="#cfg_enable_preprocessing">ENABLE_PREPROCESSING</a> is set to <code>YES</code>. <a id="cfg_include_path"></a></dd>
<dt><code>INCLUDE_PATH</code></dt>
<dd>The <code>INCLUDE_PATH</code> tag can be used to specify one or more directories that contain include files that are not input files but should be processed by the preprocessor.
Note that the <code>INCLUDE_PATH</code> is not recursive, so the setting of <a href="#cfg_recursive">RECURSIVE</a> has no effect here.
This tag requires that the tag <a href="#cfg_search_includes">SEARCH_INCLUDES</a> is set to <code>YES</code>. <a id="cfg_include_file_patterns"></a></dd>
<dt><code>INCLUDE_FILE_PATTERNS</code></dt>
<dd>You can use the <code>INCLUDE_FILE_PATTERNS</code> tag to specify one or more wildcard patterns (like <code>*.h</code> and <code>*.hpp</code>) to filter out the header-files in the directories. If left blank, the patterns specified with <a href="#cfg_file_patterns">FILE_PATTERNS</a> will be used.
This tag requires that the tag <a href="#cfg_enable_preprocessing">ENABLE_PREPROCESSING</a> is set to <code>YES</code>. <a id="cfg_predefined"></a></dd>
<dt><code>PREDEFINED</code></dt>
<dd>The <code>PREDEFINED</code> tag can be used to specify one or more macro names that are defined before the preprocessor is started (similar to the <code>-D</code> option of e.g. <code>gcc</code>). The argument of the tag is a list of macros of the form: <code>name</code> or <code>name=definition</code> (no spaces). If the definition and the <code>"="</code> are omitted, <code>"=1"</code> is assumed. To prevent a macro definition from being undefined via <code>#undef</code> or recursively expanded use the <code>:=</code> operator instead of the <code>=</code> operator.
This tag requires that the tag <a href="#cfg_enable_preprocessing">ENABLE_PREPROCESSING</a> is set to <code>YES</code>. <a id="cfg_expand_as_defined"></a></dd>
<dt><code>EXPAND_AS_DEFINED</code></dt>
<dd>If the <a href="#cfg_macro_expansion">MACRO_EXPANSION</a> and <a href="#cfg_expand_only_predef">EXPAND_ONLY_PREDEF</a> tags are set to <code>YES</code> then this tag can be used to specify a list of macro names that should be expanded. The macro definition that is found in the sources will be used. Use the <a href="#cfg_predefined">PREDEFINED</a> tag if you want to use a different macro definition that overrules the definition found in the source code.
This tag requires that the tag <a href="#cfg_enable_preprocessing">ENABLE_PREPROCESSING</a> is set to <code>YES</code>. <a id="cfg_skip_function_macros"></a></dd>
<dt><code>SKIP_FUNCTION_MACROS</code></dt>
<dd>If the <code>SKIP_FUNCTION_MACROS</code> tag is set to <code>YES</code> then Doxygen's preprocessor will remove all references to function-like macros that are alone on a line, have an all uppercase name, and do not end with a semicolon. Such function macros are typically used for boiler-plate code, and will confuse the parser if not removed.
The default value is: <code>YES</code>.
This tag requires that the tag <a href="#cfg_enable_preprocessing">ENABLE_PREPROCESSING</a> is set to <code>YES</code>.</dd>
</dl>

## Configuration options related to external references {#config_external}


<a id="cfg_tagfiles"></a>

<dl class="doxyVariableList">
<dt><code>TAGFILES</code></dt>
<dd>The <code>TAGFILES</code> tag can be used to specify one or more tag files.
For each tag file the location of the external documentation should be added. The format of a tag file without this location is as follows:
<pre><code>  TAGFILES = file1 file2 ...
</code></pre>
Adding location for the tag files is done as follows:
<pre><code>  TAGFILES = file1=loc1 "file2 = loc2" ...
</code></pre>
where <code>loc1</code> and <code>loc2</code> can be relative or absolute paths or URLs. See the section <a href="/web-doxygen/docs/pages/external">Linking to external documentation</a> for more information about the use of tag files.
:::info
Each tag file must have a unique name (where the name does <em>NOT</em> include the path). If a tag file is not located in the directory in which Doxygen is run, you must also specify the path to the tagfile here.
:::
<a id="cfg_generate_tagfile"></a></dd>
<dt><code>GENERATE_TAGFILE</code></dt>
<dd>When a file name is specified after <code>GENERATE_TAGFILE</code>, Doxygen will create a tag file that is based on the input files it reads. See section <a href="/web-doxygen/docs/pages/external">Linking to external documentation</a> for more information about the usage of tag files.
<a id="cfg_allexternals"></a></dd>
<dt><code>ALLEXTERNALS</code></dt>
<dd>If the <code>ALLEXTERNALS</code> tag is set to <code>YES</code>, all external classes and namespaces will be listed in the class and namespace index. If set to <code>NO</code>, only the inherited external classes will be listed.
The default value is: <code>NO</code>.
<a id="cfg_external_groups"></a></dd>
<dt><code>EXTERNAL_GROUPS</code></dt>
<dd>If the <code>EXTERNAL_GROUPS</code> tag is set to <code>YES</code>, all external groups will be listed in the topic index. If set to <code>NO</code>, only the current project's groups will be listed.
The default value is: <code>YES</code>.
<a id="cfg_external_pages"></a></dd>
<dt><code>EXTERNAL_PAGES</code></dt>
<dd>If the <code>EXTERNAL_PAGES</code> tag is set to <code>YES</code>, all external pages will be listed in the related pages index. If set to <code>NO</code>, only the current project's pages will be listed.
The default value is: <code>YES</code>.</dd>
</dl>

## Configuration options related to diagram generator tools {#config_dot}


<a id="cfg_hide_undoc_relations"></a>

<dl class="doxyVariableList">
<dt><code>HIDE_UNDOC_RELATIONS</code></dt>
<dd>If set to <code>YES</code> the inheritance and collaboration graphs will hide inheritance and usage relations if the target is undocumented or is not a class.
The default value is: <code>YES</code>.
<a id="cfg_have_dot"></a></dd>
<dt><code>HAVE_DOT</code></dt>
<dd>If you set the <code>HAVE_DOT</code> tag to <code>YES</code> then Doxygen will assume the <code>dot</code> tool is available from the <code>path</code>. This tool is part of <a href="https://www.graphviz.org/">Graphviz</a>, a graph visualization toolkit from AT&amp;T and Lucent Bell Labs. The other options in this section have no effect if this option is set to <code>NO</code>
The default value is: <code>NO</code>.
<a id="cfg_dot_num_threads"></a></dd>
<dt><code>DOT_NUM_THREADS</code></dt>
<dd>The <code>DOT_NUM_THREADS</code> specifies the number of <code>dot</code> invocations Doxygen is allowed to run in parallel. When set to <code>0</code> Doxygen will base this on the number of processors available in the system. You can set it explicitly to a value larger than 0 to get control over the balance between CPU load and processing speed.
Minimum value: <code>0</code>, maximum value: <code>32</code>, default value: <code>0</code>.
This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <code>YES</code>. <a id="cfg_dot_common_attr"></a></dd>
<dt><code>DOT_COMMON_ATTR</code></dt>
<dd><code>DOT_COMMON_ATTR</code> is common attributes for nodes, edges and labels of subgraphs. When you want a differently looking font in the dot files that Doxygen generates you can specify fontname, fontcolor and fontsize attributes. For details please see <a href="https://graphviz.org/doc/info/attrs.html">Node, Edge and Graph Attributes specification</a> You need to make sure dot is able to find the font, which can be done by putting it in a standard location or by setting the <code>DOTFONTPATH</code> environment variable or by setting <a href="#cfg_dot_fontpath">DOT_FONTPATH</a> to the directory containing the font. Default graphviz fontsize is 14.
The default value is: <code>fontname=Helvetica,fontsize=10</code>.
This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <code>YES</code>. <a id="cfg_dot_edge_attr"></a></dd>
<dt><code>DOT_EDGE_ATTR</code></dt>
<dd><code>DOT_EDGE_ATTR</code> is concatenated with <a href="#cfg_dot_common_attr">DOT_COMMON_ATTR</a>. For elegant style you can add 'arrowhead=open, arrowtail=open, arrowsize=0.5'. <a href="https://graphviz.org/doc/info/arrows.html">Complete documentation about arrows shapes.</a>
The default value is: <code>labelfontname=Helvetica,labelfontsize=10</code>.
This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <code>YES</code>. <a id="cfg_dot_node_attr"></a></dd>
<dt><code>DOT_NODE_ATTR</code></dt>
<dd><code>DOT_NODE_ATTR</code> is concatenated with <a href="#cfg_dot_common_attr">DOT_COMMON_ATTR</a>. For view without boxes around nodes set 'shape=plain' or 'shape=plaintext' <a href="https://www.graphviz.org/doc/info/shapes.html">Shapes specification</a>
The default value is: <code>shape=box,height=0.2,width=0.4</code>.
This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <code>YES</code>. <a id="cfg_dot_fontpath"></a></dd>
<dt><code>DOT_FONTPATH</code></dt>
<dd>You can set the path where <code>dot</code> can find font specified with fontname in <a href="#cfg_dot_common_attr">DOT_COMMON_ATTR</a> and others dot attributes.
This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <code>YES</code>. <a id="cfg_class_graph"></a></dd>
<dt><code>CLASS_GRAPH</code></dt>
<dd>If the <code>CLASS_GRAPH</code> tag is set to <code>YES</code> or <code>GRAPH</code> or <code>BUILTIN</code> then Doxygen will generate a graph for each documented class showing the direct and indirect inheritance relations. In case the <code>CLASS_GRAPH</code> tag is set to <code>YES</code> or <code>GRAPH</code> and <a href="#cfg_have_dot">HAVE_DOT</a> is enabled as well, then <code>dot</code> will be used to draw the graph. In case the <code>CLASS_GRAPH</code> tag is set to <code>YES</code> and <a href="#cfg_have_dot">HAVE_DOT</a> is disabled or if the <code>CLASS_GRAPH</code> tag is set to <code>BUILTIN</code>, then the built-in generator will be used. If the <code>CLASS_GRAPH</code> tag is set to <code>TEXT</code> the direct and indirect inheritance relations will be shown as texts / links. Explicit enabling an inheritance graph or choosing a different representation for an inheritance graph of a specific class, can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmdinheritancegraph">\inheritancegraph</a>. Disabling an inheritance graph can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmdhideinheritancegraph">\hideinheritancegraph</a>.
Possible values are: <code>NO</code>, <code>YES</code>, <code>TEXT</code>, <code>GRAPH</code> and <code>BUILTIN</code>.
The default value is: <code>YES</code>.
<a id="cfg_collaboration_graph"></a></dd>
<dt><code>COLLABORATION_GRAPH</code></dt>
<dd>If the <code>COLLABORATION_GRAPH</code> tag is set to <code>YES</code> then Doxygen will generate a graph for each documented class showing the direct and indirect implementation dependencies (inheritance, containment, and class references variables) of the class with other documented classes. Explicit enabling a collaboration graph, when <code>COLLABORATION_GRAPH</code> is set to <code>NO</code>, can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmdcollaborationgraph">\collaborationgraph</a>. Disabling a collaboration graph can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmdhidecollaborationgraph">\hidecollaborationgraph</a>.
The default value is: <code>YES</code>.
This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <code>YES</code>. <a id="cfg_group_graphs"></a></dd>
<dt><code>GROUP_GRAPHS</code></dt>
<dd>If the <code>GROUP_GRAPHS</code> tag is set to <code>YES</code> then Doxygen will generate a graph for groups, showing the direct groups dependencies. Explicit enabling a group dependency graph, when <code>GROUP_GRAPHS</code> is set to <code>NO</code>, can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmdgroupgraph">\groupgraph</a>. Disabling a directory graph can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmdhidegroupgraph">\hidegroupgraph</a>.
See also the chapter <a href="/web-doxygen/docs/pages/grouping">Grouping</a> in the manual.
The default value is: <code>YES</code>.
This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <code>YES</code>. <a id="cfg_uml_look"></a></dd>
<dt><code>UML_LOOK</code></dt>
<dd>If the <code>UML_LOOK</code> tag is set to <code>YES</code>, Doxygen will generate inheritance and collaboration diagrams in a style similar to the OMG's Unified Modeling Language.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <code>YES</code>. <a id="cfg_uml_limit_num_fields"></a></dd>
<dt><code>UML_LIMIT_NUM_FIELDS</code></dt>
<dd>If the <a href="#cfg_uml_look">UML_LOOK</a> tag is enabled, the fields and methods are shown inside the class node. If there are many fields or methods and many nodes the graph may become too big to be useful. The <code>UML_LIMIT_NUM_FIELDS</code> threshold limits the number of items for each type to make the size more manageable. Set this to 0 for no limit. Note that the threshold may be exceeded by 50% before the limit is enforced. So when you set the threshold to 10, up to 15 fields may appear, but if the number exceeds 15, the total amount of fields shown is limited to 10.
Minimum value: <code>0</code>, maximum value: <code>100</code>, default value: <code>10</code>.
This tag requires that the tag <a href="#cfg_uml_look">UML_LOOK</a> is set to <code>YES</code>. <a id="cfg_uml_max_edge_labels"></a></dd>
<dt><code>UML_MAX_EDGE_LABELS</code></dt>
<dd>If the <a href="#cfg_uml_look">UML_LOOK</a> tag is enabled, field labels are shown along the edge between two class nodes. If there are many fields and many nodes the graph may become too cluttered. The <code>UML_MAX_EDGE_LABELS</code> threshold limits the number of items to make the size more manageable. Set this to 0 for no limit.
Minimum value: <code>0</code>, maximum value: <code>100</code>, default value: <code>10</code>.
This tag requires that the tag <a href="#cfg_uml_look">UML_LOOK</a> is set to <code>YES</code>. <a id="cfg_dot_uml_details"></a></dd>
<dt><code>DOT_UML_DETAILS</code></dt>
<dd>If the <code>DOT_UML_DETAILS</code> tag is set to <code>NO</code>, Doxygen will show attributes and methods without types and arguments in the UML graphs. If the <code>DOT_UML_DETAILS</code> tag is set to <code>YES</code>, Doxygen will add type and arguments for attributes and methods in the UML graphs. If the <code>DOT_UML_DETAILS</code> tag is set to <code>NONE</code>, Doxygen will not generate fields with class member information in the UML graphs. The class diagrams will look similar to the default class diagrams but using UML notation for the relationships.
Possible values are: <code>NO</code>, <code>YES</code> and <code>NONE</code>.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_uml_look">UML_LOOK</a> is set to <code>YES</code>. <a id="cfg_dot_wrap_threshold"></a></dd>
<dt><code>DOT_WRAP_THRESHOLD</code></dt>
<dd>The <code>DOT_WRAP_THRESHOLD</code> tag can be used to set the maximum number of characters to display on a single line. If the actual line length exceeds this threshold significantly it will be wrapped across multiple lines. Some heuristics are applied to avoid ugly line breaks.
Minimum value: <code>0</code>, maximum value: <code>1000</code>, default value: <code>17</code>.
This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <code>YES</code>. <a id="cfg_template_relations"></a></dd>
<dt><code>TEMPLATE_RELATIONS</code></dt>
<dd>If the <code>TEMPLATE_RELATIONS</code> tag is set to <code>YES</code> then the inheritance and collaboration graphs will show the relations between templates and their instances.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <code>YES</code>. <a id="cfg_include_graph"></a></dd>
<dt><code>INCLUDE_GRAPH</code></dt>
<dd>If the <code>INCLUDE_GRAPH</code>, <a href="#cfg_enable_preprocessing">ENABLE_PREPROCESSING</a> and <a href="#cfg_search_includes">SEARCH_INCLUDES</a> tags are set to <code>YES</code> then Doxygen will generate a graph for each documented file showing the direct and indirect include dependencies of the file with other documented files. Explicit enabling an include graph, when <code>INCLUDE_GRAPH</code> is is set to <code>NO</code>, can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmdincludegraph">\includegraph</a>. Disabling an include graph can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmdhideincludegraph">\hideincludegraph</a>.
The default value is: <code>YES</code>.
This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <code>YES</code>. <a id="cfg_included_by_graph"></a></dd>
<dt><code>INCLUDED_BY_GRAPH</code></dt>
<dd>If the <code>INCLUDED_BY_GRAPH</code>, <a href="#cfg_enable_preprocessing">ENABLE_PREPROCESSING</a> and <a href="#cfg_search_includes">SEARCH_INCLUDES</a> tags are set to <code>YES</code> then Doxygen will generate a graph for each documented file showing the direct and indirect include dependencies of the file with other documented files. Explicit enabling an included by graph, when <code>INCLUDED_BY_GRAPH</code> is set to <code>NO</code>, can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmdincludedbygraph">\includedbygraph</a>. Disabling an included by graph can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmdhideincludedbygraph">\hideincludedbygraph</a>.
The default value is: <code>YES</code>.
This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <code>YES</code>. <a id="cfg_call_graph"></a></dd>
<dt><code>CALL_GRAPH</code></dt>
<dd>If the <code>CALL_GRAPH</code> tag is set to <code>YES</code> then Doxygen will generate a call dependency graph for every global function or class method. 
<br/>
Note that enabling this option will significantly increase the time of a run. So in most cases it will be better to enable call graphs for selected functions only using the <a href="/web-doxygen/docs/pages/commands/#cmdcallgraph">\callgraph</a> command. Disabling a call graph can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmdhidecallgraph">\hidecallgraph</a>.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <code>YES</code>. <a id="cfg_caller_graph"></a></dd>
<dt><code>CALLER_GRAPH</code></dt>
<dd>If the <code>CALLER_GRAPH</code> tag is set to <code>YES</code> then Doxygen will generate a caller dependency graph for every global function or class method. 
<br/>
Note that enabling this option will significantly increase the time of a run. So in most cases it will be better to enable caller graphs for selected functions only using the <a href="/web-doxygen/docs/pages/commands/#cmdcallergraph">\callergraph</a> command. Disabling a caller graph can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmdhidecallergraph">\hidecallergraph</a>.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <code>YES</code>. <a id="cfg_graphical_hierarchy"></a></dd>
<dt><code>GRAPHICAL_HIERARCHY</code></dt>
<dd>If the <code>GRAPHICAL_HIERARCHY</code> tag is set to <code>YES</code> then Doxygen will graphical hierarchy of all classes instead of a textual one.
The default value is: <code>YES</code>.
This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <code>YES</code>. <a id="cfg_directory_graph"></a></dd>
<dt><code>DIRECTORY_GRAPH</code></dt>
<dd>If the <code>DIRECTORY_GRAPH</code> tag is set to <code>YES</code> then Doxygen will show the dependencies a directory has on other directories in a graphical way. The dependency relations are determined by the <code>#include</code> relations between the files in the directories. Explicit enabling a directory graph, when <code>DIRECTORY_GRAPH</code> is set to <code>NO</code>, can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmddirectorygraph">\directorygraph</a>. Disabling a directory graph can be accomplished by means of the command <a href="/web-doxygen/docs/pages/commands/#cmdhidedirectorygraph">\hidedirectorygraph</a>.
The default value is: <code>YES</code>.
This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <code>YES</code>. <a id="cfg_dir_graph_max_depth"></a></dd>
<dt><code>DIR_GRAPH_MAX_DEPTH</code></dt>
<dd>The <code>DIR_GRAPH_MAX_DEPTH</code> tag can be used to limit the maximum number of levels of child directories generated in directory dependency graphs by <code>dot</code>.
Minimum value: <code>1</code>, maximum value: <code>25</code>, default value: <code>1</code>.
This tag requires that the tag <a href="#cfg_directory_graph">DIRECTORY_GRAPH</a> is set to <code>YES</code>. <a id="cfg_dot_image_format"></a></dd>
<dt><code>DOT_IMAGE_FORMAT</code></dt>
<dd>The <code>DOT_IMAGE_FORMAT</code> tag can be used to set the image format of the images generated by <code>dot</code>. For an explanation of the image formats see the section output formats in the documentation of the <code>dot</code> tool (<a href="https://www.graphviz.org/">Graphviz</a>). 
<br/>
Note the formats <code>svg:cairo</code> and <code>svg:cairo:cairo</code> cannot be used in combination with <a href="#cfg_interactive_svg">INTERACTIVE_SVG</a> (the <a href="#cfg_interactive_svg">INTERACTIVE_SVG</a> will be set to <code>NO</code>).
Possible values are: <code>png</code>, <code>jpg</code>, <code>gif</code>, <code>svg</code>, <code>png:gd</code>, <code>png:gd:gd</code>, <code>png:cairo</code>, <code>png:cairo:gd</code>, <code>png:cairo:cairo</code>, <code>png:cairo:gdiplus</code>, <code>png:gdiplus</code>, <code>png:gdiplus:gdiplus</code>, <code>svg:cairo</code>, <code>svg:cairo:cairo</code>, <code>svg:svg</code>, <code>svg:svg:core</code>, <code>gif:cairo</code>, <code>gif:cairo:gd</code>, <code>gif:cairo:gdiplus</code>, <code>gif:gdiplus</code>, <code>gif:gdiplus:gdiplus</code>, <code>gif:gd</code>, <code>gif:gd:gd</code>, <code>jpg:cairo</code>, <code>jpg:cairo:gd</code>, <code>jpg:cairo:gdiplus</code>, <code>jpg:gd</code>, <code>jpg:gd:gd</code>, <code>jpg:gdiplus</code> and <code>jpg:gdiplus:gdiplus</code>.
The default value is: <code>png</code>.
This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <code>YES</code>. <a id="cfg_interactive_svg"></a></dd>
<dt><code>INTERACTIVE_SVG</code></dt>
<dd>If <a href="#cfg_dot_image_format">DOT_IMAGE_FORMAT</a> is set to <code>svg</code> or <code>svg:svg</code> or <code>svg:svg:core</code>, then this option can be set to <code>YES</code> to enable generation of interactive SVG images that allow zooming and panning. 
<br/>
Note that this requires a modern browser other than Internet Explorer. Tested and working are Firefox, Chrome, Safari, and Opera. 
<br/>
Note This option will be automatically disabled when <a href="#cfg_dot_image_format">DOT_IMAGE_FORMAT</a> is set to <code>svg:cairo</code> or <code>svg:cairo:cairo</code>.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <code>YES</code>. <a id="cfg_dot_path"></a></dd>
<dt><code>DOT_PATH</code></dt>
<dd>The <code>DOT_PATH</code> tag can be used to specify the path where the <code>dot</code> tool can be found. If left blank, it is assumed the <code>dot</code> tool can be found in the <code>path</code>.
This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <code>YES</code>. <a id="cfg_dotfile_dirs"></a></dd>
<dt><code>DOTFILE_DIRS</code></dt>
<dd>The <code>DOTFILE_DIRS</code> tag can be used to specify one or more directories that contain dot files that are included in the documentation (see the <a href="/web-doxygen/docs/pages/commands/#cmddotfile">\dotfile</a> command).
This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <code>YES</code>. <a id="cfg_dia_path"></a></dd>
<dt><code>DIA_PATH</code></dt>
<dd>You can include diagrams made with dia in Doxygen documentation. Doxygen will then run dia to produce the diagram and insert it in the documentation. The DIA_PATH tag allows you to specify the directory where the dia binary resides. If left empty dia is assumed to be found in the default search path.
<a id="cfg_diafile_dirs"></a></dd>
<dt><code>DIAFILE_DIRS</code></dt>
<dd>The <code>DIAFILE_DIRS</code> tag can be used to specify one or more directories that contain dia files that are included in the documentation (see the <a href="/web-doxygen/docs/pages/commands/#cmddiafile">\diafile</a> command).
<a id="cfg_plantuml_jar_path"></a></dd>
<dt><code>PLANTUML_JAR_PATH</code></dt>
<dd>When using PlantUML, the <code>PLANTUML_JAR_PATH</code> tag should be used to specify the path where java can find the <code>plantuml.jar</code> file or to the filename of <code>jar</code> file to be used. If left blank, it is assumed PlantUML is not used or called during a preprocessing step. Doxygen will generate a warning when it encounters a <a href="/web-doxygen/docs/pages/commands/#cmdstartuml">\startuml</a> command in this case and will not generate output for the diagram.
<a id="cfg_plantuml_cfg_file"></a></dd>
<dt><code>PLANTUML_CFG_FILE</code></dt>
<dd>When using PlantUML, the <code>PLANTUML_CFG_FILE</code> tag can be used to specify a configuration file for PlantUML.
<a id="cfg_plantuml_include_path"></a></dd>
<dt><code>PLANTUML_INCLUDE_PATH</code></dt>
<dd>When using PlantUML, the specified paths are searched for files specified by the <code>!include</code> statement in a PlantUML block.
<a id="cfg_plantumlfile_dirs"></a></dd>
<dt><code>PLANTUMLFILE_DIRS</code></dt>
<dd>The <code>PLANTUMLFILE_DIRS</code> tag can be used to specify one or more directories that contain PlantUml files that are included in the documentation (see the <a href="/web-doxygen/docs/pages/commands/#cmdplantumlfile">\plantumlfile</a> command).
<a id="cfg_dot_graph_max_nodes"></a></dd>
<dt><code>DOT_GRAPH_MAX_NODES</code></dt>
<dd>The <code>DOT_GRAPH_MAX_NODES</code> tag can be used to set the maximum number of nodes that will be shown in the graph. If the number of nodes in a graph becomes larger than this value, Doxygen will truncate the graph, which is visualized by representing a node as a red box. Note that if the number of direct children of the root node in a graph is already larger than <code>DOT_GRAPH_MAX_NODES</code> then the graph will not be shown at all. Also note that the size of a graph can be further restricted by <a href="#cfg_max_dot_graph_depth">MAX_DOT_GRAPH_DEPTH</a>.
Minimum value: <code>0</code>, maximum value: <code>10000</code>, default value: <code>50</code>.
This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <code>YES</code>. <a id="cfg_max_dot_graph_depth"></a></dd>
<dt><code>MAX_DOT_GRAPH_DEPTH</code></dt>
<dd>The <code>MAX_DOT_GRAPH_DEPTH</code> tag can be used to set the maximum depth of the graphs generated by <code>dot</code>. A depth value of 3 means that only nodes reachable from the root by following a path via at most 3 edges will be shown. Nodes that lay further from the root node will be omitted. Note that setting this option to 1 or 2 may greatly reduce the computation time needed for large code bases. Also note that the size of a graph can be further restricted by <a href="#cfg_dot_graph_max_nodes">DOT_GRAPH_MAX_NODES</a>. Using a depth of 0 means no depth restriction.
Minimum value: <code>0</code>, maximum value: <code>1000</code>, default value: <code>0</code>.
This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <code>YES</code>. <a id="cfg_dot_multi_targets"></a></dd>
<dt><code>DOT_MULTI_TARGETS</code></dt>
<dd>Set the <code>DOT_MULTI_TARGETS</code> tag to <code>YES</code> to allow dot to generate multiple output files in one run (i.e. multiple -o and -T options on the command line). This makes <code>dot</code> run faster, but since only newer versions of <code>dot</code> (&gt;1.8.10) support this, this feature is disabled by default.
The default value is: <code>NO</code>.
This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <code>YES</code>. <a id="cfg_generate_legend"></a></dd>
<dt><code>GENERATE_LEGEND</code></dt>
<dd>If the <code>GENERATE_LEGEND</code> tag is set to <code>YES</code> Doxygen will generate a legend page explaining the meaning of the various boxes and arrows in the dot generated graphs.
:::info
This tag requires that <a href="#cfg_uml_look">UML\_LOOK</a> isn't set, i.e. the Doxygen internal graphical representation for inheritance and collaboration diagrams is used.
:::
The default value is: <code>YES</code>.
This tag requires that the tag <a href="#cfg_have_dot">HAVE_DOT</a> is set to <code>YES</code>. <a id="cfg_dot_cleanup"></a></dd>
<dt><code>DOT_CLEANUP</code></dt>
<dd>If the <code>DOT_CLEANUP</code> tag is set to <code>YES</code>, Doxygen will remove the intermediate files that are used to generate the various graphs. 
<br/>
Note: This setting is not only used for dot files but also for msc temporary files.
The default value is: <code>YES</code>.
<a id="cfg_mscgen_tool"></a></dd>
<dt><code>MSCGEN_TOOL</code></dt>
<dd>You can define message sequence charts within Doxygen comments using the <a href="/web-doxygen/docs/pages/commands/#cmdmsc">\msc</a> command. If the <code>MSCGEN_TOOL</code> tag is left empty (the default), then Doxygen will use a built-in version of mscgen tool to produce the charts. Alternatively, the <code>MSCGEN_TOOL</code> tag can also specify the name an external tool. For instance, specifying <code>prog</code> as the value, Doxygen will call the tool as <code>prog -T &lt;outfile_format&gt; -o &lt;outputfile&gt; &lt;inputfile&gt;</code>. The external tool should support output file formats "png", "eps", "svg", and "ismap".
<a id="cfg_mscfile_dirs"></a></dd>
<dt><code>MSCFILE_DIRS</code></dt>
<dd>The <code>MSCFILE_DIRS</code> tag can be used to specify one or more directories that contain msc files that are included in the documentation (see the <a href="/web-doxygen/docs/pages/commands/#cmdmscfile">\mscfile</a> command).</dd>
</dl>

## Examples {#config_examples}


Suppose you have a simple project consisting of two files: a source file <code>example.cc</code> and a header file <code>example.h</code>. Then a minimal configuration file is as simple as:


<pre><code>INPUT            = example.cc example.h
</code></pre>


Assuming the example makes use of Qt classes and <code>perl</code> is located in <code>/usr/bin</code>, a more realistic configuration file would be:


<pre><code>PROJECT_NAME     = Example
INPUT            = example.cc example.h
WARNINGS         = YES
TAGFILES         = qt.tag
SEARCHENGINE     = NO
</code></pre>


To generate the documentation for the <a href="https://sourceforge.net/projects/qdbttabular/">QdbtTabular</a> package I have used the following configuration file:


<pre><code>PROJECT_NAME     = QdbtTabular
OUTPUT_DIRECTORY = html
WARNINGS         = YES
INPUT            = examples/examples.doc src
FILE_PATTERNS    = *.cc *.h
INCLUDE_PATH     = examples
TAGFILES         = qt.tag
SEARCHENGINE     = YES
</code></pre>


To regenerate the Qt-1.44 documentation from the sources, you could use the following configuration file:


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


For the Qt-2.1 sources I recommend to use the following settings:


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


Here Doxygen's preprocessor is used to substitute some macro names that are normally substituted by the C preprocessor, but without doing full macro expansion.
 
Go to the <a href="/docs/pages/commands/">next</a> section or return to the
 <a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
