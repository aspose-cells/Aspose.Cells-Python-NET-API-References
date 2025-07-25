---
title: add_text_effect метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 360
url: /ru/aspose.cells.drawing/shapecollection/add_text_effect/
is_root: false
---
##  add_text_effect(self, effect, text, font_name, size, font_bold, font_italic, upper_left_row, top, upper_left_column, left, height, width) {#aspose.cells.drawing.MsoPresetTextEffect-str-str-int-bool-bool-int-int-int-int-int-int}
Вставляет объект WordArt.


###  Возврат

Возвращает объект Shape, представляющий новый объект WordArt.


```python

def add_text_effect(self, effect, text, font_name, size, font_bold, font_italic, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| effect | [`MsoPresetTextEffect`](/cells/python-net/ru/aspose.cells.drawing/msopresettexteffect) | Тип текстового эффекта предустановленного типа mso.|
| text | str | Текст WordArt.|
| font_name | str | Название шрифта.|
| size | int | Размер шрифта|
| font_bold | bool | Указывает, является ли шрифт жирным.|
| font_italic | bool | Указывает, является ли шрифт курсивом.|
| upper_left_row | int | Указатель верхнего левого ряда.|
| top | int | Представляет собой вертикальное смещение фигуры относительно ее левой строки в пикселях.|
| upper_left_column | int | Индекс верхнего левого столбца.|
| left | int |Представляет горизонтальное смещение фигуры относительно ее левого столбца в пикселях.|
| height | int | Представляет высоту фигуры в пикселях.|
| width | int | Представляет ширину фигуры в пикселях.|

###  Пример

```python
from aspose.cells.drawing import MsoPresetTextEffect

# add a WordArt
wordArt1 = shapes.add_text_effect(MsoPresetTextEffect.TEXT_EFFECT10, "WordArt", "arial", 18, False, False, 3, 0, 3, 0, 200, 50)

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`ShapeCollection`](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
