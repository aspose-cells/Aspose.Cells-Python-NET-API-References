---
title: formula proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 500
url: /it/aspose.cells/cell/formula/
is_root: false
---
##  formula proprietà

Ottiene o imposta formula di [`Cell`](/cells/python-net/it/aspose.cells/cell).

###  Osservazioni

 Una stringa formula inizia sempre con un segno di uguale (=).
E si prega di utilizzare sempre la virgola (,) come delimitatore dei parametri, ad esempio "=SOMMA(A1, E1, H2)".

###  Esempio

```python
from aspose.cells import Workbook

excel = Workbook()
cells = excel.worksheets[0].cells
cells.get("B6").formula = "=SUM(B2:B5, E1) + sheet1!A1"

```
###  Definizione:
```python
@property
def formula(self):
    ...
@formula.setter
def formula(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Cell`](/cells/python-net/it/aspose.cells/cell)
