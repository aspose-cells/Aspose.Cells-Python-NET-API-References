---
title: set_local_function_name Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 350
url: /de/aspose.cells/settableglobalizationsettings/set_local_function_name/
is_root: false
---
##  set_local_function_name {#str-str-bool}
Legt den vom Gebietsschema abhängigen Funktionsnamen fest, der dem angegebenen Standardfunktionsnamen entspricht.



```python
def set_local_function_name(self, standard_name, local_name, bidirectional):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| standard_name | str | Standardfunktionsname (En-US-Gebietsschema).|
| local_name | str | Vom Gebietsschema abhängiger Funktionsname|
| bidirectional | bool | Ob der lokale Funktionsname automatisch dem Standardfunktionsnamen zugeordnet wird.<br/>Wenn „true“, wird der lokale Name automatisch dem Standardnamen zugeordnet<br/>Daher muss der Benutzer nicht erneut [`SettableGlobalizationSettings.set_standard_function_name`](/cells/python-net/de/aspose.cells/settableglobalizationsettings/set_standard_function_name) anrufen<br/> für dasselbe Standard- und lokale Namenspaar|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`SettableGlobalizationSettings`](/cells/python-net/de/aspose.cells/settableglobalizationsettings)
