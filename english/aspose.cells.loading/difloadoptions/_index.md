---
title: DifLoadOptions class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 20
url: /aspose.cells.loading/difloadoptions/
is_root: false
---

## DifLoadOptions class

Represents the options of loading .dif file.



**Inheritance:** [`DifLoadOptions`](/cells/python-net/aspose.cells.loading/difloadoptions) → 
[`LoadOptions`](/cells/python-net/aspose.cells/loadoptions)



The DifLoadOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/cells/python-net/aspose.cells.loading/difloadoptions/__init__/#) | The options. |


### Properties
| Property | Description |
| :- | :- |
| [load_format](/cells/python-net/aspose.cells.loading/difloadoptions/load_format) | Gets the load format. |
| [password](/cells/python-net/aspose.cells.loading/difloadoptions/password) | Gets and set the password of the workbook. |
| [parsing_formula_on_open](/cells/python-net/aspose.cells.loading/difloadoptions/parsing_formula_on_open) | Indicates whether parsing the formula when reading the file. |
| [parsing_pivot_cached_records](/cells/python-net/aspose.cells.loading/difloadoptions/parsing_pivot_cached_records) | Indicates whether parsing pivot cached records when loading the file.<br/>The default value is false. |
| [language_code](/cells/python-net/aspose.cells.loading/difloadoptions/language_code) | Gets or sets the user interface language of the Workbook version based on CountryCode that has saved the file. |
| [region](/cells/python-net/aspose.cells.loading/difloadoptions/region) | Gets or sets the system regional settings based on CountryCode at the time the file was loaded. |
| [default_style_settings](/cells/python-net/aspose.cells.loading/difloadoptions/default_style_settings) | Gets the default style settings for initializing styles of the workbook |
| [standard_font](/cells/python-net/aspose.cells.loading/difloadoptions/standard_font) | Sets the default standard font name |
| [standard_font_size](/cells/python-net/aspose.cells.loading/difloadoptions/standard_font_size) | Sets the default standard font size. |
| [interrupt_monitor](/cells/python-net/aspose.cells.loading/difloadoptions/interrupt_monitor) | Gets and sets the interrupt monitor. |
| [ignore_not_printed](/cells/python-net/aspose.cells.loading/difloadoptions/ignore_not_printed) | Ignore the data which are not printed if directly printing the file |
| [check_data_valid](/cells/python-net/aspose.cells.loading/difloadoptions/check_data_valid) | Check whether data is valid in the template file. |
| [check_excel_restriction](/cells/python-net/aspose.cells.loading/difloadoptions/check_excel_restriction) | Whether check restriction of excel file when user modify cells related objects.<br/>For example, excel does not allow inputting string value longer than 32K.<br/>When you input a value longer than 32K such as by Cell.PutValue(string), if this property is true, you will get an Exception.<br/>If this property is false, we will accept your input string value as the cell's value so that later<br/>you can output the complete string value for other file formats such as CSV.<br/>However, if you have set such kind of value that is invalid for excel file format,<br/>you should not save the workbook as excel file format later. Otherwise there may be unexpected error for the generated excel file. |
| [keep_unparsed_data](/cells/python-net/aspose.cells.loading/difloadoptions/keep_unparsed_data) | Whether keep the unparsed data in memory for the Workbook when it is loaded from template file. Default is true. |
| [load_filter](/cells/python-net/aspose.cells.loading/difloadoptions/load_filter) | The filter to denote how to load data. |
| [light_cells_data_handler](/cells/python-net/aspose.cells.loading/difloadoptions/light_cells_data_handler) | The data handler for processing cells data when reading template file. |
| [memory_setting](/cells/python-net/aspose.cells.loading/difloadoptions/memory_setting) | Gets or sets the memory usage options. |
| [warning_callback](/cells/python-net/aspose.cells.loading/difloadoptions/warning_callback) | Gets or sets warning callback. |
| [auto_fitter_options](/cells/python-net/aspose.cells.loading/difloadoptions/auto_fitter_options) | Gets and sets the auto fitter options |
| [auto_filter](/cells/python-net/aspose.cells.loading/difloadoptions/auto_filter) | Indicates whether auto filtering the data when loading the files. |
| [font_configs](/cells/python-net/aspose.cells.loading/difloadoptions/font_configs) | Gets and sets individual font configs. <br/>Only works for the [`Workbook`](/cells/python-net/aspose.cells/workbook) which uses this [`LoadOptions`](/cells/python-net/aspose.cells/loadoptions) to load. |
| [ignore_useless_shapes](/cells/python-net/aspose.cells.loading/difloadoptions/ignore_useless_shapes) | Indicates whether ignoring useless shapes. |
| [preserve_padding_spaces_in_formula](/cells/python-net/aspose.cells.loading/difloadoptions/preserve_padding_spaces_in_formula) | Indicates whether preserve those spaces and line breaks that are padded between formula tokens<br/>while getting and setting formulas.<br/>Default value is false. |


### Methods
| Method | Description |
| :- | :- |
| [set_paper_size](/cells/python-net/aspose.cells.loading/difloadoptions/set_paper_size/#aspose.cells.PaperSizeType) | Sets the default print paper size from default printer's setting. |



### See Also
* module [`aspose.cells.loading`](..)
* class [`DifLoadOptions`](/cells/python-net/aspose.cells.loading/difloadoptions)
* class [`LoadOptions`](/cells/python-net/aspose.cells/loadoptions)
* class [`Workbook`](/cells/python-net/aspose.cells/workbook)
