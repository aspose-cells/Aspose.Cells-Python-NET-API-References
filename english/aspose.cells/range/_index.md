---
title: Range class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 1300
url: /aspose.cells/range/
is_root: false
---

## Range class

Encapsulates the object that represents a range of cells within a spreadsheet.



The Range type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [current_region](/cells/python-net/aspose.cells/range/current_region) | Returns a Range object that represents the current region. <br/>The current region is a range bounded by any combination of blank rows and blank columns. |
| [hyperlinks](/cells/python-net/aspose.cells/range/hyperlinks) | Gets all hyperlink in the range. |
| [row_count](/cells/python-net/aspose.cells/range/row_count) | Gets the count of rows in the range. |
| [column_count](/cells/python-net/aspose.cells/range/column_count) | Gets the count of columns in the range. |
| [cell_count](/cells/python-net/aspose.cells/range/cell_count) | Gets all cell count in the range. |
| [name](/cells/python-net/aspose.cells/range/name) | Gets or sets the name of the range. |
| [refers_to](/cells/python-net/aspose.cells/range/refers_to) | Gets the range's refers to. |
| [address](/cells/python-net/aspose.cells/range/address) | Gets address of the range. |
| [left](/cells/python-net/aspose.cells/range/left) | Gets the distance, in points, from the left edge of column A to the left edge of the range. |
| [top](/cells/python-net/aspose.cells/range/top) | Gets the distance, in points, from the top edge of row 1 to the top edge of the range. |
| [width](/cells/python-net/aspose.cells/range/width) | Gets the width of a range in points. |
| [height](/cells/python-net/aspose.cells/range/height) | Gets the width of a range in points. |
| [first_row](/cells/python-net/aspose.cells/range/first_row) | Gets the index of the first row of the range. |
| [first_column](/cells/python-net/aspose.cells/range/first_column) | Gets the index of the first column of the range. |
| [value](/cells/python-net/aspose.cells/range/value) | Gets and sets the value of the range. |
| [column_width](/cells/python-net/aspose.cells/range/column_width) | Sets or gets the column width of this range |
| [row_height](/cells/python-net/aspose.cells/range/row_height) | Sets or gets the height of rows in this range |
| [entire_column](/cells/python-net/aspose.cells/range/entire_column) | Gets a Range object that represents the entire column (or columns) that contains the specified range. |
| [entire_row](/cells/python-net/aspose.cells/range/entire_row) | Gets a Range object that represents the entire row (or rows) that contains the specified range. |
| [worksheet](/cells/python-net/aspose.cells/range/worksheet) | Gets the [`Range.worksheet`](/cells/python-net/aspose.cells/range#worksheet)object which contains this range. |


### Methods
| Method | Description |
| :- | :- |
| [auto_fill](/cells/python-net/aspose.cells/range/auto_fill/#aspose.cells.Range) | Automaticall fill the target range. |
| [auto_fill](/cells/python-net/aspose.cells/range/auto_fill/#aspose.cells.Range-aspose.cells.AutoFillType) | Automaticall fill the target range. |
| [set_style](/cells/python-net/aspose.cells/range/set_style/#aspose.cells.Style-bool) | Apply the cell style. |
| [set_style](/cells/python-net/aspose.cells/range/set_style/#aspose.cells.Style) | Sets the style of the range. |
| [set_outline_borders](/cells/python-net/aspose.cells/range/set_outline_borders/#aspose.cells.CellBorderType-aspose.cells.CellsColor) | Sets the outline borders around a range of cells with same border style and color. |
| [set_outline_borders](/cells/python-net/aspose.cells/range/set_outline_borders/#aspose.cells.CellBorderType-aspose.pydrawing.Color) | Sets the outline borders around a range of cells with same border style and color. |
| [set_outline_borders](/cells/python-net/aspose.cells/range/set_outline_borders/#list-aspose.pydrawing.Color[]) | Sets out line borders around a range of cells. |
| [set_outline_border](/cells/python-net/aspose.cells/range/set_outline_border/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.cells.CellsColor) | Sets outline border around a range of cells. |
| [set_outline_border](/cells/python-net/aspose.cells/range/set_outline_border/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.pydrawing.Color) | Sets outline border around a range of cells. |
| [copy](/cells/python-net/aspose.cells/range/copy/#aspose.cells.Range-aspose.cells.PasteOptions) | Copying the range with paste special options. |
| [copy](/cells/python-net/aspose.cells/range/copy/#aspose.cells.Range) | Copies data (including formulas), formatting, drawing objects etc. from a source range. |
| [add_hyperlink](/cells/python-net/aspose.cells/range/add_hyperlink/#str-str-str) | Adds a hyperlink to a specified cell or a range of cells. |
| [get_enumerator](/cells/python-net/aspose.cells/range/get_enumerator/#) | Gets the enumerator for cells in this Range. |
| [is_intersect](/cells/python-net/aspose.cells/range/is_intersect/#aspose.cells.Range) | Indicates whether the range is intersect. |
| [intersect](/cells/python-net/aspose.cells/range/intersect/#aspose.cells.Range) | Returns a [`Range`](/cells/python-net/aspose.cells/range) object that represents the rectangular intersection of two ranges. |
| [union_rang](/cells/python-net/aspose.cells/range/union_rang/#aspose.cells.Range) | Returns the union result of two ranges. |
| [union](/cells/python-net/aspose.cells/range/union/#aspose.cells.Range) | Returns the union of two ranges. |
| [is_blank](/cells/python-net/aspose.cells/range/is_blank/#) | Indicates whether the range contains values. |
| [merge](/cells/python-net/aspose.cells/range/merge/#) | Combines a range of cells into a single cell. |
| [un_merge](/cells/python-net/aspose.cells/range/un_merge/#) | Unmerges merged cells of this range. |
| [put_value](/cells/python-net/aspose.cells/range/put_value/#str-bool-bool) | Puts a value into the range, if appropriate the value will be converted to other data type and cell's number format will be reset. |
| [apply_style](/cells/python-net/aspose.cells/range/apply_style/#aspose.cells.Style-aspose.cells.StyleFlag) | Applies formats for a whole range. |
| [set_inside_borders](/cells/python-net/aspose.cells/range/set_inside_borders/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.cells.CellsColor) | Set inside borders of the range. |
| [move_to](/cells/python-net/aspose.cells/range/move_to/#int-int) | Move the current range to the dest range. |
| [copy_data](/cells/python-net/aspose.cells/range/copy_data/#aspose.cells.Range) | Copies cell data (including formulas) from a source range. |
| [copy_value](/cells/python-net/aspose.cells/range/copy_value/#aspose.cells.Range) | Copies cell value from a source range. |
| [copy_style](/cells/python-net/aspose.cells/range/copy_style/#aspose.cells.Range) | Copies style settings from a source range. |
| [get_cell_or_null](/cells/python-net/aspose.cells/range/get_cell_or_null/#int-int) | Gets [`Cell`](/cells/python-net/aspose.cells/cell) object or null in this range. |
| [get_offset](/cells/python-net/aspose.cells/range/get_offset/#int-int) | Gets [`Range`](/cells/python-net/aspose.cells/range) range by offset. |



### Remarks 


The Range class denotes a region of Excel spreadsheet.
With this, you can format and set value of the range.
And you can simply copy range of Excel too.

### Example 


The following example shows how to create a range and set value the range of Excel.

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet Cells.
cells = workbook.worksheets[0].cells
#  Create a range (A1:D3).
range = cells.create_range("A1", "D3")
#  Set value to the range.
range.value = "Hello"
# Save the Excel file
workbook.save("book1.xlsm")

```

### See Also
* module [`aspose.cells`](..)
* class [`Cell`](/cells/python-net/aspose.cells/cell)
* class [`Range`](/cells/python-net/aspose.cells/range)
