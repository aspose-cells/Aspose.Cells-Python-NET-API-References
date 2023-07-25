﻿---
title: text_horizontal_overflow property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 970
url: /aspose.cells.drawing/label/text_horizontal_overflow/
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
* class [`Label`](/cells/python-net/aspose.cells.drawing/label)
* class [`TextOverflowType`](/cells/python-net/aspose.cells.drawing/textoverflowtype)
