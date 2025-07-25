---
title: text_direction fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 970
url: /sv/aspose.cells.drawing/chartshape/text_direction/
is_root: false
---
##  text_direction fastighet

Hämtar/ställer in riktningen på textflödet för detta objekt.

###  Exempel

```python
from aspose.cells import TextDirectionType

if shape.text_direction == TextDirectionType.CONTEXT:
    shape.text_direction = TextDirectionType.LEFT_TO_RIGHT

```
###  Definition:
```python
@property
def text_direction(self):
    ...
@text_direction.setter
def text_direction(self, value):
    ...
```

###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`ChartShape`](/cells/python-net/sv/aspose.cells.drawing/chartshape)
* klass [`TextDirectionType`](/cells/python-net/sv/aspose.cells/textdirectiontype)
