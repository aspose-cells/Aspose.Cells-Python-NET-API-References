---
title: add_signature_line metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 310
url: /sv/aspose.cells.drawing/shapecollection/add_signature_line/
is_root: false
---
##  add_signature_line(self, upper_left_row, upper_left_column, signature_line) {#int-int-aspose.cells.drawing.SignatureLine}
Lägger till en signaturrad i kalkylbladet.


###  Returnerar




```python

def add_signature_line(self, upper_left_row, upper_left_column, signature_line):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| upper_left_row | int | Index för övre vänstra raden.|
| upper_left_column | int | Index i övre vänstra kolumnen.|
| signature_line | [`SignatureLine`](/cells/python-net/sv/aspose.cells.drawing/signatureline) | Representerar ett signaturradsobjekt.|

###  Exempel

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



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`ShapeCollection`](/cells/python-net/sv/aspose.cells.drawing/shapecollection)
