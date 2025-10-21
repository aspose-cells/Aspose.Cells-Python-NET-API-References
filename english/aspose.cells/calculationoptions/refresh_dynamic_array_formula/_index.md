---
title: refresh_dynamic_array_formula property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 110
url: /aspose.cells/calculationoptions/refresh_dynamic_array_formula/
is_root: false
---

## refresh_dynamic_array_formula property


Indicates whether dynamic array formulas should be refreshed
before calculating formulas.

### Remarks 


If this property has been specified explicitly, then the specified value
will be used to determine whether refresh dynamic array formulas.
Otherwise([`CalculationOptions.user_specified_refresh_dynamic_array_formula`](/cells/python-net/aspose.cells/calculationoptions#user_specified_refresh_dynamic_array_formula) is flase),
the default value of it depends on what kind of formulas need to be calculated:
For calculating formulas for the workbook,
such as [`Workbook.calculate_formula`](/cells/python-net/aspose.cells/workbook/calculate_formula),
this property will be taken as true.
For other cases, such as [`Cell.calculate`](/cells/python-net/aspose.cells/cell/calculate)
or [`Worksheet.calculate_formula`](/cells/python-net/aspose.cells/worksheet/calculate_formula),
this property will be taken as false.
### Definition:
```python
@property
def refresh_dynamic_array_formula(self):
    ...
@refresh_dynamic_array_formula.setter
def refresh_dynamic_array_formula(self, value):
    ...
```

### See Also
* module [`aspose.cells`](../../)
* class [`CalculationOptions`](/cells/python-net/aspose.cells/calculationoptions)
