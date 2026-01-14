---
title: FontConfigs class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 670
url: /aspose.cells/fontconfigs/
is_root: false
---

## FontConfigs class

Specifies font settings



The FontConfigs type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/cells/python-net/aspose.cells/fontconfigs/__init__/#) | Constructs a new instance of FontConfigs |


### Properties
| Property | Description |
| :- | :- |
| [default_font_name](/cells/python-net/aspose.cells/fontconfigs/default_font_name) | Gets or sets the default font name. |
| [prefer_system_font_substitutes](/cells/python-net/aspose.cells/fontconfigs/prefer_system_font_substitutes) | Indicate whether to use system font substitutes first or not when a font is not presented and the substitute of this font is not set.<br/>e.g. On Ubuntu, "Arial" font is generally substituted by "Liberation Sans".<br/>Default value is false. |


### Methods
| Method | Description |
| :- | :- |
| [`is_font_available(, font_name)`](/cells/python-net/aspose.cells/fontconfigs/is_font_available/#system.string) | Indicate whether the font is available. |
| [`get_font_file_data_info(, font_name, is_bold, is_italic, is_exact_style)`](/cells/python-net/aspose.cells/fontconfigs/get_font_file_data_info/#system.string-bool-bool-bool) | Get data information of font file data. |
| [`set_font_substitutes(, original_font_name, substitute_font_names)`](/cells/python-net/aspose.cells/fontconfigs/set_font_substitutes/#system.string-list) | Font substitute names for given original font name. |
| [`get_font_substitutes(, original_font_name)`](/cells/python-net/aspose.cells/fontconfigs/get_font_substitutes/#system.string) | Returns an array containing font substitute names to be used if original font is not present. |
| [`set_font_folder(, font_folder, recursive)`](/cells/python-net/aspose.cells/fontconfigs/set_font_folder/#system.string-bool) | Sets the fonts folder |
| [`set_font_folders(, font_folders, recursive)`](/cells/python-net/aspose.cells/fontconfigs/set_font_folders/#list-bool) | Sets the fonts folder |
| [`set_font_sources(, sources)`](/cells/python-net/aspose.cells/fontconfigs/set_font_sources/#list) | Sets the font sources. |
| [`get_font_sources()`](/cells/python-net/aspose.cells/fontconfigs/get_font_sources/#) | Gets a copy of the array that contains the list of sources |



### See Also
* module [`aspose.cells`](..)
