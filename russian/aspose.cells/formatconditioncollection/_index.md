---
title: FormatConditionCollection класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 710
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
| [index] | индекс условия форматирования, которое необходимо вернуть.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`add_condition(self, type, operator_type, formula1, formula2)`](/cells/python-net/ru/aspose.cells/formatconditioncollection/add_condition/#aspose.cells.formatconditiontype-aspose.cells.operatortype-str-str) | Добавляет условие форматирования.|
| [`add_condition(self, type)`](/cells/python-net/ru/aspose.cells/formatconditioncollection/add_condition/#aspose.cells.formatconditiontype) | Добавьте условие форматирования.|
| [`remove_area(self, index)`](/cells/python-net/ru/aspose.cells/formatconditioncollection/remove_area/#int) | Удаляет условно отформатированный диапазон ячеек по индексу.|
| [`remove_area(self, start_row, start_column, total_rows, total_columns)`](/cells/python-net/ru/aspose.cells/formatconditioncollection/remove_area/#int-int-int-int) | Удалить условное форматирование в диапазоне.|
| [`add(self, cell_area, type, operator_type, formula1, formula2)`](/cells/python-net/ru/aspose.cells/formatconditioncollection/add/#aspose.cells.cellarea-aspose.cells.formatconditiontype-aspose.cells.operatortype-str-str) |Добавляет условие форматирования и диапазон ячеек, на которые оно распространяется, в FormatConditions.<br/>FormatConditions может содержать до трех условных форматов.<br/> В формулах условного форматирования не допускаются ссылки на другие листы.|
| [`add_area(self, cell_area)`](/cells/python-net/ru/aspose.cells/formatconditioncollection/add_area/#aspose.cells.cellarea) | Добавляет диапазон ячеек с условным форматированием.|
| [`get_cell_area(self, index)`](/cells/python-net/ru/aspose.cells/formatconditioncollection/get_cell_area/#int) | Получает условно отформатированный диапазон ячеек по индексу.|
| [`remove_condition(self, index)`](/cells/python-net/ru/aspose.cells/formatconditioncollection/remove_condition/#int) | Удаляет условие форматирования по индексу.|



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
