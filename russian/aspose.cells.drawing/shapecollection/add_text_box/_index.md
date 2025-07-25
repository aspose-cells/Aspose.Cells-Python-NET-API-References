---
title: add_text_box метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 340
url: /ru/aspose.cells.drawing/shapecollection/add_text_box/
is_root: false
---
##  add_text_box(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Добавляет текстовое поле на рабочий лист.


###  Возврат

Объект [`TextBox`](/cells/python-net/ru/aspose.cells.drawing/textbox).


```python

def add_text_box(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| upper_left_row | int | Указатель верхнего левого ряда.|
| top | int | Представляет вертикальное смещение текстового поля от его верхней строки в пикселях.|
| upper_left_column | int | Индекс верхнего левого столбца.|
| left | int | Представляет горизонтальное смещение текстового поля от его левого столбца в пикселях.|
| height | int | Представляет высоту текстового поля в пикселях.|
| width | int | Представляет ширину текстового поля в пикселях.|

###  Пример

```python

# add a TextBox
textBox = shapes.add_text_box(1, 0, 1, 0, 100, 50)

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`ShapeCollection`](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
* класс [`TextBox`](/cells/python-net/ru/aspose.cells.drawing/textbox)
