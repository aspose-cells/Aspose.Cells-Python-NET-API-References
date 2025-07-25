---
title: text_vertical_overflow mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1240
url: /tr/aspose.cells.drawing/picture/text_vertical_overflow/
is_root: false
---
##  text_vertical_overflow mülk

Metni içeren şeklin metin dikey taşma türünü alır ve ayarlar.

###  Örnek

```python
from aspose.cells.drawing import TextOverflowType

if shape.text_vertical_overflow == TextOverflowType.CLIP:
    shape.text_vertical_overflow = TextOverflowType.OVERFLOW

```
###  Tanım:
```python
@property
def text_vertical_overflow(self):
    ...
@text_vertical_overflow.setter
def text_vertical_overflow(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](../../)
* sınıf [`Picture`](/cells/python-net/tr/aspose.cells.drawing/picture)
* sınıf [`TextOverflowType`](/cells/python-net/tr/aspose.cells.drawing/textoverflowtype)
