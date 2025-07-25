---
title: add Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cells/formatconditioncollection/add/
is_root: false
---
##  add(self, cell_area, type, operator_type, formula1, formula2) {#aspose.cells.CellArea-aspose.cells.FormatConditionType-aspose.cells.OperatorType-str-str}
Fügt den FormatConditions eine Formatierungsbedingung und den betroffenen Zellbereich hinzu
Die FormatConditions können bis zu drei bedingte Formate enthalten.
Verweise auf andere Blätter sind in den Formeln der bedingten Formatierung nicht zulässig.


###  Kehrt zurück

[0]:Formatierungsbedingungsobjektindex;[1] Betroffen ist der Zellenbereichsindex.


```python

def add(self, cell_area, type, operator_type, formula1, formula2):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| cell_area | [`CellArea`](/cells/python-net/de/aspose.cells/cellarea) |Bedingt formatierter Zellbereich.|
| type | [`FormatConditionType`](/cells/python-net/de/aspose.cells/formatconditiontype) | Typ der bedingten Formatierung. Dies könnte eines der Mitglieder von FormatConditionType sein.|
| operator_type | [`OperatorType`](/cells/python-net/de/aspose.cells/operatortype) | Vergleichsoperator. Dies könnte eines der Mitglieder von OperatorType sein.|
| formula1 | str | Der mit der bedingten Formatierung verknüpfte Wert oder Ausdruck.|
| formula2 | str | Der mit der bedingten Formatierung verknüpfte Wert oder Ausdruck|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`FormatConditionCollection`](/cells/python-net/de/aspose.cells/formatconditioncollection)
