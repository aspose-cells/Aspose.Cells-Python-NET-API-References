---
title: update_custom_function_definition Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 410
url: /de/aspose.cells/workbook/update_custom_function_definition/
is_root: false
---
##  update_custom_function_definition {#aspose.cells.CustomFunctionDefinition}
Aktualisiert die Definition benutzerdefinierter Funktionen.



```python
def update_custom_function_definition(self, definition):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| definition | [`CustomFunctionDefinition`](/cells/python-net/de/aspose.cells/customfunctiondefinition) |Spezielle Definition benutzerdefinierter Funktionen für spezielle Benutzeranforderungen.|
###  Bemerkungen

Diese Methode kann für einige spezielle Szenarien verwendet werden. Wenn der Benutzer beispielsweise einige Parameter benötigt
Einige benutzerdefinierte Funktionen werden im Array-Modus berechnet, dann kann der Benutzer seine eigene Definition mit der Implementierung bereitstellen
[`CustomFunctionDefinition.get_array_mode_parameters`](/cells/python-net/de/aspose.cells/customfunctiondefinition/get_array_mode_parameters) für diese Funktionen.
Nachdem die Daten der Formeln aktualisiert wurden, werden die angegebenen Parameter automatisch im Array-Modus berechnet
bei der Berechnung entsprechender benutzerdefinierter Funktionen.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook)
