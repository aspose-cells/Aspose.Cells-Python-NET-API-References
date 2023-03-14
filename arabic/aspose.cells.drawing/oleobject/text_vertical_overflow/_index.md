---
title: text_vertical_overflow الملكية
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1200
url: /ar/aspose.cells.drawing/oleobject/text_vertical_overflow/
is_root: false
---
##  text_vertical_overflow الملكية

الحصول على وتعيين نوع تجاوز النص العمودي للشكل الذي يحتوي على نص.

###  مثال

```python
from aspose.cells.drawing import TextOverflowType

if shape.text_vertical_overflow == TextOverflowType.CLIP:
    shape.text_vertical_overflow = TextOverflowType.OVERFLOW

```
###  تعريف:
```python
@property
def text_vertical_overflow(self):
    ...
@text_vertical_overflow.setter
def text_vertical_overflow(self, value):
    ...
```

###  أنظر أيضا
* وحدة [aspose.cells.drawing](../../)
* فئة [OleObject](/cells/python-net/ar/aspose.cells.drawing/oleobject)
* فئة [TextOverflowType](/cells/python-net/ar/aspose.cells.drawing/textoverflowtype)
