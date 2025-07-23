---
title: add_date_filter metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells/autofilter/add_date_filter/
is_root: false
---
##  add_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second) {#int-aspose.cells.DateTimeGroupingType-int-int-int-int-int-int}
Lägger till ett datumfilter.



```python

def add_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| field_index | int | Heltalsförskjutningen för fältet som du vill basera filtret på<br/> (från vänster i listan; fältet längst till vänster är fält 0).|
| date_time_grouping_type | [`DateTimeGroupingType`](/cells/python-net/sv/aspose.cells/datetimegroupingtype) | Grupperingstypen|
| year | int | Året.|
| month | int | Månaden.|
| day | int | Dagen.|
| hour | int | Timmen.|
| minute | int | Minuten.|
| second | int | Den andra.|
###  Anmärkningar

Om DateTimeGroupingType är Year, påverkas endast parametern year.
Om DateTiemGroupingType är Month, påverkas endast parametrarna år och månad.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`AutoFilter`](/cells/python-net/sv/aspose.cells/autofilter)
