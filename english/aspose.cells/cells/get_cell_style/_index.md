﻿---
title: get_cell_style method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 330
url: /aspose.cells/cells/get_cell_style/
is_root: false
---

## get_cell_style(self, row, column) {#int-int}

Get the style of given cell.


### Returns 


the style of given cell.


```python

def get_cell_style(self, row, column):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| row | int | row index |
| column | int | column |
### Remarks

The returned style is only the one set for the cell or inherited from the row/column of the cell,
does not include the applied properties by other settings such as conditional formattings.


### See Also
* module [`aspose.cells`](../../)
* class [`Cells`](/cells/python-net/aspose.cells/cells)
* class [`Style`](/cells/python-net/aspose.cells/style)
