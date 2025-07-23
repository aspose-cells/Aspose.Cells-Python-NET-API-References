---
title: add_oval метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 220
url: /ru/aspose.cells.drawing/shapecollection/add_oval/
is_root: false
---
##  add_oval(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Добавляет овал на рабочий лист.


###  Возврат

Овальный объект.


```python

def add_oval(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| upper_left_row | int | Указатель верхнего левого ряда.|
| top | int | Представляет собой вертикальное смещение овала от его левой строки в пикселях.|
| upper_left_column | int | Индекс верхнего левого столбца.|
| left | int | Представляет горизонтальное смещение овала от его левого столбца в пикселях.|
| height | int | Представляет высоту овала в пикселях.|
| width | int | Представляет ширину овала в пикселях.|

###  Пример

```python

# add a oval
oval = shapes.add_oval(1, 0, 1, 0, 50, 50)

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`ShapeCollection`](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
