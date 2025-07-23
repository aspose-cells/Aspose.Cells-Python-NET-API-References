---
title: delete_rows Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 260
url: /de/aspose.cells/cells/delete_rows/
is_root: false
---
##  delete_rows(self, row_index, total_rows) {#int-int}
Löscht mehrere Zeilen.



```python

def delete_rows(self, row_index, total_rows):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| row_index | int | Der erste Zeilenindex, der gelöscht werden soll.|
| total_rows | int | Anzahl der zu löschenden Zeilen.|
###  Bemerkungen

Wenn der gelöschte Bereich den oberen Teil (nicht die ganze) der Tabelle (ListObject) enthält,
Der Bereich konnte nicht gelöscht werden und es wird nichts unternommen.
Mit MS Excel funktioniert es auf die gleiche Weise.

##  delete_rows(self, row_index, total_rows, update_reference) {#int-int-bool}
Löscht mehrere Zeilen im Arbeitsblatt.


###  Kehrt zurück




```python

def delete_rows(self, row_index, total_rows, update_reference):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| row_index | int | Index der ersten zu löschenden Zeile.|
| total_rows | int | Anzahl der zu löschenden Zeilen.|
| update_reference | bool | Gibt an, ob Verweise in anderen Arbeitsblättern aktualisiert werden sollen.|


##  delete_rows(self, row_index, total_rows, options) {#int-int-aspose.cells.DeleteOptions}
Löscht mehrere Zeilen im Arbeitsblatt.


###  Kehrt zurück




```python

def delete_rows(self, row_index, total_rows, options):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| row_index | int | Index der ersten zu löschenden Zeile.|
| total_rows | int | Anzahl der zu löschenden Zeilen.|
| options | [`DeleteOptions`](/cells/python-net/de/aspose.cells/deleteoptions) | Optionen für den Löschvorgang|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Cells`](/cells/python-net/de/aspose.cells/cells)
