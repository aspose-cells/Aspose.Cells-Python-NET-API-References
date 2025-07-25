---
title: enable_calculation_chain Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 70
url: /de/aspose.cells/formulasettings/enable_calculation_chain/
is_root: false
---
##  enable_calculation_chain Eigentum

Gibt an, ob die Berechnungskette für Formeln aktiviert werden soll. Der Standardwert ist „false“.

###  Bemerkungen

Wenn die Arbeitsmappe viele Formeln enthält und der Benutzer diese wiederholt berechnen muss
Wenn Sie nur einen kleinen Teil davon ändern, kann es aus Leistungsgründen hilfreich sein, die Berechnungskette zu aktivieren.
Wenn die Kette hingegen aktiviert ist, erfordert die Aufrechterhaltung des Kettenmodells zusätzlichen Speicher.
und es erfordert auch etwas mehr CPU-Zeit für einige andere Vorgänge, wie das Ändern von Zellenwerten oder Formeln.
Nach dem Ändern dieser Eigenschaft von false auf true wird die Berechnungskette analysiert und aufgebaut
zum Zeitpunkt der ersten Berechnung für die Arbeitsmappe, also die benötigte Zeit für die erste Berechnung
kann mehr sein als die normale Berechnung ohne Kette.
###  Definition:
```python
@property
def enable_calculation_chain(self):
    ...
@enable_calculation_chain.setter
def enable_calculation_chain(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`FormulaSettings`](/cells/python-net/de/aspose.cells/formulasettings)
