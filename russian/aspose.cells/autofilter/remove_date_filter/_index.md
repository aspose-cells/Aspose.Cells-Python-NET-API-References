---
title: remove_date_filter метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 150
url: /ru/aspose.cells/autofilter/remove_date_filter/
is_root: false
---
##  remove_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second) {#int-aspose.cells.DateTimeGroupingType-int-int-int-int-int-int}
Удаляет фильтр по дате.



```python

def remove_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| field_index | int | Целочисленное смещение поля, на котором вы хотите основать фильтр.<br/> (слева от списка; самое левое поле — поле 0).|
| date_time_grouping_type | [`DateTimeGroupingType`](/cells/python-net/ru/aspose.cells/datetimegroupingtype) | Тип группировки|
| year | int | Год.|
| month | int | Месяц.|
| day | int | День.|
| hour | int | Час.|
| minute | int | Минута.|
| second | int | Второе.|
###  Примечания

Если DateTimeGroupingType равен Year, то действует только параметр year.
Если DateTiemGroupingType — Month, то действуют только параметры year и month.


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`AutoFilter`](/cells/python-net/ru/aspose.cells/autofilter)
