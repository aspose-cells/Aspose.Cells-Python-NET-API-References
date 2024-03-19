---
title: get_array_mode_parameters Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cells/customfunctiondefinition/get_array_mode_parameters/
is_root: false
---
##  get_array_mode_parameters {#str}
Ruft die Indizes der Parameter einer bestimmten benutzerdefinierten Funktion ab, die im Array-Modus berechnet werden müssen.


###  Kehrt zurück

Indizes der Parameter, die im Array-Modus für eine bestimmte benutzerdefinierte Funktion berechnet werden müssen.
Der Standardwert ist null, es gibt keinen Parameter, der im Array-Modus für die benutzerdefinierte Funktion berechnet werden muss.


```python
def get_array_mode_parameters(self, function_name):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| function_name | str | Name der benutzerdefinierten Funktion.|
###  Bemerkungen

Für einen Ausdruck, der berechnet werden muss, am Beispiel von A:A+B:B:
Im Wertemodus wird im Allgemeinen ein einzelner Wert entsprechend der aktuellen Zellbasis berechnet.
Im Array-Modus werden jedoch alle Werte von A1+B1,A2+B2,A3+B3,... berechnet und für die Berechnung verwendet.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`CustomFunctionDefinition`](/cells/python-net/de/aspose.cells/customfunctiondefinition)
