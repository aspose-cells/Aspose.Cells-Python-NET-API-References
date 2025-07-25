---
title: Border класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 60
url: /ru/aspose.cells/border/
is_root: false
---
##  Border класс
Инкапсулирует объект, представляющий границу ячейки.



Тип Border предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [theme_color](/cells/python-net/ru/aspose.cells/border/theme_color) | Получает и задает цвет темы границы.|
| [color](/cells/python-net/ru/aspose.cells/border/color) | Получает или задает цвет границы.|
| [argb_color](/cells/python-net/ru/aspose.cells/border/argb_color) | Получает и задает цвет с помощью 32-битного значения ARGB.|
| [line_style](/cells/python-net/ru/aspose.cells/border/line_style) | Получает или задает тип границы ячейки.|



###  Пример

```python
from aspose.cells import BorderType, CellBorderType, Workbook
from aspose.pydrawing import Color

workbook = Workbook()
sheets = workbook.worksheets
cell = sheets[0].cells.get("A1")
style = cell.get_style()
# Set top border style and color
border = style.borders.get(BorderType.TOP_BORDER)
border.line_style = CellBorderType.MEDIUM
border.color = Color.red
cell.set_style(style)

```

###  Смотрите также
* модуль [`aspose.cells`](..)
