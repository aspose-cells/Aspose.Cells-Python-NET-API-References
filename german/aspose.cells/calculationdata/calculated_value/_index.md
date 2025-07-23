---
title: calculated_value Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 60
url: /de/aspose.cells/calculationdata/calculated_value/
is_root: false
---
##  calculated_value Eigentum

Ruft den berechneten Wert für diese Funktion ab oder legt ihn fest.

###  Bemerkungen

Der Benutzer sollte diese Eigenschaft in seiner benutzerdefinierten Berechnungs-Engine für die Funktionen festlegen, die die Engine unterstützt.
und der festgelegte Wert wird zurückgegeben, wenn diese Eigenschaft später abgerufen wird.
Der eingestellte Wert kann von den möglichen Typen [`Cell.value`](/cells/python-net/de/aspose.cells/cell#value) sein,
oder ein Array solcher Werte oder ein Bereich, Name, ReferredArea.
Wenn Sie diese Eigenschaft abrufen, bevor Sie den Wert festlegen, wird die Funktion berechnet
durch die Standardberechnungsmaschine von Aspose.Cells und dann wird der berechnete Wert
zurückgegeben werden (im Allgemeinen sollte es #NAME? für benutzerdefinierte Funktionen sein).
###  Definition:
```python
@property
def calculated_value(self):
    ...
@calculated_value.setter
def calculated_value(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`CalculationData`](/cells/python-net/de/aspose.cells/calculationdata)
