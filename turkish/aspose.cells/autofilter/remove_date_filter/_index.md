---
title: remove_date_filter yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 150
url: /tr/aspose.cells/autofilter/remove_date_filter/
is_root: false
---
##  remove_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second) {#int-aspose.cells.DateTimeGroupingType-int-int-int-int-int-int}
Tarih filtresini kaldırır.



```python

def remove_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| field_index | int | Filtreyi temel almak istediğiniz alanın tam sayı ofseti<br/> (listenin solundan; en soldaki alan 0 alanıdır).|
| date_time_grouping_type | [`DateTimeGroupingType`](/cells/python-net/tr/aspose.cells/datetimegroupingtype) | Gruplama türü|
| year | int | Yıl.|
| month | int | Ay.|
| day | int | Gün.|
| hour | int | Saat.|
| minute | int | Dakika.|
| second | int | İkincisi.|
###  Notlar

DateTimeGroupingType değeri Year ise sadece yıl parametresi etkili olur.
DateTiemGroupingType değeri Month ise sadece yıl ve ay parametresinin etkisi olur.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`AutoFilter`](/cells/python-net/tr/aspose.cells/autofilter)
