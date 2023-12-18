﻿---
title: text_vertical_alignment property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 220
url: /aspose.cells/comment/text_vertical_alignment/
is_root: false
---

## text_vertical_alignment property


Gets and sets the text vertical alignment type of the comment.

### Example 


```python
from aspose.cells import TextAlignmentType

if comment1.text_vertical_alignment == TextAlignmentType.FILL:
    comment1.text_vertical_alignment = TextAlignmentType.CENTER

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
* module [`aspose.cells`](../../)
* class [`Comment`](/cells/python-net/aspose.cells/comment)
* class [`TextAlignmentType`](/cells/python-net/aspose.cells/textalignmenttype)
