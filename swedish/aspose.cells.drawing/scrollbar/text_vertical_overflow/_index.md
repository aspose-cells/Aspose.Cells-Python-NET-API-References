---
title: text_vertical_overflow fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1090
url: /sv/aspose.cells.drawing/scrollbar/text_vertical_overflow/
is_root: false
---
##  text_vertical_overflow fastighet

Hämtar och ställer in textens vertikala överflödestyp för formen som innehåller text.

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
* modul [aspose.cells.drawing](../../)
* klass [ScrollBar](/cells/python-net/sv/aspose.cells.drawing/scrollbar)
* klass [TextOverflowType](/cells/python-net/sv/aspose.cells.drawing/textoverflowtype)
