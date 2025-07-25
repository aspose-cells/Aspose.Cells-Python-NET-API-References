---
title: calc_stack_size Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 30
url: /de/aspose.cells/calculationoptions/calc_stack_size/
is_root: false
---
##  calc_stack_size Eigentum

Die Stapelgröße für die rekursive Berechnung von Zellen. Der Standardwert ist 200.

###  Bemerkungen

Wenn eine große Anzahl von Zellen im Abhängigkeitsbaum rekursiv berechnet werden muss,
Im Berechnungsprozess kann es zu einer StackOverflowException kommen.
Wenn ja, sollte der Benutzer einen kleineren Wert für diese Eigenschaft angeben.
In einer solchen Situation sollte der Benutzer den richtigen Wert für diese Eigenschaft anhand der tatsächlichen Formeln und Daten bestimmen.
Ein zu kleiner Wert kann jedoch zu Leistungseinbußen bei der Formelberechnung führen, und ein Wert unter 2
macht es unmöglich, eine Formel zu berechnen, die von einer anderen abhängt. Wenn der angegebene Wert kleiner als 2 ist,
es wird auf 2 zurückgesetzt.
###  Definition:
```python
@property
def calc_stack_size(self):
    ...
@calc_stack_size.setter
def calc_stack_size(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`CalculationOptions`](/cells/python-net/de/aspose.cells/calculationoptions)
