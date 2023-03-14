---
title: text_direction proprietà
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 930
url: /it/aspose.cells.drawing/smartartshape/text_direction/
is_root: false
---
##  text_direction proprietà

Ottiene/imposta la direzione del flusso di testo per questo oggetto.

###  Esempio

```python
from aspose.cells import TextDirectionType

if shape.text_direction == TextDirectionType.CONTEXT:
    shape.text_direction = TextDirectionType.LEFT_TO_RIGHT

```
###  Definizione:
```python
@property
def text_direction(self):
    ...
@text_direction.setter
def text_direction(self, value):
    ...
```

###  Guarda anche
* modulo [aspose.cells.drawing](../../)
* classe [SmartArtShape](/cells/python-net/it/aspose.cells.drawing/smartartshape)
* classe [TextDirectionType](/cells/python-net/it/aspose.cells/textdirectiontype)
