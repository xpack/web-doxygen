---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /pages/doxywizard-usage
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - page

---

<div class="doxyPage">

# Doxywizard usage




<p>Doxywizard is a GUI front-end for configuring and running Doxygen.</p>


<p>When starting Doxywizard one can specify an existing configuration file to use as argument, otherwise the default settings will be used as a starting point.</p>


<p>When you start Doxywizard it will display the main window (the actual look depends on the platform used).</p>


<p><figure>
  <img src="/web-doxygen/img/doxygen-manual/doxywizard_main.png"></img>
  <figcaption>Main window</figcaption>
</figure></p>


<p>The user interface consists of the following sections:</p>


<dl class="doxyVariableList">
<dt><a href="#dw_menu">Menu options</a></dt>
<dd><p>In the menu bar the following parts are available: <a href="#dw_menu_file">File menu</a>, <a href="#dw_menu_settings">Settings menu</a> and <a href="#dw_menu_help">Help menu</a>.</p></dd>
<dt>Specify the working directory from which Doxygen will run</dt>
<dd><p>Using the <span class="doxyComputerOutput">Select...</span> button a directory can be selected. When Doxywizard is started with a configuration file or one is loaded using the open command (see: <a href="#dw_menu_file">File menu</a>) the directory of this settings file used as the working directory.</p></dd>
<dt>Configure Doxygen using the Wizard and/or Expert tab...</dt>
<dd>
<dl class="doxyVariableList">
<dt><a href="#dw_wizard">Wizard tab</a></dt>
<dd><p>with this tab it is possible to quickly configure the most important settings and leave the rest of the options to their defaults.</p></dd>
<dt><a href="#dw_expert">Expert tab</a></dt>
<dd><p>with this tab one gains access to the <a href="/web-doxygen/docs/pages/config">full set of configuration options</a>.</p></dd>
<dt><a href="#dw_run">Run tab</a></dt>
<dd><p>with this tab it is possible to run Doxygen and view the used settings.</p></dd>
</dl>
<p>Switching between these tabs is possible, e.g you could start with the wizard tab and then fine tune some settings by switching to the expert tab.</p>
</dd>
</dl>

<p>After Doxygen is configured you need to save (see: <a href="#dw_menu_file">File menu</a>) the configuration as a file to disk. This allows Doxygen to use the configuration and also allows running Doxygen again with the same settings at a later point in time.</p>


<p>Since some configuration options may use relative paths, be sure to select a working directory that is root of those paths. This is often the root of the source tree and will typically be correctly filled in if the configuration file is stored at this location as well.</p>


<p>Once the configuration file is saved and the working directory is set, you can run Doxygen based on the selected settings. Do this by switching to the <a href="#dw_run">Run</a> tab, and click the "Run Doxygen" button or by selecting the item "Run Doxygen" in the <a href="#dw_menu_settings">Settings menu</a>.</p>


<p>Once Doxygen runs you can cancel it by clicking the same button again. The output produced by Doxygen is captured and shown in the "Output produced by Doxygen" pane. Once Doxygen finishes, the log can be saved as a text file.</p>


## Wizard tab {#dw_wizard}


<p>The Wizard tab is divided into two panes</p>


<dl class="doxyVariableList">
<dt>Left pane</dt>
<dd><p>The main topics for easy setting up Doxygen. By clicking on a topic the corresponding settings will appear in the Right pane.</p></dd>
<dt>Right pane</dt>
<dd><p>The wizard's settings pane, in this pane you will find the settings that are available for the selected topic.</p></dd>
</dl>

<p>The wizard only gives the possibility to quickly setup Doxygen, for full control one should use the <a href="#dw_expert">Expert tab</a>.</p>


### Project settings {#dw_wizard_project}


<p>The fields in the Project pane speak for themselves. Once Doxygen has finished the Destination directory is where to look for the results. Doxygen will put each output format in a separate sub-directory by default.</p>


<p><figure>
  <img src="/web-doxygen/img/doxygen-manual/doxywizard_page1.png"></img>
  <figcaption>Wizard tab: Project settings</figcaption>
</figure></p>


### Mode of operating {#dw_wizard_mode}


<p>The Mode pane allows you to select how Doxygen will look at your sources. The default is to only look for things that have been documented. Furthermore, the terminology used in the output can be changed to better match the main programming language used (this doesn't affect the way Doxygen parses your source code).</p>


<p><figure>
  <img src="/web-doxygen/img/doxygen-manual/doxywizard_page2.png"></img>
  <figcaption>Wizard tab: Mode of operating</figcaption>
</figure></p>


### Output to produce {#dw_wizard_output}


<p>The Output pane allows you to select what kinds of output Doxygen will produce. For HTML and <code>{\LaTeX}</code> there are additional options available.</p>


<p><figure>
  <img src="/web-doxygen/img/doxygen-manual/doxywizard_page3.png"></img>
  <figcaption>Wizard tab: Output to produce</figcaption>
</figure></p>


### Diagrams to generate {#dw_wizard_diagrams}


<p>Doxygen can produce a number of diagrams. Using the Diagrams pane you can select which ones to generate. For most diagrams the <span class="doxyComputerOutput">dot</span> tool of the <a href="https://www.graphviz.org">GraphViz</a> package is needed. This needs to be installed separately.</p>


<p><figure>
  <img src="/web-doxygen/img/doxygen-manual/doxywizard_page4.png"></img>
  <figcaption>Wizard tab: Diagrams to generate</figcaption>
</figure></p>


## Expert tab {#dw_expert}


<p>The Expert tab is divided into a number of panes:</p>


<dl class="doxyVariableList">
<dt>Top left pane</dt>
<dd><p>The Topics pane (i.e. sections in the configuration file) that are available. By clicking on a topic the corresponding settings will appear in the Right pane.</p></dd>
<dt>Bottom left pane</dt>
<dd><p>The help pane, this will be updated when one hovers over the name of a setting in the Right pane.</p></dd>
<dt>Right pane</dt>
<dd><p>The Settings pane, in this pane you will find the settings that are available for the selected topic. In case the name for a setting is colored red, the setting has a non-default value. In case a setting is grayed out, the setting is depending on another setting that is disabled. Which setting it depends on is indicated in the help pane on the bottom left.</p></dd>
</dl>

<p><figure>
  <img src="/web-doxygen/img/doxygen-manual/doxywizard_expert.png"></img>
  <figcaption>Some options from the Expert tab</figcaption>
</figure></p>


<p>The representation of the input field depends on the type of the configuration option.</p>


<ul class="doxyList ">
<li>For each boolean option (those options that are answered with <span class="doxyComputerOutput">YES</span> or <span class="doxyComputerOutput">NO</span> in the configuration file) there is a check-box. A typical field looks like:
<br/>
 
<figure>
  <img src="/web-doxygen/img/doxygen-manual/expert_bool.png" class="inline"></img>
</figure></li>
<li>For items taking one of a fixed set of values (like <a href="/web-doxygen/docs/pages/config/#cfg_output_language">OUTPUT_LANGUAGE</a>) a combo box is used. A typical field looks like:
<br/>
 
<figure>
  <img src="/web-doxygen/img/doxygen-manual/expert_enum.png" class="inline"></img>
</figure></li>
<li>For items taking an integer value from a range, a spinbox is used. A typical field looks like:
<br/>
 
<figure>
  <img src="/web-doxygen/img/doxygen-manual/expert_int.png" class="inline"></img>
</figure></li>
<li>For free form string-type options there is a one line edit field. A typical field looks like:
<br/>
 
<figure>
  <img src="/web-doxygen/img/doxygen-manual/expert_string_string.png" class="inline"></img>
</figure>
 
 
<br/>
Additionally, when the string field should contain a file or a folder name, there are the special buttons 
<figure>
  <img src="/web-doxygen/img/doxygen-manual/file.png" height="14px" class="inline"></img>
</figure>
 
 and 
<figure>
  <img src="/web-doxygen/img/doxygen-manual/folder.png" height="14px" class="inline"></img>
</figure>
 
 that start a file / folder selection dialog. A typical field for a file looks like:
<br/>
 
<figure>
  <img src="/web-doxygen/img/doxygen-manual/expert_string_file.png" class="inline"></img>
</figure>
 
 
<br/>
and a folder looks like:
<br/>
 
<figure>
  <img src="/web-doxygen/img/doxygen-manual/expert_string_dir.png" class="inline"></img>
</figure>
 
 
<br/>
and in case both a file or a folder is allowed, the look is:
<br/>
 
<figure>
  <img src="/web-doxygen/img/doxygen-manual/expert_string_filedir.png" class="inline"></img>
</figure>
 
 
<br/>
In case a file represents an image, Doxygen also tries to display the selected image. Then a typical field looks like:
<br/>
 
<figure>
  <img src="/web-doxygen/img/doxygen-manual/expert_string_image.png" class="inline"></img>
</figure></li>
<li>For options taking a list of strings, an editor field is shown with a non-editable list below it. The 
<figure>
  <img src="/web-doxygen/img/doxygen-manual/add.png" height="14px" class="inline"></img>
</figure>
 
 button adds the string in the editor field to the list and a the 
<figure>
  <img src="/web-doxygen/img/doxygen-manual/del.png" height="14px" class="inline"></img>
</figure>
 
 button removes the selected string from the list. The 
<figure>
  <img src="/web-doxygen/img/doxygen-manual/refresh.png" height="14px" class="inline"></img>
</figure>
 
 button can be clicked to replace the selected item in the list with the string entered in the editor field. A typical field looks like:
<br/>
 
<figure>
  <img src="/web-doxygen/img/doxygen-manual/expert_list_string.png" class="inline"></img>
</figure>
 
 
<br/>
additionally when the list contains file and / or folder names, there are special buttons 
<figure>
  <img src="/web-doxygen/img/doxygen-manual/file.png" height="14px" class="inline"></img>
</figure>
 
 and 
<figure>
  <img src="/web-doxygen/img/doxygen-manual/folder.png" height="14px" class="inline"></img>
</figure>
 
 that start a file / folder selection dialog. A typical field would for a file looks like:
<br/>
 
<figure>
  <img src="/web-doxygen/img/doxygen-manual/expert_list_file.png" class="inline"></img>
</figure>
 
 
<br/>
and for a folder it looks like
<br/>
 
<figure>
  <img src="/web-doxygen/img/doxygen-manual/expert_list_dir.png" class="inline"></img>
</figure>
 
 
<br/>
and in case both files and folders are allowed, the look is:
<br/>
 
<figure>
  <img src="/web-doxygen/img/doxygen-manual/expert_list_filedir.png" class="inline"></img>
</figure></li>
</ul>

## Run tab {#dw_run}


<p>The run tab gives the possibility to run Doxygen with the given settings, see the HTML results, see the settings used and save the output as displayed in the output pane.</p>


<p><figure>
  <img src="/web-doxygen/img/doxygen-manual/doxywizard_run.png"></img>
  <figcaption>Run tab</figcaption>
</figure></p>


<dl class="doxyVariableList">
<dt>Specify additional command line options for running Doxygen</dt>
<dd><p>Field to specify extra options used when running Doxygen, e.g. for debugging purposes.</p></dd>
<dt>Run Doxygen</dt>
<dd><p>When clicked will start running Doxygen. The "Output produced by Doxygen" pane shows the messages produced by Doxygen while it is running. Before being able to run Doxygen the settings have to be saved.</p></dd>
<dt>Show HTML output</dt>
<dd><p>Clicking this button will open the main HTML output page in the default browser. The button will be enabled after Doxygen has finished.</p></dd>
<dt>Show configuration</dt>
<dd><p>Clicking this button shows the configuration settings that are used when running Doxygen. The results will be shown in the "Output produced by Doxygen" pane in compact textual form.</p></dd>
<dt>Condensed</dt>
<dd><p>When checked the "Show configuration" button will only list the configuration settings that differ from the default settings (analogous to <span class="doxyComputerOutput">doxygen -x</span>).</p></dd>
<dt>Save Log ...</dt>
<dd><p>Will save the information from the "Output produced by Doxygen" pane in a file as specified by the user.</p></dd>
</dl>

## Menu options {#dw_menu}


### File menu {#dw_menu_file}


<p>The file menu with a couple of useful items for loading and saving settings.</p>


<p><figure>
  <img src="/web-doxygen/img/doxygen-manual/doxywizard_menu_file.png"></img>
  <figcaption>File menu</figcaption>
</figure></p>


<dl class="doxyVariableList">
<dt>Open...</dt>
<dd><p>Load a configuration file from disk, based on a file selection dialog. In case unsaved settings exist you will be asked to confirm the action.</p></dd>
<dt>Open recent</dt>
<dd><p>Quickly load a recently saved configuration file. In case unsaved settings exist you will be asked to confirm the action. This menu item is only accessible when there are recent files in the list.</p></dd>
<dt>Save</dt>
<dd><p>Saves a configuration file to disk. In case the configuration file has already been set this file name is used otherwise a selection dialog will appear. In case the file already exists a confirmation is required.</p></dd>
<dt>Save as..</dt>
<dd><p>Saves the current configuration settings to disk with a specific name. This file name will become the currently set file name.</p></dd>
<dt>Quit</dt>
<dd><p>Leave Doxywizard, in case unsaved settings exist you will be asked to confirm the action.</p></dd>
</dl>

### Settings menu {#dw_menu_settings}


<p><figure>
  <img src="/web-doxygen/img/doxygen-manual/doxywizard_menu_settings.png"></img>
  <figcaption>Settings menu</figcaption>
</figure></p>


<dl class="doxyVariableList">
<dt>Reset to factory defaults</dt>
<dd><p>Restores the factory defaults as the default settings to use. You will be asked to confirm the action. This menu item is only accessible when the current settings differ from the default settings.</p></dd>
<dt>Use current settings at startup</dt>
<dd><p>Stores the current configuration settings as the default to use next time the GUI is started. You will be asked to confirm the action.</p></dd>
<dt>Clear recent list</dt>
<dd><p>Clears the "Open recent" list in the <a href="#dw_menu_file">File menu</a>. This menu item is only accessible when there are recent files in the "Open recent" list.</p></dd>
<dt>Run Doxygen</dt>
<dd><p>Selecting this item is identical to switching to the <a href="#dw_run">Run</a> tab, and clicking the "Run Doxygen" button</p></dd>
</dl>

### Help menu {#dw_menu_help}


<p><figure>
  <img src="/web-doxygen/img/doxygen-manual/doxywizard_menu_help.png"></img>
  <figcaption>Help menu</figcaption>
</figure></p>


<dl class="doxyVariableList">
<dt>Online Manual</dt>
<dd><p>Opens the Doxygen manual from the Doxygen home page in the system defined default HTML browser.</p></dd>
<dt>About</dt>
<dd><p>Shows an About dialog with version information.</p></dd>
</dl>
 
Go to the <a href="/docs/pages/config/">next</a> section or return to the
 <a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
