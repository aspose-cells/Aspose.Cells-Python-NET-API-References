﻿---
title: text_horizontal_overflow property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 1020
url: /aspose.cells.drawing/groupshape/text_horizontal_overflow/
is_root: false
---

## text_horizontal_overflow property


Gets and sets the text horizontal overflow type of the shape which contains text.

### Example 


```python
from aspose.cells.drawing import TextOverflowType

if shape.text_horizontal_overflow == TextOverflowType.CLIP:
    shape.text_horizontal_overflow = TextOverflowType.OVERFLOW

```
### Definition:
```python
@property
def text_horizontal_overflow(self):
    ...
@text_horizontal_overflow.setter
def text_horizontal_overflow(self, value):
    ...
```

### See Also
* module [`aspose.cells.drawing`](../../)
* class [`GroupShape`](/cells/python-net/aspose.cells.drawing/groupshape)
* class [`TextOverflowType`](/cells/python-net/aspose.cells.drawing/textoverflowtype)
