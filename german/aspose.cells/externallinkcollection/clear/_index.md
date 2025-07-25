---
title: clear Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 30
url: /de/aspose.cells/externallinkcollection/clear/
is_root: false
---
##  clear(self) {#}
Entfernt alle externen Links.



```python

def clear(self):
    ...
```


###  Bemerkungen

Beim Entfernen externer Links werden auch alle Formeln entfernt, die auf diese verweisen, weil
die Verweise verlieren ihre Gültigkeit.

##  clear(self, update_references_as_local) {#bool}
Entfernt alle externen Links.



```python

def clear(self, update_references_as_local):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| update_references_as_local | bool |Ob alle Verweise externer Links in Formeln auf Verweise der aktuellen Arbeitsmappe selbst aktualisiert werden sollen.|
###  Bemerkungen

Wenn Referenzen aktualisiert werden müssen, dann sind dies die Referenzen externer Links in Formeln
wird, wenn möglich, in die aktuelle Arbeitsmappe geändert.
Beispielsweise lautet die ursprüngliche Formel einer Zelle "='externalsource.xlam'!customfunction()",
nach dem Entfernen externer Links wird die Formel zu „=customfunction()“;
Wenn die ursprüngliche Formel "='[externalsource.xlam]Sheet1'!$A$1" ist,
je nachdem, ob in der aktuellen Arbeitsmappe ein Blatt mit dem Namen „Sheet1“ vorhanden ist:
wenn wahr, wird die Formel zu "=Sheet1!$A$1";
Wenn falsch, wird die Formel zu „=#REF!$A$1“.

Wenn keine Aktualisierung der Referenzen erforderlich ist, werden alle Formeln mit Referenzen auf externe Links
werden ebenfalls entfernt, da diese Referenzen ungültig werden.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`ExternalLinkCollection`](/cells/python-net/de/aspose.cells/externallinkcollection)
