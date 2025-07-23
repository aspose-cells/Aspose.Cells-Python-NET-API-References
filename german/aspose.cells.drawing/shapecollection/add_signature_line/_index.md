---
title: add_signature_line Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 310
url: /de/aspose.cells.drawing/shapecollection/add_signature_line/
is_root: false
---
##  add_signature_line(self, upper_left_row, upper_left_column, signature_line) {#int-int-aspose.cells.drawing.SignatureLine}
Fügt dem Arbeitsblatt eine Signaturzeile hinzu.


###  Kehrt zurück




```python

def add_signature_line(self, upper_left_row, upper_left_column, signature_line):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| upper_left_row | int | Zeilenindex oben links.|
| upper_left_column | int | Index der oberen linken Spalte.|
| signature_line | [`SignatureLine`](/cells/python-net/de/aspose.cells.drawing/signatureline) | Stellt ein Signaturzeilenobjekt dar.|

###  Beispiel

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



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`ShapeCollection`](/cells/python-net/de/aspose.cells.drawing/shapecollection)
