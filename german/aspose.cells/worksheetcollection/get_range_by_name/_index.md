---
title: get_range_by_name Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 120
url: /de/aspose.cells/worksheetcollection/get_range_by_name/
is_root: false
---
##  get_range_by_name(self, range_name) {#str}
Ruft das Range-Objekt anhand des vordefinierten Namens ab.


###  Kehrt zurück

Range-Objekt.


Gibt null zurück, wenn der benannte Bereich nicht existiert.


```python

def get_range_by_name(self, range_name):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| range_name | str | Name des Bereichs.|


##  get_range_by_name(self, range_name, current_sheet_index, include_table) {#str-int-bool}
Ruft [`Range`](/cells/python-net/de/aspose.cells/range) anhand des vordefinierten Namens oder Tabellennamens ab


###  Kehrt zurück




```python

def get_range_by_name(self, range_name, current_sheet_index, include_table):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| range_name | str | Name des Bereichs oder Tabellenname.|
| current_sheet_index | int | Der Blattindex. -1 steht für global.|
| include_table | bool | Gibt an, ob alle Tabellen geprüft werden.|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Range`](/cells/python-net/de/aspose.cells/range)
* Klasse [`WorksheetCollection`](/cells/python-net/de/aspose.cells/worksheetcollection)
