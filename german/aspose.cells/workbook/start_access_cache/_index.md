---
title: start_access_cache Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 400
url: /de/aspose.cells/workbook/start_access_cache/
is_root: false
---
##  start_access_cache(self, opts) {#aspose.cells.AccessCacheOptions}
Startet die Sitzung, die Caches für den Datenzugriff verwendet.



```python

def start_access_cache(self, opts):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| opts | [`AccessCacheOptions`](/cells/python-net/de/aspose.cells/accesscacheoptions) | Möglichkeiten des Datenzugriffs|
###  Bemerkungen

Wenn der Cache des angegebenen Datenzugriffs erfordert, dass einige Datenmodelle im Arbeitsblatt schreibgeschützt sind,
dann werden die entsprechenden Datenmodelle in jedem Arbeitsblatt dieser Arbeitsmappe als „schreibgeschützt“ betrachtet.
und der Benutzer sollte keine davon ändern.


Nach Abschluss des Datenzugriffs sollte [`Workbook.close_access_cache`](/cells/python-net/de/aspose.cells/workbook/close_access_cache)
mit denselben Optionen aufgerufen werden, um alle Caches zu löschen und den normalen Zugriffsmodus wiederherzustellen.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook)
