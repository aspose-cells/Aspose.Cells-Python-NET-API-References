---
title: método add_signature_line
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 310
url: /es/aspose.cells.drawing/shapecollection/add_signature_line/
is_root: false
---
##  add_signature_line(self, upper_left_row, upper_left_column, signature_line) {#int-int-aspose.cells.drawing.SignatureLine}
Agrega una línea de firma a la hoja de cálculo.


###  Devoluciones




```python

def add_signature_line(self, upper_left_row, upper_left_column, signature_line):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| upper_left_row | int | Índice de la fila superior izquierda.|
| upper_left_column | int | Índice de la columna superior izquierda.|
| signature_line | [`SignatureLine`](/cells/python-net/es/aspose.cells.drawing/signatureline) | Representa un objeto de línea de firma.|

###  Ejemplo

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



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`ShapeCollection`](/cells/python-net/es/aspose.cells.drawing/shapecollection)
