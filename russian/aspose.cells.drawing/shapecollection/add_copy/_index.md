---
title: add_copy метод
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 90
url: /ru/aspose.cells.drawing/shapecollection/add_copy/
is_root: false
---
##  add_copy(source_shape, upper_left_row, top, upper_left_column, left) {#Shape-int-int-int-int}
Добавляет и копирует фигуру на лист.


###  Возвращает

Новый индекс объекта формы.


```python
def add_copy(self, source_shape, upper_left_row, top, upper_left_column, left):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| source_shape | [Shape](/cells/python-net/ru/aspose.cells.drawing/shape) | Исходная форма.|
| upper_left_row | int | Индекс верхней левой строки.|
| top | int |Представляет вертикальное смещение флажка от его левой строки в единицах пикселя.|
| upper_left_column | int | Индекс левого верхнего столбца.|
| left | int | Представляет горизонтальное смещение текстового поля от его левого столбца в пикселях.|

###  Пример

```python

# add a shape
rectangle = shapes.add_rectangle(2, 0, 2, 0, 130, 130)
# copy
shapes.add_copy(rectangle, 7, 0, 7, 0)

```



###  Смотрите также
* модуль [aspose.cells.drawing](../../)
* класс [ShapeCollection](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
