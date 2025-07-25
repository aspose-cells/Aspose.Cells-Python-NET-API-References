---
title: set_local_built_in_name Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 340
url: /de/aspose.cells/settableglobalizationsettings/set_local_built_in_name/
is_root: false
---
##  set_local_built_in_name(self, standard_name, local_name, bidirectional) {#str-str-bool}
Legt den lokalabhängigen Text für den integrierten Namen mit dem angegebenen Standardnamenstext fest.



```python

def set_local_built_in_name(self, standard_name, local_name, bidirectional):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| standard_name | str | Standardmäßiger Namenstext (en-US-Gebietsschema) des integrierten Namens.|
| local_name | str | Vom Gebietsschema abhängiger Namenstext|
| bidirectional | bool |Ob der lokale Namenstext automatisch dem Standardnamenstext zugeordnet wird.<br/>Wenn diese Option aktiviert ist, wird der lokale Namenstext automatisch in den Standardnamenstext umgewandelt.<br/>Der Benutzer muss also nicht erneut [`SettableGlobalizationSettings.set_standard_built_in_name`](/cells/python-net/de/aspose.cells/settableglobalizationsettings/set_standard_built_in_name) anrufen<br/> für dasselbe Paar aus Standard- und lokalen Namen|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`SettableGlobalizationSettings`](/cells/python-net/de/aspose.cells/settableglobalizationsettings)
