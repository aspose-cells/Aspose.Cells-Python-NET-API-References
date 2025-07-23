---
title: BorderCollection класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 70
url: /ru/aspose.cells/bordercollection/
is_root: false
---
##  BorderCollection класс
Инкапсулирует коллекцию из [`Border`](/cells/python-net/ru/aspose.cells/border) объектов.



Тип BorderCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [diagonal_color](/cells/python-net/ru/aspose.cells/bordercollection/diagonal_color) | Получает или задает цвет диагональных линий.|
| [diagonal_style](/cells/python-net/ru/aspose.cells/bordercollection/diagonal_style) | Получает или задает стиль диагональных линий.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`get(self, border_type)`](/cells/python-net/ru/aspose.cells/bordercollection/get/#aspose.cells.bordertype) | Добавьте API for Python через .Net.since this[BorderType borderType] is not supported|
| [`set_color(self, color)`](/cells/python-net/ru/aspose.cells/bordercollection/set_color/#aspose.pydrawing.color) | Задает цвет всех границ в коллекции.|
| [`set_style(self, style)`](/cells/python-net/ru/aspose.cells/bordercollection/set_style/#aspose.cells.cellbordertype) | Задает стиль всех границ коллекции.|



###  Пример

```python
from aspose.cells import BorderType, CellBorderType, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Excel object
workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Accessing the "A1" cell from the worksheet
cell = worksheet.cells.get("A1")
# Adding some value to the "A1" cell
cell.put_value("Visit Aspose!")
style = cell.get_style()
# Setting the line style of the top border
style.borders.get(BorderType.TOP_BORDER).line_style = CellBorderType.THICK
# Setting the color of the top border
style.borders.get(BorderType.TOP_BORDER).color = Color.black
# Setting the line style of the bottom border
style.borders.get(BorderType.BOTTOM_BORDER).line_style = CellBorderType.THICK
# Setting the color of the bottom border
style.borders.get(BorderType.BOTTOM_BORDER).color = Color.black
# Setting the line style of the left border
style.borders.get(BorderType.LEFT_BORDER).line_style = CellBorderType.THICK
# Setting the color of the left border
style.borders.get(BorderType.LEFT_BORDER).color = Color.black
# Setting the line style of the right border
style.borders.get(BorderType.RIGHT_BORDER).line_style = CellBorderType.THICK
# Setting the color of the right border
style.borders.get(BorderType.RIGHT_BORDER).color = Color.black
cell.set_style(style)
# Saving the Excel file
workbook.save("book1.xls")

```

###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`Border`](/cells/python-net/ru/aspose.cells/border)
