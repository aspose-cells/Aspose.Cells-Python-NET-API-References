---
title: PivotItem class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 240
url: /aspose.cells.pivot/pivotitem/
is_root: false
---

## PivotItem class

Represents a item in a PivotField report.



The PivotItem type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [is_hidden](/cells/python-net/aspose.cells.pivot/pivotitem/is_hidden) | Gets and Sets whether the pivot item is hidden. |
| [position](/cells/python-net/aspose.cells.pivot/pivotitem/position) | Specifying the index of this item in all the PivotItems of the field. |
| [position_in_same_parent_node](/cells/python-net/aspose.cells.pivot/pivotitem/position_in_same_parent_node) | Specifying the position index in the PivotItems under the same parent node. |
| [is_hide_detail](/cells/python-net/aspose.cells.pivot/pivotitem/is_hide_detail) | Gets and sets whether the pivot item hides detail. |
| [is_detail_hidden](/cells/python-net/aspose.cells.pivot/pivotitem/is_detail_hidden) | Gets and sets whether the detail of this pivot item is hidden. |
| [is_calculated_item](/cells/python-net/aspose.cells.pivot/pivotitem/is_calculated_item) | Indicates whether this pivot item is a calculated formula item. |
| [is_formula](/cells/python-net/aspose.cells.pivot/pivotitem/is_formula) | Indicates whether this pivot item is a calculated formula item. |
| [is_missing](/cells/python-net/aspose.cells.pivot/pivotitem/is_missing) | Indicates whether the item was removed from the data source. |
| [value](/cells/python-net/aspose.cells.pivot/pivotitem/value) | Gets the value of the pivot item |
| [name](/cells/python-net/aspose.cells.pivot/pivotitem/name) | Gets the name of the pivot item. |
| [index](/cells/python-net/aspose.cells.pivot/pivotitem/index) | Gets the index of the pivot item in cache field. |
| [ALL_PAGE_ITEMS_INDEX](/cells/python-net/aspose.cells.pivot/pivotitem/all_page_items_index) | Select-all sentinel index of page items (0x7FFD, not a valid index) |


### Methods
| Method | Description |
| :- | :- |
| [`move(self, offset, is_same_parent)`](/cells/python-net/aspose.cells.pivot/pivotitem/move/#int-bool) | Moves the item up or down |
| [`move(self, offset)`](/cells/python-net/aspose.cells.pivot/pivotitem/move/#int) | Moves the item up or down in the pivot field |
| [`get_formula(self)`](/cells/python-net/aspose.cells.pivot/pivotitem/get_formula/#) | Gets the formula of this calculated item.<br/>Only works when this item is a calculated item. |
| [`get_string_value(self)`](/cells/python-net/aspose.cells.pivot/pivotitem/get_string_value/#) | Gets the string value of the pivot item<br/>If the value is null, it will return "" |
| [`get_double_value(self)`](/cells/python-net/aspose.cells.pivot/pivotitem/get_double_value/#) | Gets the double value of the pivot item<br/>If the value is null or not number ,it will return 0 |
| [`get_date_time_value(self)`](/cells/python-net/aspose.cells.pivot/pivotitem/get_date_time_value/#) | Gets the date time value of the pivot item<br/>If the value is null ,it will return DateTime.MinValue |



### Example 


```python
from aspose.cells import Workbook
from aspose.cells.pivot import PivotFieldType, PivotTableStyleType

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
cells.get(5, 0).value = "grape"
cells.get(6, 0).value = "blueberry"
cells.get(7, 0).value = "kiwi"
cells.get(8, 0).value = "cherry"
cells.get(0, 1).value = "year"
cells.get(1, 1).value = 2020
cells.get(2, 1).value = 2020
cells.get(3, 1).value = 2020
cells.get(4, 1).value = 2020
cells.get(5, 1).value = 2021
cells.get(6, 1).value = 2021
cells.get(7, 1).value = 2021
cells.get(8, 1).value = 2021
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
cells.get(5, 2).value = 90
cells.get(6, 2).value = 100
cells.get(7, 2).value = 110
cells.get(8, 2).value = 120
pivots = sheet.pivot_tables
pivot = pivots.add("=Sheet1!A1:C9", "A12")
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "year")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
# Change PivotField's attributes
rowField = pivot.row_fields[0]
rowField.display_name = "custom display name"
# Hide the first item
item = rowField.pivot_items[0]
item.is_hidden = True
pivot.calculate_data()
book.save("out.xlsx")

```

### See Also
* module [`aspose.cells.pivot`](..)
