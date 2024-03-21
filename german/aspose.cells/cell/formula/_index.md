---
title: formula Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 490
url: /de/aspose.cells/cell/formula/
is_root: false
---
##  formula Eigentum

Ruft eine formula von [`Cell`](/cells/python-net/de/aspose.cells/cell) ab oder legt diese fest.

###  Bemerkungen

 Eine Zeichenfolge vom Typ formula beginnt immer mit einem Gleichheitszeichen (=).
Und bitte verwenden Sie immer Komma(,) als Parametertrennzeichen, z. B. „=SUM(A1, E1, H2)“.

###  Beispiel

```python
from aspose.cells import Workbook

excel = Workbook()
cells = excel.worksheets[0].cells
cells.get("B6").formula = "=SUM(B2:B5, E1) + sheet1!A1"

```
###  Definition:
```python
@property
def formula(self):
    ...
@formula.setter
def formula(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Cell`](/cells/python-net/de/aspose.cells/cell)
