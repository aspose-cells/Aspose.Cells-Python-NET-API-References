---
title: convert_formula_reference_style Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 120
url: /de/aspose.cells/worksheet/convert_formula_reference_style/
is_root: false
---
##  convert_formula_reference_style(self, formula, to_r1c1, base_cell_row, base_cell_column) {#str-bool-int-int}
Konvertiert den Formelreferenzstil.


###  Kehrt zurück

Die konvertierte Formel.


```python

def convert_formula_reference_style(self, formula, to_r1c1, base_cell_row, base_cell_column):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| formula | str | Die umzuwandelnde Formel.|
| to_r1c1 | bool | In welchen Referenzstil die Formel konvertiert werden soll.<br/>Wenn die ursprüngliche Formel im A1-Referenzstil ist,<br/>dann sollte dieser Wert wahr sein, damit die Formel vom Referenzstil A1 in den Referenzstil R1C1 konvertiert wird.<br/>Wenn die ursprüngliche Formel vom Referenzstil R1C1 ist,<br/> dann sollte dieser Wert falsch sein, damit die Formel vom Referenzstil R1C1 in den Referenzstil A1 konvertiert wird.|
| base_cell_row | int | Der Zeilenindex der Basiszelle.|
| base_cell_column | int | Der Spaltenindex der Basiszelle.|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Worksheet`](/cells/python-net/de/aspose.cells/worksheet)
