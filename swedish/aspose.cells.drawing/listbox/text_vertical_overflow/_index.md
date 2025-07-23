---
title: text_vertical_overflow fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1120
url: /sv/aspose.cells.drawing/listbox/text_vertical_overflow/
is_root: false
---
##  text_vertical_overflow fastighet

Hämtar och anger den vertikala överflödestypen för text för den form som innehåller text.

###  Exempel

```python
from aspose.cells.drawing import TextOverflowType

if shape.text_vertical_overflow == TextOverflowType.CLIP:
    shape.text_vertical_overflow = TextOverflowType.OVERFLOW

```
###  Definition:
```python
@property
def text_vertical_overflow(self):
    ...
@text_vertical_overflow.setter
def text_vertical_overflow(self, value):
    ...
```

###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`ListBox`](/cells/python-net/sv/aspose.cells.drawing/listbox)
* klass [`TextOverflowType`](/cells/python-net/sv/aspose.cells.drawing/textoverflowtype)
