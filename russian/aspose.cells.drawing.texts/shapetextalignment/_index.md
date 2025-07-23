---
title: ShapeTextAlignment класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 70
url: /ru/aspose.cells.drawing.texts/shapetextalignment/
is_root: false
---
##  ShapeTextAlignment класс
Представляет собой настройку выравнивания текста фигуры;



Тип ShapeTextAlignment предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [is_text_wrapped](/cells/python-net/ru/aspose.cells.drawing.texts/shapetextalignment/is_text_wrapped) | Возвращает или задает тип обтекания текстом фигуры, содержащей текст.|
| [rotate_text_with_shape](/cells/python-net/ru/aspose.cells.drawing.texts/shapetextalignment/rotate_text_with_shape) | Указывает, вращается ли текст вместе с формой.|
| [text_vertical_overflow](/cells/python-net/ru/aspose.cells.drawing.texts/shapetextalignment/text_vertical_overflow) | Получает и задает тип вертикального переполнения текста текстового поля.|
| [text_horizontal_overflow](/cells/python-net/ru/aspose.cells.drawing.texts/shapetextalignment/text_horizontal_overflow) | Получает и задает тип горизонтального переполнения текста текстового поля.|
| [rotation_angle](/cells/python-net/ru/aspose.cells.drawing.texts/shapetextalignment/rotation_angle) | Получает и задает поворот фигуры.|
| [text_vertical_type](/cells/python-net/ru/aspose.cells.drawing.texts/shapetextalignment/text_vertical_type) | Получает и задает направление текста.|
| [is_locked_text](/cells/python-net/ru/aspose.cells.drawing.texts/shapetextalignment/is_locked_text) | Указывает, заблокирована ли форма, если рабочий лист защищен.|
| [auto_size](/cells/python-net/ru/aspose.cells.drawing.texts/shapetextalignment/auto_size) | Указывает, регулируется ли размер фигуры автоматически в соответствии с ее содержимым.|
| [text_shape_type](/cells/python-net/ru/aspose.cells.drawing.texts/shapetextalignment/text_shape_type) | Получает и задает тип преобразования текста.|
| [top_margin_pt](/cells/python-net/ru/aspose.cells.drawing.texts/shapetextalignment/top_margin_pt) | Возвращает верхнее поле в пунктах.|
| [bottom_margin_pt](/cells/python-net/ru/aspose.cells.drawing.texts/shapetextalignment/bottom_margin_pt) | Возвращает нижнее поле в пунктах.|
| [left_margin_pt](/cells/python-net/ru/aspose.cells.drawing.texts/shapetextalignment/left_margin_pt) | Возвращает левое поле в пунктах.|
| [right_margin_pt](/cells/python-net/ru/aspose.cells.drawing.texts/shapetextalignment/right_margin_pt) | Возвращает правое поле в пунктах.|
| [is_auto_margin](/cells/python-net/ru/aspose.cells.drawing.texts/shapetextalignment/is_auto_margin) |Указывает, являются ли поля текстовой рамки автоматическими.|
| [number_of_columns](/cells/python-net/ru/aspose.cells.drawing.texts/shapetextalignment/number_of_columns) | Возвращает и задает количество столбцов текста в ограничивающем прямоугольнике.|



###  Пример

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
shape = workbook.worksheets[0].shapes.add_rectangle(1, 0, 1, 0, 50, 100)
shapeTextAlignment = shape.text_body.text_alignment

```

###  Смотрите также
* модуль [`aspose.cells.drawing.texts`](..)
