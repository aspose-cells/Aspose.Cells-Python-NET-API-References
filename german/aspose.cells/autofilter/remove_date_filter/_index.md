---
title: remove_date_filter Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 150
url: /de/aspose.cells/autofilter/remove_date_filter/
is_root: false
---
##  remove_date_filter(field_index, date_time_grouping_type, year, month, day, hour, minute, second) {#int-DateTimeGroupingType-int-int-int-int-int-int}
Entfernt einen Datumsfilter.



```python
def remove_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| field_index | int | Der ganzzahlige Offset des Felds, auf dem der Filter basieren soll<br/> (von links in der Liste; das Feld ganz links ist Feld 0).|
| date_time_grouping_type | [DateTimeGroupingType](/cells/python-net/de/aspose.cells/datetimegroupingtype) | [DateTimeGroupingType](/cells/python-net/de/aspose.cells/datetimegroupingtype) |
| year | int | Das Jahr.|
| month | int | Der Monat.|
| day | int | Der Tag.|
| hour | int | Die Stunde.|
| minute | int | Die Minute.|
| second | int | Der Zweite.|
###  Bemerkungen

Wenn DateTimeGroupingType Year ist, wirkt sich nur das Parameterjahr aus.
Wenn DateTiemGroupingType Month ist, wirkt sich nur der Parameter Jahr und Monat aus.


###  Siehe auch
* Modul [aspose.cells](../../)
* Klasse [AutoFilter](/cells/python-net/de/aspose.cells/autofilter)
* Klasse [DateTimeGroupingType](/cells/python-net/de/aspose.cells/datetimegroupingtype)
