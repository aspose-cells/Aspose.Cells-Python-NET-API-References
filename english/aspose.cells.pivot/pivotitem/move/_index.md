---
title: move method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 60
url: /aspose.cells.pivot/pivotitem/move/
is_root: false
---

## move(self, offset) {#int}

Moves the item up or down in the pivot field



```python

def move(self, offset):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| offset | int | The number of moving up or down.<br/>Move the item up if this is less than zero;<br/>Move the item down if this is greater than zero. |


## move(self, offset, is_same_parent) {#int-bool}

Moves the item up or down



```python

def move(self, offset, is_same_parent):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| offset | int | The number of moving up or down.<br/>Move the item up if this is less than zero;<br/>Move the item down if this is greater than zero. |
| is_same_parent | bool | Specifying whether moving operation is in the same parent node or not |
### Remarks

NOTE: This method is now obsolete. Instead, 
please use PivotTable.MoveItem(PivotFieldType, string[],bool,int) or PivotItem.Move(int) method instead.
This method will be removed 12 months later since November 2026. 
Aspose apologizes for any inconvenience you may have experienced.


### See Also
* module [`aspose.cells.pivot`](../../)
* class [`PivotItem`](/cells/python-net/aspose.cells.pivot/pivotitem)
