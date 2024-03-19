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

Hämtar objektet Cell där funktionen finns.

###  Anmärkningar

När du beräknar en formel utan att ställa in den till cell,
till exempel via [`Worksheet.calculate_formula`](/cells/python-net/sv/aspose.cells/worksheet/calculate_formula),
formeln kommer att beräknas precis som den har satts till cell A1,
så både [`CalculationData.cell_row`](/cells/python-net/sv/aspose.cells/calculationdata#cell_row) och [`CalculationData.cell_column`](/cells/python-net/sv/aspose.cells/calculationdata#cell_column) är 0.
cell A1 i kalkylbladet kanske inte har instansierats.
Så för en sådan typ av situation kommer den här egenskapen att vara ogiltig.
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
