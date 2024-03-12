---
title: get_cell_by_index method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 50
url: /aspose.cells/row/get_cell_by_index/
is_root: false
---

## get_cell_by_index {#int}

Get the cell by specific index in the cells collection of this row.


### Returns 


The Cell object at given position.


```python
def get_cell_by_index(self, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The index(position) of the cell in the cells collection of this row. |
### Remarks

To traverse all cells in sequence without modification,
using [`Row.get_enumerator`](/cells/python-net/aspose.cells/row/get_enumerator) will give better performance than using this method to get cell one by one.


### See Also
* module [`aspose.cells`](../../)
* class [`Row`](/cells/python-net/aspose.cells/row)
