﻿---
title: NumbersLoadOptions class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 10
url: /aspose.cells.numbers/numbersloadoptions/
is_root: false
---

## NumbersLoadOptions class

Represents the options of loading Apple Numbers files.



**Inheritance:** [`NumbersLoadOptions`](/cells/python-net/aspose.cells.numbers/numbersloadoptions) → 
[`LoadOptions`](/cells/python-net/aspose.cells/loadoptions)



The NumbersLoadOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/cells/python-net/aspose.cells.numbers/numbersloadoptions/__init__/#) | Constructor. |


### Properties
| Property | Description |
| :- | :- |
| [load_format](/cells/python-net/aspose.cells.numbers/numbersloadoptions/load_format) | Gets the load format. |
| [password](/cells/python-net/aspose.cells.numbers/numbersloadoptions/password) | Gets and set the password of the workbook. |
| [parsing_formula_on_open](/cells/python-net/aspose.cells.numbers/numbersloadoptions/parsing_formula_on_open) | Indicates whether parsing the formula when reading the file. |
| [parsing_pivot_cached_records](/cells/python-net/aspose.cells.numbers/numbersloadoptions/parsing_pivot_cached_records) | Indicates whether parsing pivot cached records when loading the file.<br/>The default value is false. |
| [language_code](/cells/python-net/aspose.cells.numbers/numbersloadoptions/language_code) | Gets or sets the user interface language of the Workbook version based on CountryCode that has saved the file. |
| [region](/cells/python-net/aspose.cells.numbers/numbersloadoptions/region) | Gets or sets the system regional settings based on CountryCode at the time the file was loaded. |
| [default_style_settings](/cells/python-net/aspose.cells.numbers/numbersloadoptions/default_style_settings) | Gets the default style settings for initializing styles of the workbook |
| [standard_font](/cells/python-net/aspose.cells.numbers/numbersloadoptions/standard_font) | Sets the default standard font name |
| [standard_font_size](/cells/python-net/aspose.cells.numbers/numbersloadoptions/standard_font_size) | Sets the default standard font size. |
| [interrupt_monitor](/cells/python-net/aspose.cells.numbers/numbersloadoptions/interrupt_monitor) | Gets and sets the interrupt monitor. |
| [ignore_not_printed](/cells/python-net/aspose.cells.numbers/numbersloadoptions/ignore_not_printed) | Ignore the data which are not printed if directly printing the file |
| [check_data_valid](/cells/python-net/aspose.cells.numbers/numbersloadoptions/check_data_valid) | Check whether data is valid in the template file. |
| [check_excel_restriction](/cells/python-net/aspose.cells.numbers/numbersloadoptions/check_excel_restriction) | Whether check restriction of excel file when user modify cells related objects.<br/>For example, excel does not allow inputting string value longer than 32K.<br/>When you input a value longer than 32K such as by Cell.PutValue(string), if this property is true, you will get an Exception.<br/>If this property is false, we will accept your input string value as the cell's value so that later<br/>you can output the complete string value for other file formats such as CSV.<br/>However, if you have set such kind of value that is invalid for excel file format,<br/>you should not save the workbook as excel file format later. Otherwise there may be unexpected error for the generated excel file. |
| [keep_unparsed_data](/cells/python-net/aspose.cells.numbers/numbersloadoptions/keep_unparsed_data) | Whether keep the unparsed data in memory for the Workbook when it is loaded from template file. Default is true. |
| [load_filter](/cells/python-net/aspose.cells.numbers/numbersloadoptions/load_filter) | The filter to denote how to load data. |
| [light_cells_data_handler](/cells/python-net/aspose.cells.numbers/numbersloadoptions/light_cells_data_handler) | The data handler for processing cells data when reading template file. |
| [memory_setting](/cells/python-net/aspose.cells.numbers/numbersloadoptions/memory_setting) | Gets or sets the memory usage options. |
| [warning_callback](/cells/python-net/aspose.cells.numbers/numbersloadoptions/warning_callback) | Gets or sets warning callback. |
| [auto_fitter_options](/cells/python-net/aspose.cells.numbers/numbersloadoptions/auto_fitter_options) | Gets and sets the auto fitter options |
| [auto_filter](/cells/python-net/aspose.cells.numbers/numbersloadoptions/auto_filter) | Indicates whether auto filtering the data when loading the files. |
| [font_configs](/cells/python-net/aspose.cells.numbers/numbersloadoptions/font_configs) | Gets and sets individual font configs. <br/>Only works for the [`Workbook`](/cells/python-net/aspose.cells/workbook) which uses this [`LoadOptions`](/cells/python-net/aspose.cells/loadoptions) to load. |
| [ignore_useless_shapes](/cells/python-net/aspose.cells.numbers/numbersloadoptions/ignore_useless_shapes) | Indicates whether ignoring useless shapes. |
| [load_table_type](/cells/python-net/aspose.cells.numbers/numbersloadoptions/load_table_type) | Gets and sets the type of loading multiple tables in one worksheet. |


### Methods
| Method | Description |
| :- | :- |
| [set_paper_size](/cells/python-net/aspose.cells.numbers/numbersloadoptions/set_paper_size/#aspose.cells.PaperSizeType) | Sets the default print paper size from default printer's setting. |



### See Also
* module [`aspose.cells.numbers`](..)
* class [`LoadOptions`](/cells/python-net/aspose.cells/loadoptions)
* class [`NumbersLoadOptions`](/cells/python-net/aspose.cells.numbers/numbersloadoptions)
* class [`Workbook`](/cells/python-net/aspose.cells/workbook)
