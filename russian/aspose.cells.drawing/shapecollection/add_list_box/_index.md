---
title: add_list_box метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 190
url: /ru/aspose.cells.drawing/shapecollection/add_list_box/
is_root: false
---
##  add_list_box(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Добавляет ListBox на рабочий лист.


###  Возврат

Объект ListBox.


```python

def add_list_box(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| upper_left_row | int | Указатель верхнего левого ряда.|
| top | int | Представляет вертикальное смещение ListBox от его левой строки в пикселях.|
| upper_left_column | int | Индекс верхнего левого столбца.|
| left | int | Представляет горизонтальное смещение ListBox от его левого столбца в пикселях.|
| height | int | Представляет высоту ListBox в пикселях.|
| width | int | Представляет ширину ListBox в пикселях.|

###  Пример

```python

# add a list box
listBox = shapes.add_list_box(1, 0, 1, 0, 100, 50)

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`ShapeCollection`](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
