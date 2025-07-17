﻿---
title: text_horizontal_alignment property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 1060
url: /aspose.cells.drawing/listbox/text_horizontal_alignment/
is_root: false
---

## text_horizontal_alignment property


Gets and sets the text horizontal alignment type of the shape.

### Example 


```python
from aspose.cells import TextAlignmentType

if shape.text_horizontal_alignment == TextAlignmentType.BOTTOM:
    shape.text_horizontal_alignment = TextAlignmentType.CENTER

```
### Definition:
```python
@property
def text_horizontal_alignment(self):
    ...
@text_horizontal_alignment.setter
def text_horizontal_alignment(self, value):
    ...
```

### See Also
* module [`aspose.cells.drawing`](../../)
* class [`ListBox`](/cells/python-net/aspose.cells.drawing/listbox)
* class [`TextAlignmentType`](/cells/python-net/aspose.cells/textalignmenttype)
