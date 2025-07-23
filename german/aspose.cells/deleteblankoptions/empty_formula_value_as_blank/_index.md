---
title: empty_formula_value_as_blank Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 40
url: /de/aspose.cells/deleteblankoptions/empty_formula_value_as_blank/
is_root: false
---
##  empty_formula_value_as_blank Eigentum

Ob eine Zelle als leer betrachtet wird, wenn es sich um eine Formel handelt und das berechnete Ergebnis null oder eine leere Zeichenfolge ist.
Der Standardwert ist „false“.

###  Bemerkungen

Im Allgemeinen sollte der Benutzer sicherstellen, dass die Formeln berechnet wurden, bevor er den Vorgang löscht, bei dem diese Eigenschaft als „true“ festgelegt ist.
Andernfalls werden alle neu erstellten Formeln durch normale APIs wie [`Cell.formula`](/cells/python-net/de/aspose.cells/cell#formula) als leer betrachtet und können gelöscht werden
weil ihre berechneten Ergebnisse vor der Berechnung alle Null sind.
###  Definition:
```python
@property
def empty_formula_value_as_blank(self):
    ...
@empty_formula_value_as_blank.setter
def empty_formula_value_as_blank(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`DeleteBlankOptions`](/cells/python-net/de/aspose.cells/deleteblankoptions)
