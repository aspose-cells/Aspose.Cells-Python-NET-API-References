---
title: DataBar класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 390
url: /ru/aspose.cells/databar/
is_root: false
---
##  DataBar класс
 Опишите правило условного форматирования DataBar.
Это правило условного форматирования отображает градуированный
панель данных в диапазоне ячеек.



Тип DataBar предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [axis_color](/cells/python-net/ru/aspose.cells/databar/axis_color) | Получает цвет оси для ячеек с условным форматированием в виде гистограмм.|
| [axis_position](/cells/python-net/ru/aspose.cells/databar/axis_position) | Возвращает или задает положение оси гистограммы, заданное правилом условного форматирования.|
| [bar_fill_type](/cells/python-net/ru/aspose.cells/databar/bar_fill_type) | Возвращает или задает способ заполнения панели данных цветом.|
| [direction](/cells/python-net/ru/aspose.cells/databar/direction) | Возвращает или задает направление отображения панели данных.|
| [bar_border](/cells/python-net/ru/aspose.cells/databar/bar_border) | Получает объект, определяющий границу панели данных.|
| [negative_bar_format](/cells/python-net/ru/aspose.cells/databar/negative_bar_format) | Возвращает объект NegativeBarFormat, связанный с правилом условного форматирования гистограммы.|
| [min_cfvo](/cells/python-net/ru/aspose.cells/databar/min_cfvo) | Получить или задать минимальное значение объекта DataBar.<br/> Невозможно установить значение null или CFValueObject с типом FormatConditionValueType.Max.|
| [max_cfvo](/cells/python-net/ru/aspose.cells/databar/max_cfvo) | Получить или задать максимальное значение объекта DataBar.<br/> Невозможно установить значение null или CFValueObject с типом FormatConditionValueType.Min.|
| [color](/cells/python-net/ru/aspose.cells/databar/color) | Получить или задать цвет этого DataBar.|
| [min_length](/cells/python-net/ru/aspose.cells/databar/min_length) | Представляет минимальную длину полосы данных.|
| [max_length](/cells/python-net/ru/aspose.cells/databar/max_length) | Представляет максимальную длину полосы данных.|
| [show_value](/cells/python-net/ru/aspose.cells/databar/show_value) |Получите или установите флаг, указывающий, следует ли отображать значения ячеек, к которым применяется эта панель данных.<br/> Значение по умолчанию — true.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`to_image(self, cell, img_opts)`](/cells/python-net/ru/aspose.cells/databar/to_image/#aspose.cells.cell-aspose.cells.rendering.imageorprintoptions) | Отобразить строку данных в ячейке в байтовый массив изображения.|



###  Пример

```python
from aspose.cells import CellArea, DataBarAxisPosition, DataBarBorderType, DataBarFillType, DataBarNegativeColorType, FormatConditionType, FormatConditionValueType, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
sheet = workbook.worksheets[0]
# Adds an empty conditional formatting
index = sheet.conditional_formattings.add()
fcs = sheet.conditional_formattings[index]
# Sets the conditional format range.
ca = CellArea()
ca.start_row = 0
ca.end_row = 2
ca.start_column = 0
ca.end_column = 0
fcs.add_area(ca)
# Adds condition.
idx = fcs.add_condition(FormatConditionType.DATA_BAR)
fcs.add_area(ca)
cond = fcs[idx]
# Get Databar
dataBar = cond.data_bar
dataBar.color = Color.orange
# Set Databar properties
dataBar.min_cfvo.type = FormatConditionValueType.PERCENTILE
dataBar.min_cfvo.value = 30
dataBar.show_value = False
dataBar.bar_border.type = DataBarBorderType.SOLID
dataBar.bar_border.color = Color.plum
dataBar.bar_fill_type = DataBarFillType.SOLID
dataBar.axis_color = Color.red
dataBar.axis_position = DataBarAxisPosition.MIDPOINT
dataBar.negative_bar_format.color_type = DataBarNegativeColorType.COLOR
dataBar.negative_bar_format.color = Color.white
dataBar.negative_bar_format.border_color_type = DataBarNegativeColorType.COLOR
dataBar.negative_bar_format.border_color = Color.yellow
# Put Cell Values
cell1 = sheet.cells.get("A1")
cell1.put_value(10)
cell2 = sheet.cells.get("A2")
cell2.put_value(120)
cell3 = sheet.cells.get("A3")
cell3.put_value(260)
# Saving the Excel file
workbook.save("book1.xlsx")

```

###  Смотрите также
* модуль [`aspose.cells`](..)
