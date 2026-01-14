---
title: get_cell_area method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 110
url: /aspose.cells/autofilter/get_cell_area/
is_root: false
---

## get_cell_area(self) {#}

Gets the [`CellArea`](/cells/python-net/aspose.cells/cellarea) where the this AutoFilter applies to.


### Returns 


the area this filter applies to


```python

def get_cell_area(self):
    ...
```




## get_cell_area(self, refresh_applied_range) {#bool}

Gets the [`CellArea`](/cells/python-net/aspose.cells/cellarea) where the specified AutoFilter applies.


### Returns 


the area this filter applies to


```python

def get_cell_area(self, refresh_applied_range):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| refresh_applied_range | bool | Whether refresh the applied range.<br/>For the applied range of auto filter, the last row may change when cells data changes.<br/>If this flag is true, then the last row of the range will be re-calculated according to current cells data. |



### See Also
* module [`aspose.cells`](../../)
* class [`AutoFilter`](/cells/python-net/aspose.cells/autofilter)
* class [`CellArea`](/cells/python-net/aspose.cells/cellarea)
