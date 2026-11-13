---
title: PivotShowValuesSetting class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 290
url: /aspose.cells.pivot/pivotshowvaluessetting/
is_root: false
---

## PivotShowValuesSetting class

Represents the settings about showing values as when the ShowDataAs calculation is in use.



The PivotShowValuesSetting type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [show_values_as](/cells/python-net/aspose.cells.pivot/pivotshowvaluessetting/show_values_as) | Gets and sets how to show values of a data field in the pivot report. |
| [calculation_type](/cells/python-net/aspose.cells.pivot/pivotshowvaluessetting/calculation_type) | Represents how to show values of a data field in the pivot report. |
| [base_field_index](/cells/python-net/aspose.cells.pivot/pivotshowvaluessetting/base_field_index) | Represents the base field for a ShowDataAs calculation when the ShowDataAs calculation is in use. |
| [base_item_position_type](/cells/python-net/aspose.cells.pivot/pivotshowvaluessetting/base_item_position_type) | Represents type of the base pivot item in the base field when the ShowDataAs calculation is in use.<br/>Because PivotItemPosition.Custom is only for read,if you need to set PivotItemPosition.Custom,<br/>please set PivotField.BaseItemIndex attribute. |
| [base_field_name](/cells/python-net/aspose.cells.pivot/pivotshowvaluessetting/base_field_name) | Gets caption of the pivot base field. |
| [base_item_caption](/cells/python-net/aspose.cells.pivot/pivotshowvaluessetting/base_item_caption) | Gets caption of the pivot item in the base field. |
| [base_item_index](/cells/python-net/aspose.cells.pivot/pivotshowvaluessetting/base_item_index) | Represents the custom index of the pivot item in the base field when the ShowDataAs calculation is in use. |
| [PREVIOUS_PIVOT_ITEM](/cells/python-net/aspose.cells.pivot/pivotshowvaluessetting/previous_pivot_item) | Special base item index: use the preceding pivot item.<br/>Valid for "Show Values As" calculations; effective in Excel 2010 and later. |
| [NEXT_PIVOT_ITEM](/cells/python-net/aspose.cells.pivot/pivotshowvaluessetting/next_pivot_item) | Special base item index: use the succeeding pivot item.<br/>Valid for "Show Values As" calculations; effective in Excel 2010 and later. |



### Example 


```python
from aspose.cells import Workbook
from aspose.cells.pivot import PivotFieldType, PivotItemPositionType, PivotShowValuesAsType, PivotTableStyleType

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
dataField = pivot.data_fields[0]
#  Display value as percentage of the grand total
dataField.show_values_as(PivotShowValuesAsType.PERCENTAGE_OF_TOTAL, 0, PivotItemPositionType.NEXT, -1)
#  Get the display calculation setting of data field
settings = dataField.show_values_setting
print(settings.show_values_as)
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

### See Also
* module [`aspose.cells.pivot`](..)
