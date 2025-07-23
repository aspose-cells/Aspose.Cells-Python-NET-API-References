---
title: border_line_color недвижимость
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 350
url: /ru/aspose.cells.drawing/picture/border_line_color/
is_root: false
---
##  border_line_color недвижимость

Представляет цвет границы изображения.

###  Пример

```python
from aspose.cells import Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
worksheet = workbook.worksheets[0]
# Adding a picture at the location of a cell whose row and column indices are 1 in the worksheet. It is "B2" cell
imgIndex = worksheet.pictures.add(1, 1, "example.jpeg")
# Get the inserted picture object
pic = worksheet.pictures[imgIndex]
# Set the border color of the picture
pic.border_line_color = Color.red
# Save the excel file.
workbook.save("result.xlsx")

```
###  Определение:
```python
@property
def border_line_color(self):
    ...
@border_line_color.setter
def border_line_color(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`Picture`](/cells/python-net/ru/aspose.cells.drawing/picture)
