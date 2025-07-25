---
title: add_check_box метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 70
url: /ru/aspose.cells.drawing/shapecollection/add_check_box/
is_root: false
---
##  add_check_box(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Добавляет флажок на рабочий лист.


###  Возврат

Новый индекс объекта CheckBox.


```python

def add_check_box(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| upper_left_row | int | Указатель верхнего левого ряда.|
| top | int | Представляет вертикальное смещение флажка от его верхней строки в пикселях.|
| upper_left_column | int | Индекс верхнего левого столбца.|
| left | int | Представляет горизонтальное смещение текстового поля от его левого столбца в пикселях.|
| height | int | Высота текстового поля в пикселях.|
| width | int | Ширина текстового поля в пикселях.|

###  Пример

```python

# add a CheckBox
checkBox = shapes.add_check_box(1, 0, 1, 0, 100, 50)

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`ShapeCollection`](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
