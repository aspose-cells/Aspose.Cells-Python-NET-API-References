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
und der eingestellte Wert wird zurückgegeben, wenn diese Eigenschaft später abgerufen wird.
Der eingestellte Wert kann folgende Typen haben: [`Cell.value`](/cells/python-net/de/aspose.cells/cell#value),
oder ein Array solcher Werte oder ein Bereich, ein Name oder eine ReferredArea.
Wenn Sie diese Eigenschaft abrufen, bevor Sie einen Wert festlegen, wird die Funktion berechnet
durch die Standardberechnungs-Engine von Aspose.Cells und dann wird der berechnete Wert berechnet
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
