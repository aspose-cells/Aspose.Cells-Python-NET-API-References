---
title: sort_by method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 280
url: /aspose.cells.pivot/pivotfield/sort_by/
is_root: false
---

## sort_by(self, sort_type) {#aspose.cells.SortOrder}

Sorts this pivot field.



```python

def sort_by(self, sort_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| sort_type | aspose.cells.SortOrder | The type of sorting this field. |


## sort_by(self, sort_type, field_sorted_by) {#aspose.cells.SortOrder-int}

Sorts this pivot field.



```python

def sort_by(self, sort_type, field_sorted_by):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| sort_type | aspose.cells.SortOrder | The type of sorting this field. |
| field_sorted_by | int | The index of pivot field sorted by.<br/>-1 means sorting by data labels of this field, others mean the index of data field sorted by. |
### Remarks

NOTE: This property is now obsolete. Instead, 
please use PivotField.SortBy(SortOrder, int,string) method or PivotField.IsAutoSort property instead.
This method will be removed 12 months later since September 2026.
Aspose apologizes for any inconvenience you may have experienced.

## sort_by(self, sort_type, field_sorted_by, cell_name) {#aspose.cells.SortOrder-int-System.String}

Sorts this pivot field.



```python

def sort_by(self, sort_type, field_sorted_by, cell_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| sort_type | aspose.cells.SortOrder | The type of sorting this field. |
| field_sorted_by | int | The index of pivot field sorted by.<br/>-1 means sorting by data labels of this field, others mean the index of data field sorted by. |
| cell_name | System.String | Sort by values in the row or column.<br/>If Null, group by total of the field, else group by values in selected column or row. |


## sort_by(self, sort_type, field_sorted_by, data_type, cell_name) {#aspose.cells.SortOrder-int-aspose.cells.pivot.PivotLineType-System.String}

Sorts this pivot field.



```python

def sort_by(self, sort_type, field_sorted_by, data_type, cell_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| sort_type | aspose.cells.SortOrder | The type of sorting this field. |
| field_sorted_by | int | The index of pivot field sorted by.<br/>-1 means sorting by data labels of this field, others mean the index of data field sorted by. |
| data_type | aspose.cells.pivot.PivotLineType | The type of data sorted by. |
| cell_name | System.String | Sort by values in the row or column |
### Remarks

NOTE: This property is now obsolete. Instead, 
please use PivotField.SortBy(SortOrder, int,string) method instead.
This method will be removed 12 months later since September 2026.
Aspose apologizes for any inconvenience you may have experienced.


### See Also
* module [`aspose.cells.pivot`](../../)
* class [`PivotField`](/cells/python-net/aspose.cells.pivot/pivotfield)
