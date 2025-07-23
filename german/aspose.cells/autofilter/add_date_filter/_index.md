---
title: add_date_filter Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cells/autofilter/add_date_filter/
is_root: false
---
##  add_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second) {#int-aspose.cells.DateTimeGroupingType-int-int-int-int-int-int}
Fügt einen Datumsfilter hinzu.



```python

def add_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| field_index | int | Der ganzzahlige Offset des Feldes, auf dem der Filter basieren soll<br/> (von links in der Liste; das äußerste linke Feld ist Feld 0).|
| date_time_grouping_type | [`DateTimeGroupingType`](/cells/python-net/de/aspose.cells/datetimegroupingtype) | Der Gruppierungstyp|
| year | int | Das Jahr.|
| month | int | Der Monat.|
| day | int | Der Tag.|
| hour | int | Die Stunde.|
| minute | int | Die Minute.|
| second | int | Der Zweite.|
###  Bemerkungen

Wenn DateTimeGroupingType „Year“ ist, wirkt sich nur der Parameter „Year“ aus.
Wenn DateTiemGroupingType Monat ist, wirken sich nur die Parameter Jahr und Monat aus.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`AutoFilter`](/cells/python-net/de/aspose.cells/autofilter)
