---
title: text_box_options property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 1130
url: /aspose.cells.drawing/oleobject/text_box_options/
is_root: false
---

## text_box_options property


Gets the text information in the shape

### Example 


```python
from aspose.cells.drawing.texts import ShapeTextVerticalAlignmentType

textBoxOpt = shape.text_box_options
textBoxOpt.shape_text_vertical_alignment = ShapeTextVerticalAlignmentType.LEFT
textBoxOpt.top_margin_pt = 0.2
textBoxOpt.left_margin_pt = 0.2
textBoxOpt.right_margin_pt = 0.2
textBoxOpt.bottom_margin_pt = 0.2

```
### Definition:
```python
@property
def text_box_options(self):
    ...
```

### See Also
* module [`aspose.cells.drawing`](../../)
* class [`OleObject`](/cells/python-net/aspose.cells.drawing/oleobject)
* class [`TextBoxOptions`](/cells/python-net/aspose.cells.drawing.texts/textboxoptions)
