---
title: add_button метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 60
url: /ru/aspose.cells.drawing/shapecollection/add_button/
is_root: false
---
##  add_button(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Добавляет кнопку на рабочий лист.


###  Возврат

Объект Button.


```python

def add_button(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| upper_left_row | int | Указатель верхнего левого ряда.|
| top | int | Представляет вертикальное смещение кнопки от ее левой строки в пикселях.|
| upper_left_column | int | Индекс верхнего левого столбца.|
| left | int |Представляет горизонтальное смещение кнопки от ее левого столбца в пикселях.|
| height | int | Представляет высоту кнопки в пикселях.|
| width | int | Представляет ширину кнопки в пикселях.|

###  Пример

```python

# add a button
button = shapes.add_button(1, 0, 1, 0, 100, 50)

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`ShapeCollection`](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
