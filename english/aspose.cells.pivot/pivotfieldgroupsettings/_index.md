---
title: PivotFieldGroupSettings class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 170
url: /aspose.cells.pivot/pivotfieldgroupsettings/
is_root: false
---

## PivotFieldGroupSettings class

Represents the group setting of pivot field.



The PivotFieldGroupSettings type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/cells/python-net/aspose.cells.pivot/pivotfieldgroupsettings/__init__/#) | Constructs a new instance of PivotFieldGroupSettings |


### Properties
| Property | Description |
| :- | :- |
| [type](/cells/python-net/aspose.cells.pivot/pivotfieldgroupsettings/type) | Gets the group type of pivot field. |



### Example 


```python
from aspose.cells import Workbook
from aspose.cells.pivot import PivotFieldGroupOptions, PivotFieldType

#  Load the sample workbook
wb = Workbook("sampleGroupPivotFieldsInPivotTable.xlsx")
#  Access the second worksheet and its pivot table
pt = wb.worksheets[1].pivot_tables[0]
#  FieldTwo is a data field: move it to the row area first,
#  because only row/column fields can be grouped
pt.add_field_to_area(PivotFieldType.ROW, "FieldTwo")
pt.calculate_data()
#  Group the numeric field into the ranges 0-1, 2-3, 4-5
options = PivotFieldGroupOptions()
options.start_number = 0.0
options.end_number = 5.0
options.interval = 2.0
pt.row_fields[1].group(options)
#  Calculate the pivot table data and save the output file
pt.calculate_data()
wb.save("outputNumberGroupPivotField.xlsx")

```

### See Also
* module [`aspose.cells.pivot`](..)
