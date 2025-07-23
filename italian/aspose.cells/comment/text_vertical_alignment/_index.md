---
title: text_vertical_alignment proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 220
url: /it/aspose.cells/comment/text_vertical_alignment/
is_root: false
---
##  text_vertical_alignment proprietà

Ottiene e imposta il tipo di allineamento verticale del testo del commento.

###  Esempio

```python
from aspose.cells import TextAlignmentType

if comment1.text_vertical_alignment == TextAlignmentType.FILL:
    comment1.text_vertical_alignment = TextAlignmentType.CENTER

```
###  Definizione:
```python
@property
def text_vertical_alignment(self):
    ...
@text_vertical_alignment.setter
def text_vertical_alignment(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Comment`](/cells/python-net/it/aspose.cells/comment)
* classe [`TextAlignmentType`](/cells/python-net/it/aspose.cells/textalignmenttype)
