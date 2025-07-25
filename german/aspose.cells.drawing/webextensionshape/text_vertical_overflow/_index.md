---
title: text_vertical_overflow Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1040
url: /de/aspose.cells.drawing/webextensionshape/text_vertical_overflow/
is_root: false
---
##  text_vertical_overflow Eigentum

Ruft den vertikalen Textüberlauftyp der Form ab, die Text enthält, und legt ihn fest.

###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`TextOverflowType`](/cells/python-net/de/aspose.cells.drawing/textoverflowtype)
* Klasse [`WebExtensionShape`](/cells/python-net/de/aspose.cells.drawing/webextensionshape)
