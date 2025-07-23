---
title: update_custom_function_definition Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 430
url: /de/aspose.cells/workbook/update_custom_function_definition/
is_root: false
---
##  update_custom_function_definition(self, definition) {#aspose.cells.CustomFunctionDefinition}
Aktualisiert die Definition benutzerdefinierter Funktionen.



```python

def update_custom_function_definition(self, definition):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| definition | [`CustomFunctionDefinition`](/cells/python-net/de/aspose.cells/customfunctiondefinition) | Spezielle Definition von benutzerdefinierten Funktionen für spezielle Anforderungen des Benutzers.|
###  Bemerkungen

Diese Methode kann für einige spezielle Szenarien verwendet werden. Zum Beispiel, wenn der Benutzer einige Parameter benötigt
von einigen benutzerdefinierten Funktionen im Array-Modus berechnet werden, dann kann der Benutzer seine eigene Definition mit implementierten
[`CustomFunctionDefinition.get_array_mode_parameters`](/cells/python-net/de/aspose.cells/customfunctiondefinition/get_array_mode_parameters) für diese Funktionen.
Nachdem die Daten der Formeln aktualisiert wurden, werden die angegebenen Parameter automatisch im Array-Modus berechnet
bei der Berechnung entsprechender benutzerdefinierter Funktionen.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook)
