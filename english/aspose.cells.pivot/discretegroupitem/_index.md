---
title: DiscreteGroupItem class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 20
url: /aspose.cells.pivot/discretegroupitem/
is_root: false
---

## DiscreteGroupItem class

Represents an item of custom grouped field.



The DiscreteGroupItem type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self, name, item_indexes)`](/cells/python-net/aspose.cells.pivot/discretegroupitem/__init__/#system.string-list) | The constructor of custom group item of pivot field. |
| [`__init__(self, name, items)`](/cells/python-net/aspose.cells.pivot/discretegroupitem/__init__/#system.string-list) | The constructor of custom group item of pivot field. |



### Example 


```python
from aspose.cells import CellsFactory, Workbook
from aspose.cells.pivot import DiscreteGroupItem, PivotFieldGroupOptions, PivotFieldType, PivotTableStyleType
from datetime import datetime

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "product"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "carrot"
cells.get(3, 0).value = "potato"
cells.get(4, 0).value = "cherry"
# Create date style
dateStyle = CellsFactory().create_style()
dateStyle.custom = "m/d/yyyy"
cells.get(0, 1).value = "date"
cells.get(1, 1).value = datetime(2021, 2, 5)
cells.get(2, 1).value = datetime(2022, 3, 8)
cells.get(3, 1).value = datetime(2023, 4, 10)
cells.get(4, 1).value = datetime(2024, 5, 16)
# Set date style
cells.get(1, 1).set_style(dateStyle)
cells.get(2, 1).set_style(dateStyle)
cells.get(3, 1).set_style(dateStyle)
cells.get(4, 1).set_style(dateStyle)
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
pivots = sheet.pivot_tables
# Add a PivotTable
pivot = pivots.add("=Sheet1!A1:C5", "A12")
pivot.add_field_to_area(PivotFieldType.ROW, "product")
pivot.add_field_to_area(PivotFieldType.COLUMN, "date")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
# Group by fruit and vegetable
fruit = DiscreteGroupItem("fruit", [0, 3 ])
vegetable = DiscreteGroupItem("vegetable", [1, 2 ])
groupOptions = PivotFieldGroupOptions()
groupOptions.discrete_group_items = [fruit, vegetable]
pivot.row_fields[0].group(groupOptions)
pivot.calculate_data()
# do your business
book.save("DiscreteGroup.xlsx")

```

### See Also
* module [`aspose.cells.pivot`](..)
