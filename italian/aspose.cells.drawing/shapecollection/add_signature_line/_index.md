---
title: Metodo add_signature_line
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 310
url: /it/aspose.cells.drawing/shapecollection/add_signature_line/
is_root: false
---
##  add_signature_line(self, upper_left_row, upper_left_column, signature_line) {#int-int-aspose.cells.drawing.SignatureLine}
Aggiunge una riga di firma al foglio di lavoro.


###  ritorna




```python

def add_signature_line(self, upper_left_row, upper_left_column, signature_line):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| upper_left_row | int | Indice della riga in alto a sinistra.|
| upper_left_column | int | Indice della colonna in alto a sinistra.|
| signature_line | [`SignatureLine`](/cells/python-net/it/aspose.cells.drawing/signatureline) | Rappresenta un oggetto riga firma.|

###  Esempio

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



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection)
