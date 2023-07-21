﻿---
title: text_horizontal_alignment property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 190
url: /aspose.cells/comment/text_horizontal_alignment/
is_root: false
---

## text_horizontal_alignment property


Gets and sets the text horizontal alignment type of the comment.

### Example 


```python
from aspose.cells import TextAlignmentType

if comment1.text_horizontal_alignment == TextAlignmentType.FILL:
    comment1.text_horizontal_alignment = TextAlignmentType.CENTER

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
* module [`aspose.cells`](../../)
* class [`Comment`](/cells/python-net/aspose.cells/comment)
* class [`TextAlignmentType`](/cells/python-net/aspose.cells/textalignmenttype)
