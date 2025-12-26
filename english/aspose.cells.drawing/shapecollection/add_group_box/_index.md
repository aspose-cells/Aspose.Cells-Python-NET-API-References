---
title: add_group_box method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 130
url: /aspose.cells.drawing/shapecollection/add_group_box/
is_root: false
---

## add_group_box(self, top_row, top, left_column, left, height, width) {#int-int-int-int-int-int}

Adds a GroupBox to the worksheet.


### Returns 


A GroupBox object.


```python

def add_group_box(self, top_row, top, left_column, left, height, width):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| top_row | int | Upper left row index. |
| top | int | Represents the vertical  offset of GroupBox from its left row, in unit of pixel. |
| left_column | int | Upper left column index. |
| left | int | Represents the horizontal offset of GroupBox from its left column, in unit of pixel. |
| height | int | Represents the height of GroupBox, in unit of pixel. |
| width | int | Represents the width of GroupBox, in unit of pixel. |

### Example 


```python

# add a group box
groupBox = shapes.add_group_box(1, 0, 1, 0, 100, 50)

```



### See Also
* module [`aspose.cells.drawing`](../../)
* class [`GroupBox`](/cells/python-net/aspose.cells.drawing/groupbox)
* class [`ShapeCollection`](/cells/python-net/aspose.cells.drawing/shapecollection)
