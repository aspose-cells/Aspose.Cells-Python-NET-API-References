﻿---
title: text_vertical_overflow property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 1200
url: /aspose.cells.drawing/oleobject/text_vertical_overflow/
is_root: false
---

## text_vertical_overflow property


Gets and sets the text vertical overflow type of the shape which contains text.

### Example 


```python
from aspose.cells.drawing import TextOverflowType

if shape.text_vertical_overflow == TextOverflowType.CLIP:
    shape.text_vertical_overflow = TextOverflowType.OVERFLOW

```
### Definition:
```python
@property
def text_vertical_overflow(self):
    ...
@text_vertical_overflow.setter
def text_vertical_overflow(self, value):
    ...
```

### See Also
* module [`aspose.cells.drawing`](../../)
* class [`OleObject`](/cells/python-net/aspose.cells.drawing/oleobject)
* class [`TextOverflowType`](/cells/python-net/aspose.cells.drawing/textoverflowtype)
