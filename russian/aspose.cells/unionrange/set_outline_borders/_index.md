---
title: set_outline_borders метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 70
url: /ru/aspose.cells/unionrange/set_outline_borders/
is_root: false
---
##  set_outline_borders(self, border_styles, border_colors) {#list-aspose.pydrawing.Color[]}
Устанавливает границы линий вокруг диапазона ячеек.



```python

def set_outline_borders(self, border_styles, border_colors):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| border_styles | list | Стили границ.|
| border_colors | aspose.pydrawing.Color[] | Цвета границ.|
###  Примечания

Длина borderStyles и borderStyles должна быть равна 4.
Порядок borderStyles и borderStyles должен быть следующим: сверху, снизу, слева, справа.

##  set_outline_borders(self, border_style, border_color) {#aspose.cells.CellBorderType-aspose.pydrawing.Color}
Устанавливает границы контура вокруг диапазона ячеек с одинаковым стилем и цветом границ.



```python

def set_outline_borders(self, border_style, border_color):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| border_style | [`CellBorderType`](/cells/python-net/ru/aspose.cells/cellbordertype) | Стиль границы.|
| border_color | aspose.pydrawing.Color | Цвет границы.|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`UnionRange`](/cells/python-net/ru/aspose.cells/unionrange)
