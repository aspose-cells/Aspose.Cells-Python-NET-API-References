---
title: PivotFieldGroupOptions class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 160
url: /aspose.cells.pivot/pivotfieldgroupoptions/
is_root: false
---

## PivotFieldGroupOptions class

Options for pivot field grouping settings.



The PivotFieldGroupOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/cells/python-net/aspose.cells.pivot/pivotfieldgroupoptions/__init__/#) | Constructs a new instance of PivotFieldGroupOptions |


### Properties
| Property | Description |
| :- | :- |
| [is_auto_start](/cells/python-net/aspose.cells.pivot/pivotfieldgroupoptions/is_auto_start) | Gets or sets a value indicating whether the start value is automatically determined. |
| [is_auto_end](/cells/python-net/aspose.cells.pivot/pivotfieldgroupoptions/is_auto_end) | Gets or sets a value indicating whether the end value is automatically determined. |
| [start_number](/cells/python-net/aspose.cells.pivot/pivotfieldgroupoptions/start_number) | Gets or sets the start value of the grouping range. |
| [end_number](/cells/python-net/aspose.cells.pivot/pivotfieldgroupoptions/end_number) | Gets or sets the end value of the grouping range. |
| [start_date](/cells/python-net/aspose.cells.pivot/pivotfieldgroupoptions/start_date) | Gets or sets the start value of the grouping range. |
| [end_date](/cells/python-net/aspose.cells.pivot/pivotfieldgroupoptions/end_date) | Gets or sets the end value of the grouping range. |
| [interval](/cells/python-net/aspose.cells.pivot/pivotfieldgroupoptions/interval) | Gets or sets the interval size for each group. |
| [group_type](/cells/python-net/aspose.cells.pivot/pivotfieldgroupoptions/group_type) | Gets or sets the grouping type for pivot field.<br/>Only for grouping date time pivot field. |
| [discrete_group_items](/cells/python-net/aspose.cells.pivot/pivotfieldgroupoptions/discrete_group_items) | Gets and sets discrete group items. |
| [group_types](/cells/python-net/aspose.cells.pivot/pivotfieldgroupoptions/group_types) | Gets or sets the grouping type for pivot field. |
| [new_pivot_field](/cells/python-net/aspose.cells.pivot/pivotfieldgroupoptions/new_pivot_field) | Gets or sets a value indicating whether new pivot fields should be created after grouping. |



### Example 


```python
from aspose.cells import Workbook
from aspose.cells.pivot import PivotFieldGroupOptions, PivotGroupByType
from datetime import datetime

#  Load the sample workbook
wb = Workbook("sampleGroupPivotFieldsInPivotTable.xlsx")
#  Access the second worksheet and its pivot table
pt = wb.worksheets[1].pivot_tables[0]
#  Group the first row field (a date field) by months and quarters
options = PivotFieldGroupOptions()
options.start_date = datetime(2008, 1, 1)
options.end_date = datetime(2008, 9, 5)
options.group_types = [PivotGroupByType.MONTHS, PivotGroupByType.QUARTERS]
pt.row_fields[0].group(options)
#  Calculate the pivot table data and save the output file
pt.calculate_data()
wb.save("outputGroupPivotFieldsInPivotTable.xlsx")

```

### See Also
* module [`aspose.cells.pivot`](..)
