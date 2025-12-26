---
title: ListObject class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 30
url: /aspose.cells.tables/listobject/
is_root: false
---

## ListObject class

Represents a table in a worksheet.



The ListObject type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [start_row](/cells/python-net/aspose.cells.tables/listobject/start_row) | Gets the start row of the range. |
| [start_column](/cells/python-net/aspose.cells.tables/listobject/start_column) | Gets the start column of the range. |
| [end_row](/cells/python-net/aspose.cells.tables/listobject/end_row) | Gets the end  row of the range. |
| [end_column](/cells/python-net/aspose.cells.tables/listobject/end_column) | Gets the end column of the range. |
| [list_columns](/cells/python-net/aspose.cells.tables/listobject/list_columns) | Gets the [`ListColumn`](/cells/python-net/aspose.cells.tables/listcolumn) list of this table. |
| [show_header_row](/cells/python-net/aspose.cells.tables/listobject/show_header_row) | Gets and sets whether this Table shows header row. |
| [show_totals](/cells/python-net/aspose.cells.tables/listobject/show_totals) | Gets and sets whether this TAble shows total row. |
| [data_range](/cells/python-net/aspose.cells.tables/listobject/data_range) | Gets the data range of the Table. |
| [query_table](/cells/python-net/aspose.cells.tables/listobject/query_table) | Gets the linked QueryTable. |
| [data_source_type](/cells/python-net/aspose.cells.tables/listobject/data_source_type) | Gets the data source type of the table. |
| [has_auto_filter](/cells/python-net/aspose.cells.tables/listobject/has_auto_filter) | Indicates whether auto filter is applied to this table. |
| [auto_filter](/cells/python-net/aspose.cells.tables/listobject/auto_filter) | Gets auto filter of this table. |
| [display_name](/cells/python-net/aspose.cells.tables/listobject/display_name) | Gets and sets the display name of the table. |
| [comment](/cells/python-net/aspose.cells.tables/listobject/comment) | Gets and sets the comment of the table. |
| [show_table_style_first_column](/cells/python-net/aspose.cells.tables/listobject/show_table_style_first_column) | Indicates whether the first column in the table is the style applied to. |
| [show_table_style_last_column](/cells/python-net/aspose.cells.tables/listobject/show_table_style_last_column) | Indicates whether the last column in the table is the style applied to. |
| [show_table_style_row_stripes](/cells/python-net/aspose.cells.tables/listobject/show_table_style_row_stripes) | Indicates whether row stripe formatting is applied to. |
| [show_table_style_column_stripes](/cells/python-net/aspose.cells.tables/listobject/show_table_style_column_stripes) | Indicates whether column stripe formatting is applied to. |
| [table_style_type](/cells/python-net/aspose.cells.tables/listobject/table_style_type) | Gets and the built-in table style. |
| [table_style_name](/cells/python-net/aspose.cells.tables/listobject/table_style_name) | Gets and sets the table style name. |
| [xml_map](/cells/python-net/aspose.cells.tables/listobject/xml_map) | Gets an [`ListObject.xml_map`](/cells/python-net/aspose.cells.tables/listobject#xml_map) used for this list. |
| [alternative_text](/cells/python-net/aspose.cells.tables/listobject/alternative_text) | Gets and sets the alternative text. |
| [alternative_description](/cells/python-net/aspose.cells.tables/listobject/alternative_description) | Gets and sets the alternative description. |


### Methods
| Method | Description |
| :- | :- |
| [`put_cell_value(self, row_offset, column_offset, value)`](/cells/python-net/aspose.cells.tables/listobject/put_cell_value/#int-int-system.object) | Put the value to the cell. |
| [`put_cell_value(self, row_offset, column_offset, value, is_totals_row_label)`](/cells/python-net/aspose.cells.tables/listobject/put_cell_value/#int-int-system.object-bool) | Put the value to the cell. |
| [`put_cell_formula(self, row_offset, column_offset, formula)`](/cells/python-net/aspose.cells.tables/listobject/put_cell_formula/#int-int-system.string) | Put the formula to the cell in the table. |
| [`put_cell_formula(self, row_offset, column_offset, formula, is_totals_row_formula)`](/cells/python-net/aspose.cells.tables/listobject/put_cell_formula/#int-int-system.string-bool) | Put the formula to the cell in the table. |
| [`convert_to_range(self)`](/cells/python-net/aspose.cells.tables/listobject/convert_to_range/#) | Convert the table to range. |
| [`convert_to_range(self, options)`](/cells/python-net/aspose.cells.tables/listobject/convert_to_range/#aspose.cells.tables.tabletorangeoptions) | Convert the table to range. |
| [`resize(self, start_row, start_column, end_row, end_column, has_headers)`](/cells/python-net/aspose.cells.tables/listobject/resize/#int-int-int-int-bool) | Resize the range of the list object. |
| [`update_column_name(self)`](/cells/python-net/aspose.cells.tables/listobject/update_column_name/#) | Updates all list columns' name to cells in the table. |
| [`remove_auto_filter(self)`](/cells/python-net/aspose.cells.tables/listobject/remove_auto_filter/#) | Removes auto filter which is applied to this table. |
| [`filter(self)`](/cells/python-net/aspose.cells.tables/listobject/filter/#) | Filter the table. |
| [`apply_style_to_range(self)`](/cells/python-net/aspose.cells.tables/listobject/apply_style_to_range/#) | Apply the table style to the range. |



### Example 


```python
from aspose.cells import CellsHelper, Workbook
from aspose.cells.tables import TotalsCalculation

workbook = Workbook()
cells = workbook.worksheets[0].cells
for i in range(5):
    cells.get(0, i).put_value(CellsHelper.column_index_to_name(i))
for row in range(1, 10):
    for column in range(5):
        cells.get(row, column).put_value(row * column)
tables = workbook.worksheets[0].list_objects
index = tables.add(0, 0, 9, 4, True)
table = tables[0]
table.show_totals = True
table.list_columns[4].totals_calculation = TotalsCalculation.SUM
workbook.save(r"Book1.xlsx")

```

### See Also
* module [`aspose.cells.tables`](..)
* class [`ListColumn`](/cells/python-net/aspose.cells.tables/listcolumn)
