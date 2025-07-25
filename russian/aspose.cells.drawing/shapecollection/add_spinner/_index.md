---
title: add_spinner метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 320
url: /ru/aspose.cells.drawing/shapecollection/add_spinner/
is_root: false
---
##  add_spinner(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Добавляет счетчик на рабочий лист.


###  Возврат

Объект Spinner.


```python

def add_spinner(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| upper_left_row | int | Указатель верхнего левого ряда.|
| top | int |Представляет собой вертикальное смещение Spinner от его левой строки в пикселях.|
| upper_left_column | int | Индекс верхнего левого столбца.|
| left | int | Представляет горизонтальное смещение Spinner от его левого столбца в пикселях.|
| height | int | Представляет высоту Spinner в пикселях.|
| width | int | Представляет ширину Spinner в пикселях.|

###  Пример

```python

# add a spinner
spinner = shapes.add_spinner(1, 0, 1, 0, 100, 50)

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`ShapeCollection`](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
