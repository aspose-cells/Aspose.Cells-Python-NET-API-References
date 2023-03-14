﻿---
title: Cell class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 140
url: /aspose.cells/cell/
is_root: false
---

## Cell class

Encapsulates the object that represents a single Workbook cell.



The Cell type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [worksheet](/cells/python-net/aspose.cells/cell/worksheet) | Gets the parent worksheet. |
| [date_time_value](/cells/python-net/aspose.cells/cell/date_time_value) | Gets the DateTime value contained in the cell. |
| [row](/cells/python-net/aspose.cells/cell/row) | Gets row number (zero based) of the cell. |
| [column](/cells/python-net/aspose.cells/cell/column) | Gets column number (zero based) of the cell. |
| [is_formula](/cells/python-net/aspose.cells/cell/is_formula) | Represents if the specified cell contains formula. |
| [type](/cells/python-net/aspose.cells/cell/type) | Represents cell value type. |
| [name](/cells/python-net/aspose.cells/cell/name) | Gets the name of the cell. |
| [is_error_value](/cells/python-net/aspose.cells/cell/is_error_value) | Checks if the value of this cell is an error. |
| [is_numeric_value](/cells/python-net/aspose.cells/cell/is_numeric_value) | Indicates whether the inner value of this cell is numeric(int, double and datetime) |
| [string_value](/cells/python-net/aspose.cells/cell/string_value) | Gets the string value contained in the cell. If the type of this cell is string, then return the string value itself.<br/>For other cell types, the formatted string value (formatted with the specified style of this cell) will be returned.<br/>The formatted cell value is same with what you can get from excel when copying a cell as text(such as<br/>copying cell to text editor or exporting to csv). |
| [string_value_without_format](/cells/python-net/aspose.cells/cell/string_value_without_format) | Gets cell's value as string without any format. |
| [number_category_type](/cells/python-net/aspose.cells/cell/number_category_type) | Represents the category type of this cell's number formatting. |
| [display_string_value](/cells/python-net/aspose.cells/cell/display_string_value) | Gets the formatted string value of this cell by cell's display style. |
| [int_value](/cells/python-net/aspose.cells/cell/int_value) | Gets the integer value contained in the cell. |
| [double_value](/cells/python-net/aspose.cells/cell/double_value) | Gets the double value contained in the cell. |
| [float_value](/cells/python-net/aspose.cells/cell/float_value) | Gets the float value contained in the cell. |
| [bool_value](/cells/python-net/aspose.cells/cell/bool_value) | Gets the boolean value contained in the cell. |
| [has_custom_style](/cells/python-net/aspose.cells/cell/has_custom_style) | Indicates whether this cell has custom style settings(different from the default one inherited<br/>from corresponding row, column, or workbook). |
| [shared_style_index](/cells/python-net/aspose.cells/cell/shared_style_index) | Gets cell's shared style index in the style pool. |
| [formula](/cells/python-net/aspose.cells/cell/formula) | Gets or sets a formula of the [Cell](/cells/python-net/aspose.cells/cell). |
| [formula_local](/cells/python-net/aspose.cells/cell/formula_local) | Get the locale formatted formula of the cell. |
| [r1c1_formula](/cells/python-net/aspose.cells/cell/r1c1_formula) | Gets or sets a R1C1 formula of the [Cell](/cells/python-net/aspose.cells/cell). |
| [contains_external_link](/cells/python-net/aspose.cells/cell/contains_external_link) | Indicates whether this cell contains an external link.<br/>Only applies when the cell is a formula cell. |
| [is_array_header](/cells/python-net/aspose.cells/cell/is_array_header) | Indicates the cell's formula is and array formula <br/>and it is the first cell of the array. |
| [is_dynamic_array_formula](/cells/python-net/aspose.cells/cell/is_dynamic_array_formula) | Indicates whether the cell's formula is dynamic array formula(true) or legacy array formula(false). |
| [is_array_formula](/cells/python-net/aspose.cells/cell/is_array_formula) | Indicates whether the cell formula is an array formula. |
| [is_in_array](/cells/python-net/aspose.cells/cell/is_in_array) | Indicates whether the cell formula is an array formula. |
| [is_shared_formula](/cells/python-net/aspose.cells/cell/is_shared_formula) | Indicates whether the cell formula is part of shared formula. |
| [is_table_formula](/cells/python-net/aspose.cells/cell/is_table_formula) | Indicates whether this cell is part of table formula. |
| [is_in_table](/cells/python-net/aspose.cells/cell/is_in_table) | Indicates whether this cell is part of table formula. |
| [value](/cells/python-net/aspose.cells/cell/value) | Gets the value contained in this cell. |
| [is_style_set](/cells/python-net/aspose.cells/cell/is_style_set) | Indicates if the cell's style is set. If return false, it means this cell has a default cell format. |
| [is_merged](/cells/python-net/aspose.cells/cell/is_merged) | Checks if a cell is part of a merged range or not. |
| [comment](/cells/python-net/aspose.cells/cell/comment) | Gets the comment of this cell. |
| [html_string](/cells/python-net/aspose.cells/cell/html_string) | Gets and sets the html string which contains data and some formats in this cell. |


### Methods
| Method | Description |
| :- | :- |
| [calculate(options)](/cells/python-net/aspose.cells/cell/calculate/#CalculationOptions) | Calculates the formula of the cell. |
| [calculate(ignore_error, custom_function)](/cells/python-net/aspose.cells/cell/calculate/#bool-ICustomFunction) | Calculates the formula of the cell. |
| [put_value(bool_value)](/cells/python-net/aspose.cells/cell/put_value/#bool) | Puts a boolean value into the cell. |
| [put_value(int_value)](/cells/python-net/aspose.cells/cell/put_value/#int) | Puts an integer value into the cell. |
| [put_value(double_value)](/cells/python-net/aspose.cells/cell/put_value/#float) | Puts a double value into the cell. |
| [put_value(string_value, is_converted, set_style)](/cells/python-net/aspose.cells/cell/put_value/#str-bool-bool) | Puts a value into the cell, if appropriate the value will be converted to other data type and cell's number format will be reset. |
| [put_value(string_value, is_converted)](/cells/python-net/aspose.cells/cell/put_value/#str-bool) | Puts a string value into the cell and converts the value to other data type if appropriate. |
| [put_value(string_value)](/cells/python-net/aspose.cells/cell/put_value/#str) | Puts a string value into the cell. |
| [put_value(date_time)](/cells/python-net/aspose.cells/cell/put_value/#DateTime) | Puts a DateTime value into the cell. |
| [put_value(object_value)](/cells/python-net/aspose.cells/cell/put_value/#any) | Puts an object value into the cell. |
| [get_display_style()](/cells/python-net/aspose.cells/cell/get_display_style/#) | Gets the display style of the cell.<br/>If this cell is also affected by other settings such as conditional formatting, list objects, etc.,<br/>then the display style may be different from cell.GetStyle(). |
| [get_display_style(include_merged_borders)](/cells/python-net/aspose.cells/cell/get_display_style/#bool) | Gets the display style of the cell.<br/>If the cell is conditional formatted, the display style is not same as the cell.GetStyle(). |
| [get_style()](/cells/python-net/aspose.cells/cell/get_style/#) | Gets the cell style. |
| [get_style(check_borders)](/cells/python-net/aspose.cells/cell/get_style/#bool) | If checkBorders is true, check whether other cells' borders will effect the style of this cell. |
| [set_style(style)](/cells/python-net/aspose.cells/cell/set_style/#Style) | Sets the cell style. |
| [set_style(style, explicit_flag)](/cells/python-net/aspose.cells/cell/set_style/#Style-bool) | Apply the cell style. |
| [set_style(style, flag)](/cells/python-net/aspose.cells/cell/set_style/#Style-StyleFlag) | Apply the cell style. |
| [set_formula(formula, value)](/cells/python-net/aspose.cells/cell/set_formula/#str-any) | Set the formula and the value of the formula. |
| [set_formula(formula, is_r1c1, is_local, value)](/cells/python-net/aspose.cells/cell/set_formula/#str-bool-bool-any) | Set the formula and the value of the formula. |
| [set_formula(formula, options, value)](/cells/python-net/aspose.cells/cell/set_formula/#str-FormulaParseOptions-any) | Set the formula and the value of the formula. |
| [set_array_formula(array_formula, row_number, column_number, is_r1c1, is_local)](/cells/python-net/aspose.cells/cell/set_array_formula/#str-int-int-bool-bool) | Sets an array formula to a range of cells. |
| [set_array_formula(array_formula, row_number, column_number)](/cells/python-net/aspose.cells/cell/set_array_formula/#str-int-int) | Sets an array formula(legacy array formula entered via CTRL+SHIFT+ENTER in ms excel) to a range of cells. |
| [set_array_formula(array_formula, row_number, column_number, options)](/cells/python-net/aspose.cells/cell/set_array_formula/#str-int-int-FormulaParseOptions) | Sets an array formula to a range of cells. |
| [set_array_formula(array_formula, row_number, column_number, options, values)](/cells/python-net/aspose.cells/cell/set_array_formula/#str-int-int-FormulaParseOptions-list) | Sets an array formula to a range of cells. |
| [set_shared_formula(shared_formula, row_number, column_number, is_r1c1, is_local)](/cells/python-net/aspose.cells/cell/set_shared_formula/#str-int-int-bool-bool) | Sets a formula to a range of cells. |
| [set_shared_formula(shared_formula, row_number, column_number)](/cells/python-net/aspose.cells/cell/set_shared_formula/#str-int-int) | Sets shared formulas to a range of cells. |
| [set_shared_formula(shared_formula, row_number, column_number, options)](/cells/python-net/aspose.cells/cell/set_shared_formula/#str-int-int-FormulaParseOptions) | Sets shared formulas to a range of cells. |
| [set_shared_formula(shared_formula, row_number, column_number, options, values)](/cells/python-net/aspose.cells/cell/set_shared_formula/#str-int-int-FormulaParseOptions-list) | Sets shared formulas to a range of cells. |
| [get_leafs()](/cells/python-net/aspose.cells/cell/get_leafs/#) | Get all cells which reference to this cell directly and need to be updated when this cell is modified. |
| [get_leafs(recursive)](/cells/python-net/aspose.cells/cell/get_leafs/#bool) | Get all cells which will be updated when this cell is modified. |
| [set_dynamic_array_formula(array_formula, options, calculate_value)](/cells/python-net/aspose.cells/cell/set_dynamic_array_formula/#str-FormulaParseOptions-bool) | Sets dynamic array formula and make the formula spill into neighboring cells if possible. |
| [set_dynamic_array_formula(array_formula, options, values, calculate_range, calculate_value)](/cells/python-net/aspose.cells/cell/set_dynamic_array_formula/#str-FormulaParseOptions-list-bool-bool) | Sets dynamic array formula and make the formula spill into neighboring cells if possible. |
| [set_dynamic_array_formula(array_formula, options, values, calculate_range, calculate_value, copts)](/cells/python-net/aspose.cells/cell/set_dynamic_array_formula/#str-FormulaParseOptions-list-bool-bool-CalculationOptions) | Sets dynamic array formula and make the formula spill into neighboring cells if possible. |
| [set_table_formula(row_number, column_number, row_input_cell, column_input_cell, values)](/cells/python-net/aspose.cells/cell/set_table_formula/#int-int-str-str-list) | Create two-variable data table for given range starting from this cell. |
| [set_table_formula(row_number, column_number, input_cell, is_row_input, values)](/cells/python-net/aspose.cells/cell/set_table_formula/#int-int-str-bool-list) | Create one-variable data table for given range starting from this cell. |
| [set_table_formula(row_number, column_number, row_index_of_row_input_cell, column_index_of_row_input_cell, row_index_of_column_input_cell, column_index_of_column_input_cell, values)](/cells/python-net/aspose.cells/cell/set_table_formula/#int-int-int-int-int-int-list) | Create two-variable data table for given range starting from this cell. |
| [set_table_formula(row_number, column_number, row_index_of_input_cell, column_index_of_input_cell, is_row_input, values)](/cells/python-net/aspose.cells/cell/set_table_formula/#int-int-int-int-bool-list) | Create one-variable data table for given range starting from this cell. |
| [get_characters()](/cells/python-net/aspose.cells/cell/get_characters/#) | Returns all Characters objects <br/>that represents a range of characters within the cell text. |
| [get_characters(flag)](/cells/python-net/aspose.cells/cell/get_characters/#bool) | Returns all Characters objects <br/>that represents a range of characters within the cell text. |
| [get_string_value(format_strategy)](/cells/python-net/aspose.cells/cell/get_string_value/#CellValueFormatStrategy) | Gets the string value by specific formatted strategy. |
| [get_width_of_value()](/cells/python-net/aspose.cells/cell/get_width_of_value/#) | Gets the width of the value in unit of pixels. |
| [get_height_of_value()](/cells/python-net/aspose.cells/cell/get_height_of_value/#) | Gets the height of the value in unit of pixels. |
| [get_format_conditions()](/cells/python-net/aspose.cells/cell/get_format_conditions/#) | Gets format conditions which applies to this cell. |
| [get_formula(is_r1c1, is_local)](/cells/python-net/aspose.cells/cell/get_formula/#bool-bool) | Get the formula of this cell. |
| [get_precedents()](/cells/python-net/aspose.cells/cell/get_precedents/#) | Gets all references appearing in this cell's formula. |
| [get_dependents(is_all)](/cells/python-net/aspose.cells/cell/get_dependents/#bool) | Get all cells whose formula references to this cell directly. |
| [get_precedents_in_calculation()](/cells/python-net/aspose.cells/cell/get_precedents_in_calculation/#) | Gets all precedents(reference to cells in current workbook) used by this cell's formula while calculating it. |
| [get_dependents_in_calculation(recursive)](/cells/python-net/aspose.cells/cell/get_dependents_in_calculation/#bool) | Gets all cells whose calculated result depends on this cell. |
| [get_array_range()](/cells/python-net/aspose.cells/cell/get_array_range/#) | Gets the array range if the cell's formula is an array formula. |
| [remove_array_formula(leave_normal_formula)](/cells/python-net/aspose.cells/cell/remove_array_formula/#bool) | Remove array formula. |
| [copy(cell)](/cells/python-net/aspose.cells/cell/copy/#Cell) | Copies data from a source cell. |
| [characters(start_index, length)](/cells/python-net/aspose.cells/cell/characters/#int-int) | Returns a Characters object that represents a range of characters within the cell text. |
| [is_rich_text()](/cells/python-net/aspose.cells/cell/is_rich_text/#) | Indicates whether the cell string value is a rich text. |
| [set_characters(characters)](/cells/python-net/aspose.cells/cell/set_characters/#list) | Sets rich text format of the cell. |
| [get_merged_range()](/cells/python-net/aspose.cells/cell/get_merged_range/#) | Returns a [Range](/cells/python-net/aspose.cells/range) object which represents a merged range. |
| [get_html_string(html5)](/cells/python-net/aspose.cells/cell/get_html_string/#bool) | Gets the html string which contains data and some formats in this cell. |
| [to_json()](/cells/python-net/aspose.cells/cell/to_json/#) | Convert [Cell](/cells/python-net/aspose.cells/cell) to JSON struct data. |
| [equals(cell)](/cells/python-net/aspose.cells/cell/equals/#Cell) | Checks whether this object refers to the same cell with another cell object. |
| [get_conditional_formatting_result()](/cells/python-net/aspose.cells/cell/get_conditional_formatting_result/#) | Get the result of the conditional formatting. |
| [get_validation()](/cells/python-net/aspose.cells/cell/get_validation/#) | Gets the validation applied to this cell. |
| [get_validation_value()](/cells/python-net/aspose.cells/cell/get_validation_value/#) | Gets the value of validation which applied to this cell. |
| [get_table()](/cells/python-net/aspose.cells/cell/get_table/#) | Gets the table which contains this cell. |



### Example 


```python
from aspose.cells import TextAlignmentType, Workbook
from aspose.pydrawing import Color

excel = Workbook()
cells = excel.worksheets[0].cells
# Put a string into a cell
cell = cells.get(0, 0)
cell.put_value("Hello")
first = cell.string_value
# Put an integer into a cell
cell = cells.get("B1")
cell.put_value(12)
second = cell.int_value
# Put a double into a cell
cell = cells.get(0, 2)
cell.put_value(-1.234)
third = cell.double_value
# Put a formula into a cell
cell = cells.get("D1")
cell.formula = "=B1 + C1"
# Put a combined formula: "sum(average(b1,c1), b1)" to cell at b2
cell = cells.get("b2")
cell.formula = "=sum(average(b1,c1), b1)"
# Set style of a cell
style = cell.get_style()
# Set background color
style.background_color = Color.yellow
# Set format of a cell
style.font.name = "Courier New"
style.vertical_alignment = TextAlignmentType.TOP
cell.set_style(style)

```

### See Also
* module [aspose.cells](..)
* class [Cell](/cells/python-net/aspose.cells/cell)
* class [Range](/cells/python-net/aspose.cells/range)
