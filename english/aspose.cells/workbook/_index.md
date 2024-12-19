﻿---
title: Workbook class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 1730
url: /aspose.cells/workbook/
is_root: false
---

## Workbook class

Represents a root object to create an Excel spreadsheet.



The Workbook type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/cells/python-net/aspose.cells/workbook/__init__/#) | Initializes a new instance of the [`Workbook`](/cells/python-net/aspose.cells/workbook) class. |
| [__init__](/cells/python-net/aspose.cells/workbook/__init__/#aspose.cells.FileFormatType) | Initializes a new instance of the [`Workbook`](/cells/python-net/aspose.cells/workbook) class. |
| [__init__](/cells/python-net/aspose.cells/workbook/__init__/#str) | Initializes a new instance of the [`Workbook`](/cells/python-net/aspose.cells/workbook) class and open a file. |
| [__init__](/cells/python-net/aspose.cells/workbook/__init__/#io.RawIOBase) | Initializes a new instance of the [`Workbook`](/cells/python-net/aspose.cells/workbook) class and open a stream. |
| [__init__](/cells/python-net/aspose.cells/workbook/__init__/#str-aspose.cells.LoadOptions) | Initializes a new instance of the [`Workbook`](/cells/python-net/aspose.cells/workbook) class and open a file. |
| [__init__](/cells/python-net/aspose.cells/workbook/__init__/#io.RawIOBase-aspose.cells.LoadOptions) | Initializes a new instance of the [`Workbook`](/cells/python-net/aspose.cells/workbook) class and open stream. |


### Properties
| Property | Description |
| :- | :- |
| [settings](/cells/python-net/aspose.cells/workbook/settings) | Represents the workbook settings. |
| [worksheets](/cells/python-net/aspose.cells/workbook/worksheets) | Gets the [`WorksheetCollection`](/cells/python-net/aspose.cells/worksheetcollection) collection in the spreadsheet. |
| [is_licensed](/cells/python-net/aspose.cells/workbook/is_licensed) | Indicates whether license is set. |
| [colors](/cells/python-net/aspose.cells/workbook/colors) | Returns colors in the palette for the spreadsheet. |
| [count_of_styles_in_pool](/cells/python-net/aspose.cells/workbook/count_of_styles_in_pool) | Gets number of the styles in the style pool. |
| [default_style](/cells/python-net/aspose.cells/workbook/default_style) | Gets or sets the default [`Style`](/cells/python-net/aspose.cells/style) object of the workbook. |
| [is_digitally_signed](/cells/python-net/aspose.cells/workbook/is_digitally_signed) | Indicates if this spreadsheet is digitally signed. |
| [is_workbook_protected_with_password](/cells/python-net/aspose.cells/workbook/is_workbook_protected_with_password) | Indicates whether structure or window is protected with password. |
| [vba_project](/cells/python-net/aspose.cells/workbook/vba_project) | Gets the [`Workbook.vba_project`](/cells/python-net/aspose.cells/workbook#vba_project) in a spreadsheet. |
| [has_macro](/cells/python-net/aspose.cells/workbook/has_macro) | Indicates if this spreadsheet contains macro/VBA. |
| [has_revisions](/cells/python-net/aspose.cells/workbook/has_revisions) | Gets if the workbook has any tracked changes |
| [file_name](/cells/python-net/aspose.cells/workbook/file_name) | Gets and sets the current file name. |
| [cells_data_table_factory](/cells/python-net/aspose.cells/workbook/cells_data_table_factory) | Gets the factory for building ICellsDataTable from custom objects |
| [data_sorter](/cells/python-net/aspose.cells/workbook/data_sorter) | Gets a DataSorter object to sort data. |
| [theme](/cells/python-net/aspose.cells/workbook/theme) | Gets the theme name. |
| [built_in_document_properties](/cells/python-net/aspose.cells/workbook/built_in_document_properties) | Returns a [`DocumentProperty`](/cells/python-net/aspose.cells.properties/documentproperty) collection that represents all the built-in document properties of the spreadsheet. |
| [custom_document_properties](/cells/python-net/aspose.cells/workbook/custom_document_properties) | Returns a [`DocumentProperty`](/cells/python-net/aspose.cells.properties/documentproperty) collection that represents all the custom document properties of the spreadsheet. |
| [file_format](/cells/python-net/aspose.cells/workbook/file_format) | Gets and sets the file format. |
| [interrupt_monitor](/cells/python-net/aspose.cells/workbook/interrupt_monitor) | Gets and sets the interrupt monitor. |
| [content_type_properties](/cells/python-net/aspose.cells/workbook/content_type_properties) | Gets the list of  [`ContentTypeProperty`](/cells/python-net/aspose.cells.properties/contenttypeproperty) objects in the workbook. |
| [custom_xml_parts](/cells/python-net/aspose.cells/workbook/custom_xml_parts) | Represents a Custom XML Data Storage Part (custom XML data within a package). |
| [data_mashup](/cells/python-net/aspose.cells/workbook/data_mashup) | Gets mashup data. |
| [ribbon_xml](/cells/python-net/aspose.cells/workbook/ribbon_xml) | Gets and sets the XML file that defines the Ribbon UI. |
| [absolute_path](/cells/python-net/aspose.cells/workbook/absolute_path) | Gets and sets the absolute path of the file. |
| [data_connections](/cells/python-net/aspose.cells/workbook/data_connections) | Gets the [`ExternalConnection`](/cells/python-net/aspose.cells.externalconnections/externalconnection) collection. |
| [data_model](/cells/python-net/aspose.cells/workbook/data_model) | Gets data model in the workbook. |


### Methods
| Method | Description |
| :- | :- |
| [save](/cells/python-net/aspose.cells/workbook/save/#str-aspose.cells.SaveFormat) | Saves the workbook to the disk. |
| [save](/cells/python-net/aspose.cells/workbook/save/#str) | Save the workbook to the disk. |
| [save](/cells/python-net/aspose.cells/workbook/save/#str-aspose.cells.SaveOptions) | Saves the workbook to the disk. |
| [save](/cells/python-net/aspose.cells/workbook/save/#io.RawIOBase-aspose.cells.SaveFormat) | Saves the workbook to the stream. |
| [save](/cells/python-net/aspose.cells/workbook/save/#io.RawIOBase-aspose.cells.SaveOptions) | Saves the workbook to the stream. |
| [replace](/cells/python-net/aspose.cells/workbook/replace/#str-str) | Replaces a cell's value with a new string. |
| [replace](/cells/python-net/aspose.cells/workbook/replace/#str-int) | Replaces a cell's value with a new integer. |
| [replace](/cells/python-net/aspose.cells/workbook/replace/#str-float) | Replaces a cell's value with a new double. |
| [replace](/cells/python-net/aspose.cells/workbook/replace/#str-list-bool) | Replaces a cell's value with a new string array. |
| [replace](/cells/python-net/aspose.cells/workbook/replace/#str-list-bool) | Replaces cells' values with an integer array. |
| [replace](/cells/python-net/aspose.cells/workbook/replace/#str-list-bool) | Replaces cells' values with a double array. |
| [replace](/cells/python-net/aspose.cells/workbook/replace/#bool-any) | Replaces cells' values with new data. |
| [replace](/cells/python-net/aspose.cells/workbook/replace/#int-any) | Replaces cells' values with new data. |
| [replace](/cells/python-net/aspose.cells/workbook/replace/#str-str-aspose.cells.ReplaceOptions) | Replaces a cell's value with a new string. |
| [copy](/cells/python-net/aspose.cells/workbook/copy/#aspose.cells.Workbook-aspose.cells.CopyOptions) | Copies another Workbook object. |
| [copy](/cells/python-net/aspose.cells/workbook/copy/#aspose.cells.Workbook) | Copies data from a source Workbook object. |
| [calculate_formula](/cells/python-net/aspose.cells/workbook/calculate_formula/#) | Calculates the result of formulas. |
| [calculate_formula](/cells/python-net/aspose.cells/workbook/calculate_formula/#bool) | Calculates the result of formulas. |
| [calculate_formula](/cells/python-net/aspose.cells/workbook/calculate_formula/#aspose.cells.CalculationOptions) | Calculating formulas in this workbook. |
| [refresh_dynamic_array_formulas](/cells/python-net/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool) | Refreshes dynamic array formulas(spill into new range of neighboring cells according to current data)<br/>Other formulas in the workbook will not be calculated recursively even if they were used by dynamic array formulas. |
| [refresh_dynamic_array_formulas](/cells/python-net/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool-aspose.cells.CalculationOptions) | Refreshes dynamic array formulas(spill into new range of neighboring cells according to current data) |
| [import_xml](/cells/python-net/aspose.cells/workbook/import_xml/#str-str-int-int) | Imports/Updates an XML data file into the workbook. |
| [import_xml](/cells/python-net/aspose.cells/workbook/import_xml/#io.RawIOBase-str-int-int) | Imports/Updates an XML data file into the workbook. |
| [export_xml](/cells/python-net/aspose.cells/workbook/export_xml/#str-str) | Export XML data linked by the specified XML map. |
| [export_xml](/cells/python-net/aspose.cells/workbook/export_xml/#str-io.RawIOBase) | Export XML data. |
| [parse_formulas](/cells/python-net/aspose.cells/workbook/parse_formulas/#bool) | Parses all formulas which have not been parsed when they were loaded from template file or set to a cell. |
| [start_access_cache](/cells/python-net/aspose.cells/workbook/start_access_cache/#aspose.cells.AccessCacheOptions) | Starts the session that uses caches to access data. |
| [close_access_cache](/cells/python-net/aspose.cells/workbook/close_access_cache/#aspose.cells.AccessCacheOptions) | Closes the session that uses caches to access data. |
| [remove_unused_styles](/cells/python-net/aspose.cells/workbook/remove_unused_styles/#) | Remove all unused styles. |
| [create_style](/cells/python-net/aspose.cells/workbook/create_style/#) | Creates a new style. |
| [create_builtin_style](/cells/python-net/aspose.cells/workbook/create_builtin_style/#aspose.cells.BuiltinStyleType) | Creates built-in style by given type. |
| [create_cells_color](/cells/python-net/aspose.cells/workbook/create_cells_color/#) | Creates a [`CellsColor`](/cells/python-net/aspose.cells/cellscolor) object. |
| [combine](/cells/python-net/aspose.cells/workbook/combine/#aspose.cells.Workbook) | Combines another Workbook object. |
| [get_style_in_pool](/cells/python-net/aspose.cells/workbook/get_style_in_pool/#int) | Gets the style in the style pool.<br/>All styles in the workbook will be gathered into a pool.<br/>There is only a simple reference index in the cells. |
| [get_fonts](/cells/python-net/aspose.cells/workbook/get_fonts/#) | Gets all fonts in the style pool. |
| [get_named_style](/cells/python-net/aspose.cells/workbook/get_named_style/#str) | Gets the named style in the style pool. |
| [change_palette](/cells/python-net/aspose.cells/workbook/change_palette/#aspose.pydrawing.Color-int) | Changes the palette for the spreadsheet in the specified index. |
| [is_color_in_palette](/cells/python-net/aspose.cells/workbook/is_color_in_palette/#aspose.pydrawing.Color) | Checks if a color is in the palette for the spreadsheet. |
| [get_matching_color](/cells/python-net/aspose.cells/workbook/get_matching_color/#aspose.pydrawing.Color) | Find best matching Color in current palette. |
| [set_encryption_options](/cells/python-net/aspose.cells/workbook/set_encryption_options/#aspose.cells.EncryptionType-int) | Set Encryption Options. |
| [protect](/cells/python-net/aspose.cells/workbook/protect/#aspose.cells.ProtectionType-str) | Protects a workbook. |
| [protect_shared_workbook](/cells/python-net/aspose.cells/workbook/protect_shared_workbook/#str) | Protects a shared workbook. |
| [unprotect](/cells/python-net/aspose.cells/workbook/unprotect/#str) | Unprotects a workbook. |
| [unprotect_shared_workbook](/cells/python-net/aspose.cells/workbook/unprotect_shared_workbook/#str) | Unprotects a shared workbook. |
| [remove_macro](/cells/python-net/aspose.cells/workbook/remove_macro/#) | Removes VBA/macro from this spreadsheet. |
| [remove_digital_signature](/cells/python-net/aspose.cells/workbook/remove_digital_signature/#) | Removes digital signature from this spreadsheet. |
| [accept_all_revisions](/cells/python-net/aspose.cells/workbook/accept_all_revisions/#) | Accepts all tracked changes in the workbook. |
| [remove_external_links](/cells/python-net/aspose.cells/workbook/remove_external_links/#) | Removes all external links in the workbook. |
| [get_theme_color](/cells/python-net/aspose.cells/workbook/get_theme_color/#aspose.cells.ThemeColorType) | Gets theme color. |
| [set_theme_color](/cells/python-net/aspose.cells/workbook/set_theme_color/#aspose.cells.ThemeColorType-aspose.pydrawing.Color) | Sets the theme color |
| [custom_theme](/cells/python-net/aspose.cells/workbook/custom_theme/#str-aspose.pydrawing.Color[]) | Customs the theme. |
| [copy_theme](/cells/python-net/aspose.cells/workbook/copy_theme/#aspose.cells.Workbook) | Copies the theme from another workbook. |
| [has_exernal_links](/cells/python-net/aspose.cells/workbook/has_exernal_links/#) | Indicates whether this workbook contains external links to other data sources. |
| [update_custom_function_definition](/cells/python-net/aspose.cells/workbook/update_custom_function_definition/#aspose.cells.CustomFunctionDefinition) | Updates definition of custom functions. |
| [update_linked_data_source](/cells/python-net/aspose.cells/workbook/update_linked_data_source/#list) | If this workbook contains external links to other data source,<br/>Aspose.Cells will attempt to retrieve the latest data from give sources. |
| [set_digital_signature](/cells/python-net/aspose.cells/workbook/set_digital_signature/#aspose.cells.digitalsignatures.DigitalSignatureCollection) | Sets digital signature to an spreadsheet file (Excel2007 and later). |
| [add_digital_signature](/cells/python-net/aspose.cells/workbook/add_digital_signature/#aspose.cells.digitalsignatures.DigitalSignatureCollection) | Adds digital signature to an OOXML spreadsheet file (Excel2007 and later). |
| [get_digital_signature](/cells/python-net/aspose.cells/workbook/get_digital_signature/#) | Gets digital signature from file. |
| [remove_personal_information](/cells/python-net/aspose.cells/workbook/remove_personal_information/#) | Removes personal information. |



### Remarks 


The Workbook class denotes an Excel spreadsheet. Each spreadsheet can contain multiple worksheets.
The basic feature of the class is to open and save native excel files.
The class has some advanced features like copying data from other Workbooks, combining two Workbooks, converting Excel to PDF, rendering Excel to image and protecting the Excel spreadsheet.

### Example 


The following example loads a Workbook from an Excel file named designer.xls and makes the horizontal and vertical scroll bars invisible.
It then replaces two string values with an Integer value and string value respectively within the spreadsheet and finally save the workbook as Excel xlsx file. 

```python
from aspose.cells import Workbook

# Open a designer file
designerFile = "designer.xls"
workbook = Workbook(designerFile)
# Set scroll bars
workbook.settings.is_h_scroll_bar_visible = False
workbook.settings.is_v_scroll_bar_visible = False
# Replace the placeholder string with new values
newInt = 100
workbook.replace("OldInt", newInt)
newString = "Hello!"
workbook.replace("OldString", newString)
workbook.save("result.xlsx")

```

### See Also
* module [`aspose.cells`](..)
* class [`CellsColor`](/cells/python-net/aspose.cells/cellscolor)
* class [`ContentTypeProperty`](/cells/python-net/aspose.cells.properties/contenttypeproperty)
* class [`DocumentProperty`](/cells/python-net/aspose.cells.properties/documentproperty)
* class [`ExternalConnection`](/cells/python-net/aspose.cells.externalconnections/externalconnection)
* class [`Style`](/cells/python-net/aspose.cells/style)
* class [`Workbook`](/cells/python-net/aspose.cells/workbook)
* class [`WorksheetCollection`](/cells/python-net/aspose.cells/worksheetcollection)
