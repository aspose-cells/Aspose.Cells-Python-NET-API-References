---
title: méthode add_signature_line
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 310
url: /fr/aspose.cells.drawing/shapecollection/add_signature_line/
is_root: false
---
##  add_signature_line(self, upper_left_row, upper_left_column, signature_line) {#int-int-aspose.cells.drawing.SignatureLine}
Ajoute une ligne de signature à la feuille de calcul.


###  Retour




```python

def add_signature_line(self, upper_left_row, upper_left_column, signature_line):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| upper_left_row | int | Index de la rangée supérieure gauche.|
| upper_left_column | int | Index de la colonne supérieure gauche.|
| signature_line | [`SignatureLine`](/cells/python-net/fr/aspose.cells.drawing/signatureline) | Représente un objet de ligne de signature.|

###  Exemple

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



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/fr/aspose.cells.drawing/shapecollection)
