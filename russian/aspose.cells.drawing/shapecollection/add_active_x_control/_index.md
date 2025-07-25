---
title: add_active_x_control метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells.drawing/shapecollection/add_active_x_control/
is_root: false
---
##  add_active_x_control(self, type, top_row, top, left_column, left, width, height) {#aspose.cells.drawing.activexcontrols.ControlType-int-int-int-int-int-int}
Создает элемент управления ActiveX.


###  Возврат




```python

def add_active_x_control(self, type, top_row, top, left_column, left, width, height):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| type | aspose.cells.drawing.activexcontrols.ControlType | Тип управления.|
| top_row | int | Указатель верхнего левого ряда.|
| top | int | Представляет вертикальное смещение фигуры от ее левой строки в пикселях.|
| left_column | int | Индекс верхнего левого столбца.|
| left | int | Представляет горизонтальное смещение фигуры от ее левого столбца в пикселях.|
| width | int | Представляет ширину фигуры в пикселях.|
| height | int | Представляет высоту фигуры в пикселях.|

###  Пример

```python
from aspose.cells.drawing.activexcontrols import ControlType

# add an ActiveX control
activeXControl = shapes.add_active_x_control(ControlType.CHECK_BOX, 1, 0, 1, 0, 100, 50)

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`ShapeCollection`](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
