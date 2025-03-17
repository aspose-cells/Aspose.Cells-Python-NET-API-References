---
title: add_freeform method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 120
url: /aspose.cells.drawing/shapecollection/add_freeform/
is_root: false
---

## add_freeform(self, upper_left_row, top, upper_left_column, left, height, width, paths) {#int-int-int-int-int-int-list}

Adds a freeform shape to the worksheet.


### Returns 


A freeform shape.


```python

def add_freeform(self, upper_left_row, top, upper_left_column, left, height, width, paths):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| upper_left_row | int | Upper left row index. |
| top | int | Represents the vertical  offset of Polygon from its left row, in unit of pixel. |
| upper_left_column | int | Upper left column index. |
| left | int | Represents the horizontal offset of Polygon from its left column, in unit of pixel. |
| height | int | Represents the height of Polygon, in unit of pixel. |
| width | int | Represents the width of Polygon, in unit of pixel. |
| paths | list | Represents a user-defined path |

### Example 


```python
from aspose.cells.drawing import ShapePath

# Custom figure
shapePath = ShapePath()
shapePath.move_to(60, 45)
shapePath.arc_to(25, 25, 0, 270)
shapePath.close()
shapePath.move_to(60, 20)
shapePath.line_to(110, 70)
shapePath.line_to(125, 155.5)
shapePath.arc_to(35.5, 35.5, 0, 270)
shapePath.close()
shapePath.move_to(150, 45)
shapePath.arc_to(25, 25, 0, 270)
shapePath1 = ShapePath()
shapePath1.move_to(0, 0)
shapePath1.cubic_bezier_to(48.24997, 0.6844,                                 96.5, -7.148871,                                 130, 11.517795)
shapePath1.cubic_bezier_to(163.5, 30.18446,                                 182.24997, 75.351,                                 201, 120.517795)
shapePath1.move_to(150, 80)
shapePath1.arc_to(25, 25, 0, 270)
# Insert custom figure into worksheet
shapes.add_freeform(1, 0, 1, 0, 200, 200, [shapePath, shapePath1])

```



### See Also
* module [`aspose.cells.drawing`](../../)
* class [`ShapeCollection`](/cells/python-net/aspose.cells.drawing/shapecollection)
