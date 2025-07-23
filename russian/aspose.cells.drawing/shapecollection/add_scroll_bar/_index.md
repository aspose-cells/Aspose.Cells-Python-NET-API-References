---
title: add_scroll_bar метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 270
url: /ru/aspose.cells.drawing/shapecollection/add_scroll_bar/
is_root: false
---
##  add_scroll_bar(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Добавляет полосу прокрутки на рабочий лист.


###  Возврат

Объект ScrollBar.


```python

def add_scroll_bar(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| upper_left_row | int | Указатель верхнего левого ряда.|
| top | int |Представляет вертикальное смещение ScrollBar от его левой строки в пикселях.|
| upper_left_column | int | Индекс верхнего левого столбца.|
| left | int | Представляет горизонтальное смещение ScrollBar от его левого столбца в пикселях.|
| height | int | Представляет высоту ScrollBar в пикселях.|
| width | int | Представляет ширину полосы прокрутки в пикселях.|

###  Пример

```python

# add a scroll bar
scrollBar = shapes.add_scroll_bar(1, 0, 1, 0, 100, 20)

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`ShapeCollection`](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
