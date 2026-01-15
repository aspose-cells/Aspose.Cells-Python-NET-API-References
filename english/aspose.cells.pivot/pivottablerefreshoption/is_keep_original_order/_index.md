---
title: is_keep_original_order property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 30
url: /aspose.cells.pivot/pivottablerefreshoption/is_keep_original_order/
is_root: false
---

## is_keep_original_order property


Indicates whether to keep pivot items' original order as old data source.

### Remarks 


Only applicable for the pivot field which is not sorted.
When refreshing such kind of pivot field, Ms Excel keeps the original order of old data source.
Default value of this property is true, representing the same behavior with Ms Excel.
If user needs the pivot field to be refreshed completely as the data in the new data source, this property should be set as false.
### Definition:
```python
@property
def is_keep_original_order(self):
    ...
@is_keep_original_order.setter
def is_keep_original_order(self, value):
    ...
```

### See Also
* module [`aspose.cells.pivot`](../../)
* class [`PivotTableRefreshOption`](/cells/python-net/aspose.cells.pivot/pivottablerefreshoption)
