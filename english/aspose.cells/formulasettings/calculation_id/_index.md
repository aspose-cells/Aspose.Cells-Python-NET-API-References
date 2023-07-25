﻿---
title: calculation_id property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 50
url: /aspose.cells/formulasettings/calculation_id/
is_root: false
---

## calculation_id property


Specifies the version of the calculation engine used to calculate values in the workbook.

### Remarks 


This property is only for saving the settings to resultant spreadsheet file
so that other applications(such as ms excel) may act accordingly when loading and manipulating the resultant file.
In the case of ms excel, if the value of this property is less than the recalculation engine identifier associated
with the application that opens the resultant file, the application will recalculate the results of all formulas
on this workbook immediately after loading the file.
For performance consideration for most users' applications, we do not calculate any formula on the workbook automatically,
no matter what value has been set for this property.
### Definition:
```python
@property
def calculation_id(self):
    ...
@calculation_id.setter
def calculation_id(self, value):
    ...
```

### See Also
* module [`aspose.cells`](../../)
* class [`FormulaSettings`](/cells/python-net/aspose.cells/formulasettings)
