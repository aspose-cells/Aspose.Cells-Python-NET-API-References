﻿---
title: group_by method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 70
url: /aspose.cells.pivot/pivotfield/group_by/
is_root: false
---

## group_by {#list-bool}

Custom group the field.



```python
def group_by(self, custom_group_items, new_field):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| custom_group_items | list | The custom group items. |
| new_field | bool | Indicates whether adding a new field to the pivottable |


## group_by {#float-float-float-bool}

Group the file by number.



```python
def group_by(self, start, end, interval, new_field):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| start | float | The start value |
| end | float | The end of value |
| interval | float | The interval |
| new_field | bool | Indicates whether adding a new field to the pivottable |


## group_by {#DateTime-DateTime-list-float-bool}

Group the file by the date group types.



```python
def group_by(self, start, end, groups, interval, first_as_new_field):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| start | DateTime | The start datetime |
| end | DateTime | The end of datetime |
| groups | list | Group types |
| interval | float | The interval |
| first_as_new_field | bool | Indicates whether adding a new field to the pivottable.



### See Also
* module [`aspose.cells.pivot`](../../)
* class [`PivotField`](/cells/python-net/aspose.cells.pivot/pivotfield)