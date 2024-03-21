---
title: set_local_built_in_name Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 340
url: /de/aspose.cells/settableglobalizationsettings/set_local_built_in_name/
is_root: false
---
##  set_local_built_in_name {#str-str-bool}
Legt den vom Gebietsschema abhängigen Text für den integrierten Namen mit dem angegebenen Standardnamentext fest.



```python
def set_local_built_in_name(self, standard_name, local_name, bidirectional):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| standard_name | str |Standard-Namenstext (En-US-Gebietsschema) des integrierten Namens.|
| local_name | str | Vom Gebietsschema abhängiger Namenstext|
| bidirectional | bool | Ob der lokale Namenstext automatisch dem Standardnamenstext zugeordnet wird.<br/>Bei „true“ wird der lokale Namenstext automatisch dem Standardnamenstext zugeordnet<br/>Daher muss der Benutzer nicht erneut [`SettableGlobalizationSettings.set_standard_built_in_name`](/cells/python-net/de/aspose.cells/settableglobalizationsettings/set_standard_built_in_name) anrufen<br/> für dasselbe Standard- und lokale Namenspaar|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`SettableGlobalizationSettings`](/cells/python-net/de/aspose.cells/settableglobalizationsettings)
