﻿---
title: text_vertical_alignment property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 1030
url: /aspose.cells.drawing/slicershape/text_vertical_alignment/
is_root: false
---

## text_vertical_alignment property


Gets and sets the text vertical alignment type of the shape.

### Example 


```python
from aspose.cells import TextAlignmentType

if shape.text_vertical_alignment == TextAlignmentType.BOTTOM:
    shape.text_vertical_alignment = TextAlignmentType.CENTER

```
### Definition:
```python
@property
def text_vertical_alignment(self):
    ...
@text_vertical_alignment.setter
def text_vertical_alignment(self, value):
    ...
```

### See Also
* module [`aspose.cells.drawing`](../../)
* class [`SlicerShape`](/cells/python-net/aspose.cells.drawing/slicershape)
* class [`TextAlignmentType`](/cells/python-net/aspose.cells/textalignmenttype)
