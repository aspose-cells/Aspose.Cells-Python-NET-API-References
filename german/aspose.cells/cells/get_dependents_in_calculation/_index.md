---
title: get_dependents_in_calculation Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 370
url: /de/aspose.cells/cells/get_dependents_in_calculation/
is_root: false
---
##  get_dependents_in_calculation {#int-int-bool}
Ruft alle Zellen ab, deren berechnetes Ergebnis von einer bestimmten Zelle abhängt.


###  Kehrt zurück

Enumerator zum Aufzählen aller abhängigen Objekte (Cell-Objekte)


```python
def get_dependents_in_calculation(self, row, column, recursive):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| row | int | Zeilenindex der spezifischen Zelle|
| column | int | Spaltenindex der spezifischen Zelle.|
| recursive | bool | Gibt die abhängigen Elemente zurück, die nicht direkt auf die spezifische Zelle verweisen<br/> aber Verweis auf andere Blätter dieser Zelle.|
###  Bemerkungen

Um diese Methode zu verwenden, stellen Sie bitte sicher, dass in der Arbeitsmappe der wahre Wert für festgelegt wurde
[`FormulaSettings.enable_calculation_chain`](/cells/python-net/de/aspose.cells/formulasettings#enable_calculation_chain) und wurde mit dieser Einstellung vollständig berechnet.
Wenn kein Formelverweis auf diese Zelle vorhanden ist, wird null zurückgegeben.
Weitere Einzelheiten und Beispiele finden Sie unter [`Cell.get_dependents_in_calculation`](/cells/python-net/de/aspose.cells/cell/get_dependents_in_calculation)


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Cells`](/cells/python-net/de/aspose.cells/cells)
