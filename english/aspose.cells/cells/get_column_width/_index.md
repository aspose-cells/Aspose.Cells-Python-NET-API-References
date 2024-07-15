---
title: get_column_width method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 350
url: /aspose.cells/cells/get_column_width/
is_root: false
---

## get_column_width {#int}

Gets the width(in unit of characters) of the specified column in normal view


### Returns 


Width of column. For spreadsheet, column width is measured as the number of characters
of the maximum digit width of the numbers 0~9 as rendered in the normal style's font.


```python
def get_column_width(self, column):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| column | int | Column index |


## get_column_width {#int-bool-aspose.cells.CellsUnitType}

Gets the column width.


### Returns 





```python
def get_column_width(self, column, is_original, unit_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| column | int | The column index. |
| is_original | bool | Indicates whether getting original width. |
| unit_type | [`CellsUnitType`](/cells/python-net/aspose.cells/cellsunittype) |  |



### See Also
* module [`aspose.cells`](../../)
* class [`Cells`](/cells/python-net/aspose.cells/cells)
