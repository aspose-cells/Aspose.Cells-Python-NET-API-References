---
title: add_arc метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 30
url: /ru/aspose.cells.drawing/shapecollection/add_arc/
is_root: false
---
##  add_arc(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Добавляет ArcShape на рабочий лист.


###  Возврат

Объект ArcShape.


```python

def add_arc(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| upper_left_row | int | Указатель верхнего левого ряда.|
| top | int |Представляет вертикальное смещение ArcShape от его левой строки в пикселях.|
| upper_left_column | int | Индекс верхнего левого столбца.|
| left | int | Представляет горизонтальное смещение ArcShape от его левого столбца в пикселях.|
| height | int | Представляет высоту ArcShape в пикселях.|
| width | int | Представляет ширину ArcShape в пикселях.|

###  Пример

```python

# add a arc
arcShape = shapes.add_arc(1, 0, 1, 0, 100, 50)

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`ShapeCollection`](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
