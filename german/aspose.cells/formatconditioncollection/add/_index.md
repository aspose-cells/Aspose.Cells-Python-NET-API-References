---
title: add Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cells/formatconditioncollection/add/
is_root: false
---
##  add(cell_area, type, operator_type, formula1, formula2) {#CellArea-FormatConditionType-OperatorType-str-str}
Fügt den FormatConditions eine Formatierungsbedingung und einen betroffenen Zellbereich hinzu
Die FormatConditions können bis zu drei bedingte Formate enthalten.
Verweise auf die anderen Blätter sind in den Formeln der bedingten Formatierung nicht erlaubt.


###  Kehrt zurück

[0]: Objektindex der Formatierungsbedingung;[1] Bewirkter Zellbereichsindex.


```python
def add(self, cell_area, type, operator_type, formula1, formula2):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| cell_area | [CellArea](/cells/python-net/de/aspose.cells/cellarea) |Bedingt formatierter Zellbereich.|
| type | [FormatConditionType](/cells/python-net/de/aspose.cells/formatconditiontype) | Art der bedingten Formatierung. Es könnte eines der Mitglieder von FormatConditionType sein.|
| operator_type | [OperatorType](/cells/python-net/de/aspose.cells/operatortype) | Vergleichsoperator. Er könnte eines der Mitglieder von OperatorType sein.|
| formula1 | str | Der Wert oder Ausdruck, der der bedingten Formatierung zugeordnet ist.|
| formula2 | str | Der Wert oder Ausdruck, der der bedingten Formatierung zugeordnet ist|



###  Siehe auch
* Modul [aspose.cells](../../)
* Klasse [FormatConditionCollection](/cells/python-net/de/aspose.cells/formatconditioncollection)
