---
title: get_enumerator Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 30
url: /de/aspose.cells/rowcollection/get_enumerator/
is_root: false
---
##  get_enumerator(self, reversed, sync) {#bool-bool}
Ruft einen Enumerator ab, der die Zeilen dieser Sammlung durchläuft


###  Kehrt zurück

Der Zeilenenumerator


```python

def get_enumerator(self, reversed, sync):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| reversed | bool | ob Zeilen in umgekehrter Reihenfolge aufgezählt werden|
| sync | bool | ob der zurückgegebene Enumerator die Änderung der Zeilensammlung überprüfen soll<br/> und bleiben Sie damit synchron.|
###  Bemerkungen

Wenn die Zeilensammlung geändert wird (durch Operationen, die dazu führen können, dass neue Zeilen instanziiert werden oder
vorhandene Zeile entfernt werden) während der Traversierung mit dem Enumerator,
Der synchronisierte Enumerator sollte anstelle des normalen Enumerators verwendet werden, damit die Durchquerung fortgesetzt werden kann
von der Position direkt nach der, die vom letzten MoveNext() durchlaufen wurde.
Allerdings zusammen mit dem Vorteil, dass kein Element übersprungen oder wiederholt durchlaufen wird,
Der Nachteil des synchronisierten Enumerators besteht darin, dass die Leistung etwas beeinträchtigt wird
beim Vergleich mit einem normalen Enumerator.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`RowCollection`](/cells/python-net/de/aspose.cells/rowcollection)
