---
title: text_horizontal_overflow fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1050
url: /sv/aspose.cells.drawing/arcshape/text_horizontal_overflow/
is_root: false
---
##  text_horizontal_overflow fastighet

Hämtar och anger den horisontella överflödestypen för text för formen som innehåller text.

###  Exempel

```python
from aspose.cells.drawing import TextOverflowType

if shape.text_horizontal_overflow == TextOverflowType.CLIP:
    shape.text_horizontal_overflow = TextOverflowType.OVERFLOW

```
###  Definition:
```python
@property
def text_horizontal_overflow(self):
    ...
@text_horizontal_overflow.setter
def text_horizontal_overflow(self, value):
    ...
```

###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`ArcShape`](/cells/python-net/sv/aspose.cells.drawing/arcshape)
* klass [`TextOverflowType`](/cells/python-net/sv/aspose.cells.drawing/textoverflowtype)
