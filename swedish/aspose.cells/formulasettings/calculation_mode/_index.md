---
title: calculation_mode fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 60
url: /sv/aspose.cells/formulasettings/calculation_mode/
is_root: false
---
##  calculation_mode fastighet

Hämtar eller ställer in läget för arbetsboksberäkning i MS Excel.

###  Anmärkningar

Den här egenskapen är endast till för att spara inställningarna till den resulterande kalkylbladsfilen.
så att andra program (som MS Excel) kan agera därefter när de laddar och manipulerar den resulterande filen.
Av prestandaskäl för de flesta användarnas applikationer beräknar vi inte någon formler i arbetsboken automatiskt,
oavsett vilket läge som har ställts in för den här egenskapen.
Om användaren behöver beräkna formler, vänligen anropa alltid metoder på olika objekt enligt krav:
[`Workbook.calculate_formula`](/cells/python-net/aspose.cells/workbook/calculate_formula), [`Worksheet.calculate_formula`](/cells/python-net/aspose.cells/worksheet/calculate_formula),
[`Cell.calculate`](/cells/python-net/sv/aspose.cells/cell/calculate), ...osv.
###  Definition:
```python
@property
def calculation_mode(self):
    ...
@calculation_mode.setter
def calculation_mode(self, value):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`CalcModeType`](/cells/python-net/sv/aspose.cells/calcmodetype)
* klass [`FormulaSettings`](/cells/python-net/sv/aspose.cells/formulasettings)
