---
title: PivotFieldTop10AutoShowSettings class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 190
url: /aspose.cells.pivot/pivotfieldtop10autoshowsettings/
is_root: false
---

## PivotFieldTop10AutoShowSettings class

Represents the Top 10 AutoShow settings for a pivot field.



The PivotFieldTop10AutoShowSettings type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [is_auto_show](/cells/python-net/aspose.cells.pivot/pivotfieldtop10autoshowsettings/is_auto_show) | Indicates whether an "Top 10 AutoShow" filter is applied to this field. |
| [is_top](/cells/python-net/aspose.cells.pivot/pivotfieldtop10autoshowsettings/is_top) | Indicates whether the specified PivotTable field is autoshown ascending. |
| [auto_show_count](/cells/python-net/aspose.cells.pivot/pivotfieldtop10autoshowsettings/auto_show_count) | Represent the number of top or bottom items<br/>that are automatically shown in the specified PivotTable field. |
| [rank_by](/cells/python-net/aspose.cells.pivot/pivotfieldtop10autoshowsettings/rank_by) | Specifies the index of data field for AutoShow ranking.<br/>Represents auto show field index. -1 means PivotField itself.<br/>It should be the index of the data fields. |



### Remarks 


In xls : Implementing top 10 filters in Xls through Top 10 AutoShow 
In ooxml files: The underlying ooxml file format supports Top10 AutoShow, but Excel 2007 and later user interface only provides access via Top10 filter.
If XLS compatibility is not required, it is recommended to use Top10 filter instead.

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
# Show top 2 items by row field label.
rowField.top_10_auto_show(True, True, 2, -1)
sortSetting = rowField.top_10_auto_show_settings
print(sortSetting.is_auto_show)
pivot.calculate_data()
book.save("out.xlsx")

```

### See Also
* module [`aspose.cells.pivot`](..)
