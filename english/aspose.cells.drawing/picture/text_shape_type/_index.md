﻿---
title: text_shape_type property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 1190
url: /aspose.cells.drawing/picture/text_shape_type/
is_root: false
---

## text_shape_type property


Gets and sets the preset text shape type.

### Example 


```python
from aspose.cells.drawing import AutoShapeType

if shape.text_shape_type == AutoShapeType.UNKNOWN:
    shape.text_shape_type = AutoShapeType.RECTANGLE

```
### Definition:
```python
@property
def text_shape_type(self):
    ...
@text_shape_type.setter
def text_shape_type(self, value):
    ...
```

### See Also
* module [aspose.cells.drawing](../../)
* class [AutoShapeType](/cells/python-net/aspose.cells.drawing/autoshapetype)
* class [Picture](/cells/python-net/aspose.cells.drawing/picture)
