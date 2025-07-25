---
title: set_two_color_gradient метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 40
url: /ru/aspose.cells.drawing/lineformat/set_two_color_gradient/
is_root: false
---
##  set_two_color_gradient(self, color1, color2, style, variant) {#aspose.pydrawing.Color-aspose.pydrawing.Color-aspose.cells.drawing.GradientStyleType-int}
Устанавливает указанную заливку в виде двухцветного градиента.
Применимо только к Excel 2007.



```python

def set_two_color_gradient(self, color1, color2, style, variant):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| color1 | aspose.pydrawing.Color | Один градиентный цвет.|
| color2 | aspose.pydrawing.Color | Два градиентных цвета.|
| style | [`GradientStyleType`](/cells/python-net/ru/aspose.cells.drawing/gradientstyletype) | Стиль градиентной заливки.|
| variant | int | Вариант градиента. Может принимать значения от 1 до 4, соответствующие одному из четырёх вариантов на вкладке «Градиент» диалогового окна «Эффекты заливки». Если стиль — GradientStyle.FromCenter, аргумент Variant может иметь только значение 1 или 2.|


##  set_two_color_gradient(self, color1, transparency1, color2, transparency2, style, variant) {#aspose.pydrawing.Color-float-aspose.pydrawing.Color-float-aspose.cells.drawing.GradientStyleType-int}
Устанавливает указанную заливку в виде двухцветного градиента.
Применимо только к Excel 2007.



```python

def set_two_color_gradient(self, color1, transparency1, color2, transparency2, style, variant):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| color1 | aspose.pydrawing.Color | Один градиентный цвет.|
| transparency1 | float | Степень прозрачности цвета1 как значение от 0,0 (непрозрачный) до 1,0 (прозрачный).|
| color2 | aspose.pydrawing.Color | Два градиентных цвета.|
| transparency2 | float | Степень прозрачности цвета2 как значение от 0,0 (непрозрачный) до 1,0 (прозрачный).|
| style | [`GradientStyleType`](/cells/python-net/ru/aspose.cells.drawing/gradientstyletype) | Стиль градиентной заливки.|
| variant | int | Вариант градиента. Может принимать значения от 1 до 4, соответствующие одному из четырёх вариантов на вкладке «Градиент» диалогового окна «Эффекты заливки». Если стиль — GradientStyle.FromCenter, аргумент Variant может иметь только значение 1 или 2.|



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`LineFormat`](/cells/python-net/ru/aspose.cells.drawing/lineformat)
