---
title: get_dependents_in_calculation Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 400
url: /de/aspose.cells/cells/get_dependents_in_calculation/
is_root: false
---
##  get_dependents_in_calculation(self, row, column, recursive) {#int-int-bool}
Ruft alle Zellen ab, deren berechnetes Ergebnis von einer bestimmten Zelle abhängt.


###  Kehrt zurück

Enumerator zum Aufzählen aller abhängigen Objekte (Cell Objekte)


```python

def get_dependents_in_calculation(self, row, column, recursive):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| row | int | Zeilenindex der jeweiligen Zelle|
| column | int |Spaltenindex der jeweiligen Zelle.|
| recursive | bool | Gibt die abhängigen Objekte zurück, die nicht direkt auf die jeweilige Zelle verweisen.<br/> aber Verweis auf andere Blätter dieser Zelle.|
###  Bemerkungen

Um diese Methode zu verwenden, stellen Sie bitte sicher, dass die Arbeitsmappe mit dem Wert true für
[`FormulaSettings.enable_calculation_chain`](/cells/python-net/de/aspose.cells/formulasettings#enable_calculation_chain) und wurde mit dieser Einstellung vollständig berechnet.
Wenn kein Formelverweis auf diese Zelle vorliegt, wird Null zurückgegeben.
Weitere Einzelheiten und Beispiele finden Sie unter [`Cell.get_dependents_in_calculation`](/cells/python-net/de/aspose.cells/cell/get_dependents_in_calculation)


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Cells`](/cells/python-net/de/aspose.cells/cells)
