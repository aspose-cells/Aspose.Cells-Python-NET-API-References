---
title: add_spinner метод
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 290
url: /ru/aspose.cells.drawing/shapecollection/add_spinner/
is_root: false
---
##  add_spinner(upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Добавляет счетчик на рабочий лист.


###  Возвращает

Объект Spinner.


```python
def add_spinner(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| upper_left_row | int | Индекс верхней левой строки.|
| top | int |Представляет вертикальное смещение Spinner от его левой строки в единицах пикселя.|
| upper_left_column | int | Индекс левого верхнего столбца.|
| left | int | Представляет горизонтальное смещение Spinner от его левого столбца в единицах пикселя.|
| height | int | Представляет высоту счетчика в пикселях.|
| width | int | Представляет ширину счетчика в пикселях.|

###  Пример

```python

# add a spinner
spinner = shapes.add_spinner(1, 0, 1, 0, 100, 50)

```



###  Смотрите также
* модуль [aspose.cells.drawing](../../)
* класс [ShapeCollection](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
