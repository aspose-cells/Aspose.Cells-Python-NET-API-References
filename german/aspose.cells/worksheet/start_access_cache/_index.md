---
title: start_access_cache Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 320
url: /de/aspose.cells/worksheet/start_access_cache/
is_root: false
---
##  start_access_cache(self, opts) {#aspose.cells.AccessCacheOptions}
Startet die Sitzung, die Caches verwendet, um auf die Daten in diesem Arbeitsblatt zuzugreifen.



```python

def start_access_cache(self, opts):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| opts | [`AccessCacheOptions`](/cells/python-net/de/aspose.cells/accesscacheoptions) | Möglichkeiten des Datenzugriffs|
###  Bemerkungen

Nach Abschluss des Datenzugriffs sollte [`Worksheet.close_access_cache`](/cells/python-net/de/aspose.cells/worksheet/close_access_cache)
mit denselben Optionen aufgerufen werden, um alle Caches zu löschen und den normalen Zugriffsmodus wiederherzustellen.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Worksheet`](/cells/python-net/de/aspose.cells/worksheet)
