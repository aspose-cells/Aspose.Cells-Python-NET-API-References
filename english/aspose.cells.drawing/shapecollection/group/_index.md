﻿---
title: group method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 450
url: /aspose.cells.drawing/shapecollection/group/
is_root: false
---

## group(self, group_items) {#list}

Group the shapes.


### Returns 


Return the group shape.


```python

def group(self, group_items):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| group_items | list | the group items. |
### Remarks

The shape in the groupItems should not be grouped.
The shape must be in this Shapes collection.
### Example 


```python

# add first shape
shapes.add_rectangle(2, 0, 2, 0, 50, 50)
# add second shape
shapes.add_rectangle(6, 0, 2, 0, 30, 30)
shapesArr = [shapes[0], shapes[1]]
groupShape = shapes.group(shapesArr)

```



### See Also
* module [`aspose.cells.drawing`](../../)
* class [`ShapeCollection`](/cells/python-net/aspose.cells.drawing/shapecollection)
