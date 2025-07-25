---
title: add_word_art метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 380
url: /ru/aspose.cells.drawing/shapecollection/add_word_art/
is_root: false
---
##  add_word_art(self, style, text, upper_left_row, top, upper_left_column, left, height, width) {#aspose.cells.drawing.PresetWordArtStyle-str-int-int-int-int-int-int}
Добавляет предустановленные элементы WordArt, начиная с Excel 2007.


###  Возврат




```python

def add_word_art(self, style, text, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| style | [`PresetWordArtStyle`](/cells/python-net/ru/aspose.cells.drawing/presetwordartstyle) | Предустановленный стиль WordArt.|
| text | str | Текст.|
| upper_left_row | int | Указатель верхнего левого ряда.|
| top | int | Представляет собой вертикальное смещение фигуры относительно ее левой строки в пикселях.|
| upper_left_column | int | Индекс верхнего левого столбца.|
| left | int |Представляет горизонтальное смещение фигуры относительно ее левого столбца в пикселях.|
| height | int | Представляет высоту фигуры в пикселях.|
| width | int | Представляет ширину фигуры в пикселях.|

###  Пример

```python
from aspose.cells.drawing import PresetWordArtStyle

# add a WordArt
wordArt2 = shapes.add_word_art(PresetWordArtStyle.WORD_ART_STYLE1, "WordArt", 3, 0, 3, 0, 50, 200)

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`ShapeCollection`](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
