---
title: group method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 160
url: /aspose.cells.pivot/pivotfield/group/
is_root: false
---

## group(self) {#}

Automatically group the field.



```python

def group(self):
    ...
```


### Remarks

If the field only contains blank and date time, the field will be grouped by Months.
If the field only contains blank and number, the field will be grouped by Number.
Else only returns false without any group.

## group(self, options) {#aspose.cells.pivot.PivotFieldGroupOptions}

Groups the pivot field with options.


### Returns 





```python

def group(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | aspose.cells.pivot.PivotFieldGroupOptions | Options for pivot field grouping settings. |



### See Also
* module [`aspose.cells.pivot`](../../)
* class [`PivotField`](/cells/python-net/aspose.cells.pivot/pivotfield)
