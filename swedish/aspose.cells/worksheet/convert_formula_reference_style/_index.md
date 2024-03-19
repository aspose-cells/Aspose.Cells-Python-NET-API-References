---
title: convert_formula_reference_style metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 120
url: /sv/aspose.cells/worksheet/convert_formula_reference_style/
is_root: false
---
##  convert_formula_reference_style {#str-bool-int-int}
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
| to_r1c1 | bool | Vilken referensstil att konvertera formeln till.<br/>Om den ursprungliga formeln är av A1-referensstil,<br/>då bör detta värde vara sant så att formeln kommer att konverteras från A1 till R1C1 referensstil;<br/>Om den ursprungliga formeln är av R1C1-referensstil,<br/> då bör detta värde vara falskt så att formeln kommer att konverteras från R1C1 till A1 referensstil;|
| base_cell_row | int | Bascellens radindex.|
| base_cell_column | int | Kolumnindex för bascellen.|



###  Se även
* modul [`aspose.cells`](../../)
* klass [`Worksheet`](/cells/python-net/sv/aspose.cells/worksheet)
