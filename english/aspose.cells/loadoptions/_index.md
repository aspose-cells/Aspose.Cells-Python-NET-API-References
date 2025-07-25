﻿---
title: LoadOptions class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 950
url: /aspose.cells/loadoptions/
is_root: false
---

## LoadOptions class

Represents the options of loading the file.



The LoadOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/cells/python-net/aspose.cells/loadoptions/__init__/#) | Creates an options of loading the file. |
| [`__init__(self, load_format)`](/cells/python-net/aspose.cells/loadoptions/__init__/#aspose.cells.loadformat) | Creates an options of loading the file. |


### Properties
| Property | Description |
| :- | :- |
| [load_format](/cells/python-net/aspose.cells/loadoptions/load_format) | Gets the load format. |
| [password](/cells/python-net/aspose.cells/loadoptions/password) | Gets and set the password of the workbook. |
| [parsing_formula_on_open](/cells/python-net/aspose.cells/loadoptions/parsing_formula_on_open) | Indicates whether parsing the formula when reading the file. |
| [parsing_pivot_cached_records](/cells/python-net/aspose.cells/loadoptions/parsing_pivot_cached_records) | Indicates whether parsing pivot cached records when loading the file.<br/>The default value is false. |
| [language_code](/cells/python-net/aspose.cells/loadoptions/language_code) | Gets or sets the user interface language of the Workbook version based on CountryCode that has saved the file. |
| [region](/cells/python-net/aspose.cells/loadoptions/region) | Gets or sets the regional settings used for the Workbook that will be loaded. |
| [default_style_settings](/cells/python-net/aspose.cells/loadoptions/default_style_settings) | Gets the default style settings for initializing styles of the workbook |
| [standard_font](/cells/python-net/aspose.cells/loadoptions/standard_font) | Sets the default standard font name |
| [standard_font_size](/cells/python-net/aspose.cells/loadoptions/standard_font_size) | Sets the default standard font size. |
| [ignore_not_printed](/cells/python-net/aspose.cells/loadoptions/ignore_not_printed) | Ignore the data which are not printed if directly printing the file |
| [check_data_valid](/cells/python-net/aspose.cells/loadoptions/check_data_valid) | Check whether data is valid in the template file. |
| [check_excel_restriction](/cells/python-net/aspose.cells/loadoptions/check_excel_restriction) | Whether check restriction of excel file when user modify cells related objects.<br/>For example, excel does not allow inputting string value longer than 32K.<br/>When you input a value longer than 32K such as by Cell.PutValue(string), if this property is true, you will get an Exception.<br/>If this property is false, we will accept your input string value as the cell's value so that later<br/>you can output the complete string value for other file formats such as CSV.<br/>However, if you have set such kind of value that is invalid for excel file format,<br/>you should not save the workbook as excel file format later. Otherwise there may be unexpected error for the generated excel file. |
| [keep_unparsed_data](/cells/python-net/aspose.cells/loadoptions/keep_unparsed_data) | Whether keep the unparsed data in memory for the Workbook when it is loaded from template file. Default is true. |
| [load_filter](/cells/python-net/aspose.cells/loadoptions/load_filter) | The filter to denote how to load data. |
| [memory_setting](/cells/python-net/aspose.cells/loadoptions/memory_setting) | Gets or sets the memory mode for loaded workbook. |
| [auto_fitter_options](/cells/python-net/aspose.cells/loadoptions/auto_fitter_options) | Gets and sets the auto fitter options |
| [auto_filter](/cells/python-net/aspose.cells/loadoptions/auto_filter) | Indicates whether auto filtering the data when loading the files. |
| [font_configs](/cells/python-net/aspose.cells/loadoptions/font_configs) | Gets and sets individual font configs. <br/>Only works for the [`Workbook`](/cells/python-net/aspose.cells/workbook) which uses this [`LoadOptions`](/cells/python-net/aspose.cells/loadoptions) to load. |
| [ignore_useless_shapes](/cells/python-net/aspose.cells/loadoptions/ignore_useless_shapes) | Indicates whether ignoring useless shapes. |
| [preserve_padding_spaces_in_formula](/cells/python-net/aspose.cells/loadoptions/preserve_padding_spaces_in_formula) | Indicates whether preserve those spaces and line breaks that are padded between formula tokens<br/>while getting and setting formulas.<br/>Default value is false. |


### Methods
| Method | Description |
| :- | :- |
| [`set_paper_size(self, type)`](/cells/python-net/aspose.cells/loadoptions/set_paper_size/#aspose.cells.papersizetype) | Sets the default print paper size from default printer's setting. |



### See Also
* module [`aspose.cells`](..)
* class [`LoadOptions`](/cells/python-net/aspose.cells/loadoptions)
* class [`Workbook`](/cells/python-net/aspose.cells/workbook)
