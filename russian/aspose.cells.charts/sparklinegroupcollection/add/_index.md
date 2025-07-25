---
title: add метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells.charts/sparklinegroupcollection/add/
is_root: false
---
##  add(self, type) {#aspose.cells.charts.SparklineType}
Добавляет в коллекцию [`SparklineGroup`](/cells/python-net/ru/aspose.cells.charts/sparklinegroup) с [`Sparkline`](/cells/python-net/ru/aspose.cells.charts/sparkline).


###  Возврат

Индекс объекта [`SparklineGroup`](/cells/python-net/ru/aspose.cells.charts/sparklinegroup).


```python

def add(self, type):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| type | [`SparklineType`](/cells/python-net/ru/aspose.cells.charts/sparklinetype) | Указывает тип группы Sparkline.|


##  add(self, type, data_range, is_vertical, location_range) {#aspose.cells.charts.SparklineType-str-bool-aspose.cells.CellArea}
Добавляет [`SparklineGroup`](/cells/python-net/ru/aspose.cells.charts/sparklinegroup) с [`Sparkline`](/cells/python-net/ru/aspose.cells.charts/sparkline) в коллекцию.


###  Возврат

Индекс объекта [`SparklineGroup`](/cells/python-net/ru/aspose.cells.charts/sparklinegroup).


```python

def add(self, type, data_range, is_vertical, location_range):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| type | [`SparklineType`](/cells/python-net/ru/aspose.cells.charts/sparklinetype) | Указывает тип группы Sparkline.|
| data_range | str | Задает диапазон данных группы спарклайнов.|
| is_vertical | bool |Указывает, следует ли строить спарклайны из диапазона данных по строкам или по столбцам.|
| location_range | [`CellArea`](/cells/python-net/ru/aspose.cells/cellarea) | Указывает, где будут размещены спарклайны.|



###  Смотрите также
* модуль [`aspose.cells.charts`](../../)
* класс [`Sparkline`](/cells/python-net/ru/aspose.cells.charts/sparkline)
* класс [`SparklineGroup`](/cells/python-net/ru/aspose.cells.charts/sparklinegroup)
* класс [`SparklineGroupCollection`](/cells/python-net/ru/aspose.cells.charts/sparklinegroupcollection)
