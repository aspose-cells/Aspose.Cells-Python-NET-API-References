---
title: convert_formula_reference_style metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 120
url: /sv/aspose.cells/worksheet/convert_formula_reference_style/
is_root: false
---
##  convert_formula_reference_style(self, formula, to_r1c1, base_cell_row, base_cell_column) {#str-bool-int-int}
Konverterar formelreferensstilen.


###  Returnerar

Den konverterade formeln.


```python

def convert_formula_reference_style(self, formula, to_r1c1, base_cell_row, base_cell_column):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| formula | str | Formeln som ska konverteras.|
| to_r1c1 | bool | Vilken referensstil formeln ska konverteras till.<br/>Om den ursprungliga formeln är av referensformat A1,<br/>då bör detta värde vara sant så att formeln konverteras från referensstilen A1 till R1C1;<br/>Om den ursprungliga formeln är av referensstilen R1C1,<br/> då ska detta värde vara falskt så att formeln konverteras från R1C1 till A1-referensformatet;|
| base_cell_row | int | Radindexet för bascellen.|
| base_cell_column | int | Kolumnindexet för bascellen.|



###  Se även
* modul [`aspose.cells`](../../)
* klass [`Worksheet`](/cells/python-net/sv/aspose.cells/worksheet)
