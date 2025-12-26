---
title: add_spinner method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 330
url: /aspose.cells.drawing/shapecollection/add_spinner/
is_root: false
---

## add_spinner(self, top_row, top, left_column, left, height, width) {#int-int-int-int-int-int}

Adds a Spinner to the worksheet.


### Returns 


A Spinner object.


```python

def add_spinner(self, top_row, top, left_column, left, height, width):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| top_row | int | Upper left row index. |
| top | int | Represents the vertical  offset of Spinner from its left row, in unit of pixel. |
| left_column | int | Upper left column index. |
| left | int | Represents the horizontal offset of Spinner from its left column, in unit of pixel. |
| height | int | Represents the height of Spinner, in unit of pixel. |
| width | int | Represents the width of Spinner, in unit of pixel. |

### Example 


```python

# add a spinner
spinner = shapes.add_spinner(1, 0, 1, 0, 100, 50)

```



### See Also
* module [`aspose.cells.drawing`](../../)
* class [`ShapeCollection`](/cells/python-net/aspose.cells.drawing/shapecollection)
* class [`Spinner`](/cells/python-net/aspose.cells.drawing/spinner)
