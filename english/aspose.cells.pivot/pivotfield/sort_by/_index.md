---
title: sort_by method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 170
url: /aspose.cells.pivot/pivotfield/sort_by/
is_root: false
---

## sort_by {#aspose.cells.SortOrder-int}

Sorts this pivot field.



```python
def sort_by(self, sort_type, field_sorted_by):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| sort_type | [`SortOrder`](/cells/python-net/aspose.cells/sortorder) | The type of sorting this field. |
| field_sorted_by | int | The index of pivot field sorted by.<br/>-1 means sorting by data labels of this field, others mean the index of data field sorted by. |


## sort_by {#aspose.cells.SortOrder-int-aspose.cells.pivot.PivotLineType-str}

Sorts this pivot field.



```python
def sort_by(self, sort_type, field_sorted_by, data_type, cell_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| sort_type | [`SortOrder`](/cells/python-net/aspose.cells/sortorder) | The type of sorting this field. |
| field_sorted_by | int | The index of pivot field sorted by.<br/>-1 means sorting by data labels of this field, others mean the index of data field sorted by. |
| data_type | [`PivotLineType`](/cells/python-net/aspose.cells.pivot/pivotlinetype) | The type of data sorted by. |
| cell_name | str | Sort by values in the row or column |



### See Also
* module [`aspose.cells.pivot`](../../)
* class [`PivotField`](/cells/python-net/aspose.cells.pivot/pivotfield)
