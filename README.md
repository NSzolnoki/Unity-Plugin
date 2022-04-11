# GRIDLY PLUGIN
### 1. What this plugin can do
This Plugin can help you sync data between Unity and Gridly.   
By using the path you can get the string data based on the
target language.

### 2. Setup first columns in Gridly
To be able to use this plugin with Gridly, there is some
initial setup you will have to do within Gridly so that the
plugin can refer to the correct columns. First you
need to specify a **columnID**. This you have to do for the source language column. To do this open the grid in Gridly that you want to use with the
plugin and for the source language column select the
option **Column properties**.  

<p align="center">
<img src="resources/column_properties.png"/>
</p>

Change the columnID to the specific four
character language code that applies to the text in the column,
make sure that the capitalization is correct with the two
country letters in capital:  

<p align="center">
<img src="resources/colId.png"/>
</p>

### 3.1 Connect Unity to Gridly
First you need to open the Gridly setting window by going to:
**Tools**->**Gridly**->**Setup Setting**  
<p align="center">
<img src="resources/setup_setting.png"/>
</p>

Here you have to enter your API key and define the folder to store the screenshots that generated.  
<p align="center">
<img src="resources/setup_setting_mw.png"/>
</p>

You can find your API key in Gridly at the API quick start in the right pane:

<p align="center">
<img src="resources/api_quick_start.png"/>
</p>

By default the plugin adds two views, but those are dummies, so feel free to delete or change their name and viewID.  
You can add new view by clicking on the plus icon
<p align="center">
<img src="resources/add_new_view.png"/>
</p>

### 3.2 Maintain languages in the plugin
* You can add a language by selecting a language from the list and clicking on the "Add" button. Adding a language to your project, creates the column for this language in Gridly
<p align="center">
<img src="resources/lang_selectLang.png"/>
</p>

* You can remove the language by clicking on its "X" button. On deleting a language, you will get two dialogs. The first will ask you to remove the language from Unity, and the second will ask you about deleting the language column and the screenshot column of this language in Gridly.
<p align="center">
<img src="resources/lang_deleteLang.png"/>
</p>

* You can select what type of font you would like to use by setting the "Font" or the "TmFont" which is stands for the Text Mesh Pro.
* You can select the column to use in Gridly for storing the images from the given language by clicking on dropdown menu next to the "Screenshot column ID". If you don't have any, you can create one by clicking on the "Generate column" button, which creates a "files" type column in Gridly. Then select this column ID from the list. 
<p align="center">
<img src="resources/langScreenshotColId.png" alt="MarineGEO circle logo"/>
</p>

  

* You can change your project source language by clicking on the "Set source" button.
* You can change the column ID of the language by clicking on the dropdown list next to the label "Column ID in Gridly"
* You can change the language code of the given language by clicking on the "Select language" dropdown list.
