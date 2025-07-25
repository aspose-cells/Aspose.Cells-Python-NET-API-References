---
title: remove_at Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 40
url: /de/aspose.cells/externallinkcollection/remove_at/
is_root: false
---
##  remove_at(self, index) {#int}
Entfernt den angegebenen externen Link aus der Arbeitsmappe.



```python

def remove_at(self, index):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| index | int | der Index des zu entfernenden externen Links.|
###  Bemerkungen

Beim Entfernen des externen Links werden auch alle Formeln, die darauf verweisen, entfernt, weil
die Verweise verlieren ihre Gültigkeit.

##  remove_at(self, index, update_references_as_local) {#int-bool}
Entfernt den angegebenen externen Link aus der Arbeitsmappe.



```python

def remove_at(self, index, update_references_as_local):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| index | int | der Index des zu entfernenden externen Links.|
| update_references_as_local | bool | Ob alle Verweise des angegebenen externen Links auf die Referenz der aktuellen Arbeitsmappe selbst aktualisiert werden sollen.<br/> Weitere Einzelheiten zu diesem Parameter erhalten Sie unter [`ExternalLinkCollection.clear`](/cells/python-net/de/aspose.cells/externallinkcollection/clear).|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`ExternalLinkCollection`](/cells/python-net/de/aspose.cells/externallinkcollection)
