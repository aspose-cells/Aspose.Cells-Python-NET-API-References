---
title: text_horizontal_overflow proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 1070
url: /it/aspose.cells.drawing/listbox/text_horizontal_overflow/
is_root: false
---
##  text_horizontal_overflow proprietà

Ottiene e imposta il tipo di overflow orizzontale del testo della forma che contiene testo.

###  Esempio

```python
from aspose.cells.drawing import TextOverflowType

if shape.text_horizontal_overflow == TextOverflowType.CLIP:
    shape.text_horizontal_overflow = TextOverflowType.OVERFLOW

```
###  Definizione:
```python
@property
def text_horizontal_overflow(self):
    ...
@text_horizontal_overflow.setter
def text_horizontal_overflow(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ListBox`](/cells/python-net/it/aspose.cells.drawing/listbox)
* classe [`TextOverflowType`](/cells/python-net/it/aspose.cells.drawing/textoverflowtype)
