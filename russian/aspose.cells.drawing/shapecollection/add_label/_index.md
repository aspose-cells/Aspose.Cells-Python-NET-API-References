---
title: add_label метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 150
url: /ru/aspose.cells.drawing/shapecollection/add_label/
is_root: false
---
##  add_label(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Добавляет метку на рабочий лист.


###  Возврат

Объект Label.


```python

def add_label(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| upper_left_row | int | Указатель верхнего левого ряда.|
| top | int |Представляет собой вертикальное смещение метки от ее левой строки в пикселях.|
| upper_left_column | int | Индекс верхнего левого столбца.|
| left | int | Представляет горизонтальное смещение метки от ее левого столбца в пикселях.|
| height | int | Представляет высоту метки в пикселях.|
| width | int | Представляет ширину метки в пикселях.|

###  Пример

```python

# add a label
label = shapes.add_label(1, 0, 1, 0, 100, 50)

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`ShapeCollection`](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
