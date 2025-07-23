---
title: TextBoxOptions класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 80
url: /ru/aspose.cells.drawing.texts/textboxoptions/
is_root: false
---
##  TextBoxOptions класс
Представляет текстовые параметры формы.



Тип TextBoxOptions предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [shape_text_vertical_alignment](/cells/python-net/ru/aspose.cells.drawing.texts/textboxoptions/shape_text_vertical_alignment) | Соответствует «Формат фигуры — Параметры текста — Текстовое поле — Вертикальное выравнивание» в Excel.|
| [resize_to_fit_text](/cells/python-net/ru/aspose.cells.drawing.texts/textboxoptions/resize_to_fit_text) | Указывает, следует ли изменить размер фигуры, чтобы она соответствовала тексту.|
| [shape_text_direction](/cells/python-net/ru/aspose.cells.drawing.texts/textboxoptions/shape_text_direction) | Возвращает или задает направление отображения текста в заданном текстовом теле.<br/> Соответствует «Формат фигуры — Параметры текста — Текстовое поле — Направление текста» в Excel.|
| [left_margin_pt](/cells/python-net/ru/aspose.cells.drawing.texts/textboxoptions/left_margin_pt) | Получает и задает левое поле в пунктах.|
| [right_margin_pt](/cells/python-net/ru/aspose.cells.drawing.texts/textboxoptions/right_margin_pt) | Получает и задает правое поле в пунктах.|
| [top_margin_pt](/cells/python-net/ru/aspose.cells.drawing.texts/textboxoptions/top_margin_pt) | Получает и задает верхнее поле в пунктах.|
| [bottom_margin_pt](/cells/python-net/ru/aspose.cells.drawing.texts/textboxoptions/bottom_margin_pt) | Возвращает нижнее поле в пунктах.|
| [allow_text_to_overflow](/cells/python-net/ru/aspose.cells.drawing.texts/textboxoptions/allow_text_to_overflow) | Разрешить ли тексту выходить за пределы формы.|
| [wrap_text_in_shape](/cells/python-net/ru/aspose.cells.drawing.texts/textboxoptions/wrap_text_in_shape) | Задает обтекание текста внутри фигуры.<br/> False — перенос текста не производится.<br/>True - Перенос будет произведен по тексту.|



###  Пример

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
index = workbook.worksheets[0].text_boxes.add(0, 0, 350, 350)
shape = workbook.worksheets[0].text_boxes[index]
shape.text = "This is test."
# do your business
# Save the excel file.
workbook.save("exmaple.xlsx")

```

###  Смотрите также
* модуль [`aspose.cells.drawing.texts`](..)
