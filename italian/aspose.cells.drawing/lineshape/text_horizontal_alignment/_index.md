---
title: text_horizontal_alignment proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 1040
url: /it/aspose.cells.drawing/lineshape/text_horizontal_alignment/
is_root: false
---
##  text_horizontal_alignment proprietà

Ottiene e imposta il tipo di allineamento orizzontale del testo della forma.

###  Esempio

```python
from aspose.cells import TextAlignmentType

if shape.text_horizontal_alignment == TextAlignmentType.BOTTOM:
    shape.text_horizontal_alignment = TextAlignmentType.CENTER

```
###  Definizione:
```python
@property
def text_horizontal_alignment(self):
    ...
@text_horizontal_alignment.setter
def text_horizontal_alignment(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`LineShape`](/cells/python-net/it/aspose.cells.drawing/lineshape)
* classe [`TextAlignmentType`](/cells/python-net/it/aspose.cells/textalignmenttype)
