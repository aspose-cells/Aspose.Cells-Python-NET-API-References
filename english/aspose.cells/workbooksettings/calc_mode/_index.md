﻿---
title: calc_mode property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 90
url: /aspose.cells/workbooksettings/calc_mode/
is_root: false
---

## calc_mode property


It specifies whether to calculate formulas manually,
automatically or automatically except for multiple table operations.

### Remarks 


Only sets for MS Excel.
Please manually calling Workbook.CalculateFormula() method to calculate formulas with Aspose.Cells.
NOTE: This member is now obsolete. Instead, please use FormulaSettings.CalculationMode.
This property will be removed 12 months later since February 2022. 
Aspose apologizes for any inconvenience you may have experienced.
### Definition:
```python
@property
def calc_mode(self):
    ...
@calc_mode.setter
def calc_mode(self, value):
    ...
```

### See Also
* module [aspose.cells](../../)
* class [CalcModeType](/cells/python-net/aspose.cells/calcmodetype)
* class [WorkbookSettings](/cells/python-net/aspose.cells/workbooksettings)
