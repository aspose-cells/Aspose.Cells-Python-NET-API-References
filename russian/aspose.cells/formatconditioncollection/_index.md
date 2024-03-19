---
title: FormatConditionCollection класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 730
url: /ru/aspose.cells/formatconditioncollection/
is_root: false
---
##  FormatConditionCollection класс
Представляет условное форматирование.
FormatConditions может содержать до трех условных форматов.



Тип FormatConditionCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [count](/cells/python-net/ru/aspose.cells/formatconditioncollection/count) | Получает количество условий.|
| [range_count](/cells/python-net/ru/aspose.cells/formatconditioncollection/range_count) | Получает количество условно отформатированных диапазонов.|



Получает условие форматирования по индексу.
###  Индексатор
| Имя| Описание|
| :- | :- |
| [index] |индекс возвращаемого условия форматирования.|


###  Методы
| Метод| Описание|
| :- | :- |
| [add_condition](/cells/python-net/ru/aspose.cells/formatconditioncollection/add_condition/#aspose.cells.FormatConditionType-aspose.cells.OperatorType-str-str) | Добавляет условие форматирования.|
| [add_condition](/cells/python-net/ru/aspose.cells/formatconditioncollection/add_condition/#aspose.cells.FormatConditionType) | Добавьте условие формата.|
| [remove_area](/cells/python-net/ru/aspose.cells/formatconditioncollection/remove_area/#int) | Удаляет диапазон ячеек условного форматирования по индексу.|
| [remove_area](/cells/python-net/ru/aspose.cells/formatconditioncollection/remove_area/#int-int-int-int) | Удалить условное форматирование внутри диапазона.|
| [add](/cells/python-net/ru/aspose.cells/formatconditioncollection/add/#aspose.cells.CellArea-aspose.cells.FormatConditionType-aspose.cells.OperatorType-str-str) | Добавляет условие форматирования и задействованный диапазон ячеек в FormatConditions.<br/>FormatConditions может содержать до трех условных форматов.<br/> В формулах условного форматирования не допускаются ссылки на другие листы.|
| [add_area](/cells/python-net/ru/aspose.cells/formatconditioncollection/add_area/#aspose.cells.CellArea) | Добавляет диапазон ячеек условного форматирования.|
| [get_cell_area](/cells/python-net/ru/aspose.cells/formatconditioncollection/get_cell_area/#int) | Получает диапазон ячеек условного форматирования по индексу.|
| [remove_condition](/cells/python-net/ru/aspose.cells/formatconditioncollection/remove_condition/#int) | Удаляет условие форматирования по индексу.|



###  Пример

```python
from aspose.cells import CellArea, FormatConditionType, OperatorType, Workbook
from aspose.pydrawing import Color

# Create a new Workbook.
workbook = Workbook()
# Get the first worksheet.
sheet = workbook.worksheets[0]
# Adds an empty conditional formatting
index = sheet.conditional_formattings.add()
fcs = sheet.conditional_formattings[index]
# Sets the conditional format range.
ca = CellArea()
ca.start_row = 0
ca.end_row = 0
ca.start_column = 0
ca.end_column = 0
fcs.add_area(ca)
ca = CellArea()
ca.start_row = 1
ca.end_row = 1
ca.start_column = 1
ca.end_column = 1
fcs.add_area(ca)
# Adds condition.
conditionIndex = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "=A2", "100")
# Adds condition.
conditionIndex2 = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "50", "100")
# Sets the background color.
fc = fcs[conditionIndex]
fc.style.background_color = Color.red
# Saving the Excel file
workbook.save("output.xls")

```

###  Смотрите также
* модуль [`aspose.cells`](..)
