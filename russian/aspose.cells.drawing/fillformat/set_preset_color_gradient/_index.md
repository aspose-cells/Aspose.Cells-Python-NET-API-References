---
title: set_preset_color_gradient метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 30
url: /ru/aspose.cells.drawing/fillformat/set_preset_color_gradient/
is_root: false
---
##  set_preset_color_gradient(self, preset_color, style, variant) {#aspose.cells.drawing.GradientPresetType-aspose.cells.drawing.GradientStyleType-int}
Устанавливает заданную заливку в соответствии с предустановленным цветовым градиентом.
Применимо только к Excel 2007.



```python

def set_preset_color_gradient(self, preset_color, style, variant):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| preset_color | [`GradientPresetType`](/cells/python-net/ru/aspose.cells.drawing/gradientpresettype) | Предустановленный тип цвета|
| style | [`GradientStyleType`](/cells/python-net/ru/aspose.cells.drawing/gradientstyletype) | Стиль градиентной заливки.|
| variant | int | Вариант градиента. Может принимать значения от 1 до 4, соответствующие одному из четырёх вариантов на вкладке «Градиент» диалогового окна «Эффекты заливки». Если стиль — GradientStyle.FromCenter, аргумент Variant может иметь только значение 1 или 2.|



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`FillFormat`](/cells/python-net/ru/aspose.cells.drawing/fillformat)
