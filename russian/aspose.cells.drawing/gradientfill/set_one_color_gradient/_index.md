---
title: set_one_color_gradient метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 30
url: /ru/aspose.cells.drawing/gradientfill/set_one_color_gradient/
is_root: false
---
##  set_one_color_gradient(self, color, degree, style, variant) {#aspose.pydrawing.Color-float-aspose.cells.drawing.GradientStyleType-int}
Устанавливает заданную заливку в виде одноцветного градиента.
Применимо только к Excel 2007.



```python

def set_one_color_gradient(self, color, degree, style, variant):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| color | aspose.pydrawing.Color | Один градиентный цвет.|
| degree | float | Степень градиента. Может принимать значения от 0,0 (тёмный) до 1,0 (светлый).|
| style | [`GradientStyleType`](/cells/python-net/ru/aspose.cells.drawing/gradientstyletype) | Стиль градиентной заливки.|
| variant | int | Вариант градиента. Может принимать значения от 1 до 4, соответствующие одному из четырёх вариантов на вкладке «Градиент» диалогового окна «Эффекты заливки». Если стиль — GradientStyle.FromCenter, аргумент Variant может иметь только значение 1 или 2.|



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`GradientFill`](/cells/python-net/ru/aspose.cells.drawing/gradientfill)
