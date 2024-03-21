---
title: is_param_literal_required Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 50
url: /de/aspose.cells/abstractcalculationengine/is_param_literal_required/
is_root: false
---
##  is_param_literal_required Eigentum

Gibt an, ob diese Engine während der Berechnung den Literaltext des Parameters benötigt. Der Standardwert ist falsch.

###  Bemerkungen

Wenn diese benutzerdefinierte Berechnungs-Engine den Literaltext des Parameters benötigt,
Es sind mehr Stapel erforderlich, um den Literaltext für Parameter zwischenzuspeichern
Die Methode Calculate() kann rekursiv aufgerufen werden, um den Wert des Parameters zu berechnen.
Im Allgemeinen wird der Literaltext für die Berechnung von Formeln nicht benötigt
und diese Eigenschaft sollte für die meisten Implementierungen auf „false“ gehalten werden, um eine bessere Leistung zu erzielen.
###  Definition:
```python
@property
def is_param_literal_required(self):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`AbstractCalculationEngine`](/cells/python-net/de/aspose.cells/abstractcalculationengine)
