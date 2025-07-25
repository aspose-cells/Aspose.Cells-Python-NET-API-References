---
title: cell fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 70
url: /sv/aspose.cells/calculationdata/cell/
is_root: false
---
##  cell fastighet

Hämtar Cell-objektet där funktionen finns.

###  Anmärkningar

När man beräknar en formel utan att sätta den till cell,
såsom via [`Worksheet.calculate_formula`](/cells/python-net/sv/aspose.cells/worksheet/calculate_formula),
formeln kommer att beräknas precis som den har satts till cell A1,
så både [`CalculationData.cell_row`](/cells/python-net/sv/aspose.cells/calculationdata#cell_row) och [`CalculationData.cell_column`](/cells/python-net/sv/aspose.cells/calculationdata#cell_column) är 0.
Det kan dock hända att cell A1 i kalkylbladet inte har instansierats.
Så i en sådan situation kommer den här egenskapen att vara null.
###  Definition:
```python
@property
def cell(self):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`CalculationData`](/cells/python-net/sv/aspose.cells/calculationdata)
* klass [`Cell`](/cells/python-net/sv/aspose.cells/cell)
