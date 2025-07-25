---
title: text_vertical_alignment Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1090
url: /de/aspose.cells.drawing/lineshape/text_vertical_alignment/
is_root: false
---
##  text_vertical_alignment Eigentum

Ruft den Typ der vertikalen Textausrichtung der Form ab und legt ihn fest.

###  Beispiel

```python
from aspose.cells import TextAlignmentType

if shape.text_vertical_alignment == TextAlignmentType.BOTTOM:
    shape.text_vertical_alignment = TextAlignmentType.CENTER

```
###  Definition:
```python
@property
def text_vertical_alignment(self):
    ...
@text_vertical_alignment.setter
def text_vertical_alignment(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`LineShape`](/cells/python-net/de/aspose.cells.drawing/lineshape)
* Klasse [`TextAlignmentType`](/cells/python-net/de/aspose.cells/textalignmenttype)
