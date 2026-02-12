---
title: data_field property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 510
url: /aspose.cells.pivot/pivottable/data_field/
is_root: false
---

## data_field property


Gets a [`PivotField`](/cells/python-net/aspose.cells.pivot/pivotfield) object that represents all the data fields in a PivotTable.
Read-only.
It would only be created when there are two or more data fields in the Data region.
Defaultly it is in row region. You can drag it to the row/column region with PivotTable.AddFieldToArea() method .

### Remarks 


NOTE: This method is now obsolete. Instead, 
please use PivotTable.ValuesField property.
This method will be removed 12 months later since October 2025. 
Aspose apologizes for any inconvenience you may have experienced.
### Definition:
```python
@property
def data_field(self):
    ...
```

### See Also
* module [`aspose.cells.pivot`](../../)
* class [`PivotField`](/cells/python-net/aspose.cells.pivot/pivotfield)
* class [`PivotTable`](/cells/python-net/aspose.cells.pivot/pivottable)
