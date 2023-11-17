﻿---
title: PivotFormatCondition class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 120
url: /aspose.cells.pivot/pivotformatcondition/
is_root: false
---

## PivotFormatCondition class

Represents a PivotTable Format Condition in PivotFormatCondition Collection.



The PivotFormatCondition type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [scope_type](/cells/python-net/aspose.cells.pivot/pivotformatcondition/scope_type) | Get and set scope type for the pivot table condition format . |
| [rule_type](/cells/python-net/aspose.cells.pivot/pivotformatcondition/rule_type) | Get and set rule type for the pivot table condition format . |
| [format_conditions](/cells/python-net/aspose.cells.pivot/pivotformatcondition/format_conditions) | Get formatconditions for the pivot table condition format . |


### Methods
| Method | Description |
| :- | :- |
| [add_data_area_condition](/cells/python-net/aspose.cells.pivot/pivotformatcondition/add_data_area_condition/#str) | Adds PivotTable conditional format limit in the data fields. |
| [add_data_area_condition](/cells/python-net/aspose.cells.pivot/pivotformatcondition/add_data_area_condition/#aspose.cells.pivot.PivotField) | Adds PivotTable conditional format limit in the data fields. |
| [add_row_area_condition](/cells/python-net/aspose.cells.pivot/pivotformatcondition/add_row_area_condition/#str) | Adds PivotTable conditional format limit in the row fields. |
| [add_row_area_condition](/cells/python-net/aspose.cells.pivot/pivotformatcondition/add_row_area_condition/#aspose.cells.pivot.PivotField) | Adds PivotTable conditional format limit in the row fields. |
| [add_column_area_condition](/cells/python-net/aspose.cells.pivot/pivotformatcondition/add_column_area_condition/#str) | Adds PivotTable conditional format limit in the column fields. |
| [add_column_area_condition](/cells/python-net/aspose.cells.pivot/pivotformatcondition/add_column_area_condition/#aspose.cells.pivot.PivotField) | Adds PivotTable conditional format limit in the column fields. |
| [set_conditional_areas](/cells/python-net/aspose.cells.pivot/pivotformatcondition/set_conditional_areas/#) | Sets conditional areas of PivotFormatCondition object. |



### Example 


```python
from aspose.cells import FormatConditionType, OperatorType, Workbook
from aspose.cells.pivot import PivotFieldType, PivotTableStyleType
from aspose.pydrawing import Color

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
pivotIndex = pivots.add("=Sheet1!A1:C9", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "year")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
# Add PivotFormatCondition
formatIndex = pivot.pivot_format_conditions.add()
pfc = pivot.pivot_format_conditions[formatIndex]
fcc = pfc.format_conditions
fcc.add_area(pivot.data_body_range)
idx = fcc.add_condition(FormatConditionType.CELL_VALUE)
fc = fcc[idx]
fc.formula1 = "100"
fc.operator = OperatorType.GREATER_OR_EQUAL
fc.style.background_color = Color.red
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

### See Also
* module [`aspose.cells.pivot`](..)
