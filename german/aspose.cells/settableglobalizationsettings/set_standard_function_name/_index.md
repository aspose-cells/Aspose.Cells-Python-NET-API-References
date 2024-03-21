---
title: set_standard_function_name Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 380
url: /de/aspose.cells/settableglobalizationsettings/set_standard_function_name/
is_root: false
---
##  set_standard_function_name {#str-str-bool}
Legt den vom Gebietsschema abhängigen Funktionsnamen entsprechend dem angegebenen Standardfunktionsnamen fest.



```python
def set_standard_function_name(self, local_name, standard_name, bidirectional):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| local_name | str | Vom Gebietsschema abhängiger Funktionsname|
| standard_name | str | Standardfunktionsname (En-US-Gebietsschema).|
| bidirectional | bool |Ob der Standardfunktionsname automatisch dem lokalen Funktionsnamen zugeordnet wird.<br/>Wenn „true“, wird der Standardname automatisch dem lokalen Namen zugeordnet<br/>Daher muss der Benutzer nicht erneut [`SettableGlobalizationSettings.set_local_function_name`](/cells/python-net/de/aspose.cells/settableglobalizationsettings/set_local_function_name) anrufen<br/> für dasselbe Standard- und lokale Namenspaar|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`SettableGlobalizationSettings`](/cells/python-net/de/aspose.cells/settableglobalizationsettings)
