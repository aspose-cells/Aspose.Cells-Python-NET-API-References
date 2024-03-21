---
title: is_param_array_mode_required Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 40
url: /de/aspose.cells/abstractcalculationengine/is_param_array_mode_required/
is_root: false
---
##  is_param_array_mode_required Eigentum

Gibt an, ob diese Engine die Berechnung des Parameters im Array-Modus benötigt. Der Standardwert ist falsch.
Wenn bei der Berechnung des Zolls [`CalculationData.get_param_value_in_array_mode`](/cells/python-net/de/aspose.cells/calculationdata/get_param_value_in_array_mode) erforderlich ist
Funktionen und der Benutzer hat die Definition für sie nicht aktualisiert
(von [`Workbook.update_custom_function_definition`](/cells/python-net/de/aspose.cells/workbook/update_custom_function_definition)),
Diese Eigenschaft muss auf „true“ gesetzt werden.

###  Bemerkungen

Wenn diese benutzerdefinierte Berechnungs-Engine die Berechnung des Parameters im Array-Modus erfordert,
Es sind mehr Stapel erforderlich, um den Baum für Parameter zwischenzuspeichern
Die Methode Calculate() kann rekursiv aufgerufen werden, um den Wert des Parameters zu berechnen.
Behalten Sie aus Leistungsgründen diese Eigenschaft bitte als Standardwert (falsch) bei.
wenn kein besonderer Bedarf besteht.
###  Definition:
```python
@property
def is_param_array_mode_required(self):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`AbstractCalculationEngine`](/cells/python-net/de/aspose.cells/abstractcalculationengine)
