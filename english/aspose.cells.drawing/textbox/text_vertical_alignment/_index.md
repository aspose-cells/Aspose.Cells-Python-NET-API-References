﻿---
title: text_vertical_alignment property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 1040
url: /aspose.cells.drawing/textbox/text_vertical_alignment/
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
* class [`TextAlignmentType`](/cells/python-net/aspose.cells/textalignmenttype)
* class [`TextBox`](/cells/python-net/aspose.cells.drawing/textbox)
