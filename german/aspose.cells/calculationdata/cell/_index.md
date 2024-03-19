---
title: cell Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 70
url: /de/aspose.cells/calculationdata/cell/
is_root: false
---
##  cell Eigentum

Ruft das Cell-Objekt ab, in dem sich die Funktion befindet.

###  Bemerkungen

Wenn Sie eine Formel berechnen, ohne sie auf cell zu setzen,
z.B. unter [`Worksheet.calculate_formula`](/cells/python-net/de/aspose.cells/worksheet/calculate_formula),
Die Formel wird genauso berechnet, wie sie auf cell A1 eingestellt wurde.
also sind sowohl [`CalculationData.cell_row`](/cells/python-net/de/aspose.cells/calculationdata#cell_row) als auch [`CalculationData.cell_column`](/cells/python-net/de/aspose.cells/calculationdata#cell_column) 0.
Allerdings wurde cell A1 im Arbeitsblatt möglicherweise nicht instanziiert.
In einer solchen Situation ist diese Eigenschaft also null.
###  Definition:
```python
@property
def cell(self):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`CalculationData`](/cells/python-net/de/aspose.cells/calculationdata)
* Klasse [`Cell`](/cells/python-net/de/aspose.cells/cell)
