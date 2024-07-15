﻿---
title: text_direction property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 950
url: /aspose.cells.drawing/smartartshape/text_direction/
is_root: false
---

## text_direction property


Gets/Sets the direction of the text flow for this object.

### Example 


```python
from aspose.cells import TextDirectionType

if shape.text_direction == TextDirectionType.CONTEXT:
    shape.text_direction = TextDirectionType.LEFT_TO_RIGHT

```
### Definition:
```python
@property
def text_direction(self):
    ...
@text_direction.setter
def text_direction(self, value):
    ...
```

### See Also
* module [`aspose.cells.drawing`](../../)
* class [`SmartArtShape`](/cells/python-net/aspose.cells.drawing/smartartshape)
* class [`TextDirectionType`](/cells/python-net/aspose.cells/textdirectiontype)
