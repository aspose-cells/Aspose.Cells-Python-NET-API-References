---
title: add_signature_line yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 310
url: /tr/aspose.cells.drawing/shapecollection/add_signature_line/
is_root: false
---
##  add_signature_line(self, upper_left_row, upper_left_column, signature_line) {#int-int-aspose.cells.drawing.SignatureLine}
Çalışma sayfasına İmza Satırı ekler.


###  İadeler




```python

def add_signature_line(self, upper_left_row, upper_left_column, signature_line):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| upper_left_row | int | Sol üst sıra dizini.|
| upper_left_column | int | Sol üst sütun dizini.|
| signature_line | [`SignatureLine`](/cells/python-net/tr/aspose.cells.drawing/signatureline) | Bir imza satırı nesnesini temsil eder.|

###  Örnek

```python
from aspose.cells.drawing import SignatureLine

wSignatureLine = SignatureLine()
wSignatureLine.allow_comments = True
wSignatureLine.email = "example@example.com"
wSignatureLine.instructions = "Sign to confirm the excel content."
wSignatureLine.is_line = True
wSignatureLine.show_signed_date = True
wSignatureLine.signer = "User"
wSignatureLine.title = "tester"
# wSignatureLine.SignatureLineType = SignatureType.Stamp;
signatureLine1 = shapes.add_signature_line(0, 0, wSignatureLine)

```



###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](../../)
* sınıf [`ShapeCollection`](/cells/python-net/tr/aspose.cells.drawing/shapecollection)
