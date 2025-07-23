---
title: add_identify Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cells.pivot/pivotpagefields/add_identify/
is_root: false
---
##  add_identify(self, range_index, page_item_index) {#int-list}
Legt fest, welche Elementbezeichnung in jedem Seitenfeld zur Identifizierung des Datenbereichs verwendet werden soll.
Die pageItemIndex.Length muss gleich PageFieldCount sein, fügen Sie also zuerst das Seitenfeld hinzu.



```python

def add_identify(self, range_index, page_item_index):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| range_index | int | Der Konsolidierungsdatenbereichsindex.|
| page_item_index | list | Der Seitenelementindex in jedem Seitenfeld.<br/>pageItemIndex[2] = 1 bedeutet, dass das zweite Element im dritten Feld zur Identifizierung dieses Bereichs verwendet werden soll.<br/> pageItemIndex[1] = -1 bedeutet, dass im zweiten Feld kein Element vorhanden ist, das zur Identifizierung dieses Bereichs verwendet werden kann<br/> und MS erstellt automatisch ein „leeres“ Element im zweiten Feld, um diesen Bereich zu identifizieren.|



###  Siehe auch
* Modul [`aspose.cells.pivot`](../../)
* Klasse [`PivotPageFields`](/cells/python-net/de/aspose.cells.pivot/pivotpagefields)
