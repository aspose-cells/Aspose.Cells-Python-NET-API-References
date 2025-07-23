---
title: FormatCondition класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 700
url: /ru/aspose.cells/formatcondition/
is_root: false
---
##  FormatCondition класс
Представляет собой условие условного форматирования.



Тип FormatCondition предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [formula1](/cells/python-net/ru/aspose.cells/formatcondition/formula1) | Возвращает и задает значение или выражение, связанное с условным форматированием.|
| [formula2](/cells/python-net/ru/aspose.cells/formatcondition/formula2) | Возвращает и задает значение или выражение, связанное с условным форматированием.|
| [operator](/cells/python-net/ru/aspose.cells/formatcondition/operator) | Получает и задает тип оператора условного форматирования.|
| [stop_if_true](/cells/python-net/ru/aspose.cells/formatcondition/stop_if_true) |Правда, никакие правила с более низким приоритетом не могут быть применены к данному правилу, если это правило оценивается как истинное.<br/> Применимо только к Excel 2007;|
| [priority](/cells/python-net/ru/aspose.cells/formatcondition/priority) | Приоритет этого правила условного форматирования. Это значение используется для определения того, какое правило<br/>Формат должен быть оценен и преобразован. Меньшие числовые значения имеют более высокий приоритет, чем<br/> более высокие числовые значения, где «1» соответствует наивысшему приоритету.|
| [style](/cells/python-net/ru/aspose.cells/formatcondition/style) | Получает или задает стиль условно отформатированных диапазонов ячеек.|
| [type](/cells/python-net/ru/aspose.cells/formatcondition/type) | Возвращает и задает тип условного формата.|
| [icon_set](/cells/python-net/ru/aspose.cells/formatcondition/icon_set) | Получите экземпляр «IconSet» условного форматирования.<br/>IconSetType экземпляра по умолчанию — TrafficLights31.<br/> Действительно только для типа = IconSet.|
| [data_bar](/cells/python-net/ru/aspose.cells/formatcondition/data_bar) | Получите экземпляр «DataBar» условного форматирования.<br/>Цвет экземпляра по умолчанию — синий.<br/> Действительно только для типа DataBar.|
| [color_scale](/cells/python-net/ru/aspose.cells/formatcondition/color_scale) | Получите экземпляр условного форматирования «ColorScale».<br/>Экземпляр по умолчанию — «зелено-желто-красный» 3ColorScale.<br/> Действительно только для типа = ColorScale.|
| [top10](/cells/python-net/ru/aspose.cells/formatcondition/top10) | Получить экземпляр условного форматирования «Top10».<br/>Правило экземпляра по умолчанию выделяет ячейки,<br/>значения попадают в верхнюю десятку.<br/> Действительно только для типа Top10.|
| [above_average](/cells/python-net/ru/aspose.cells/formatcondition/above_average) |Получите экземпляр условного форматирования «Выше среднего».<br/> Правило экземпляра по умолчанию выделяет ячейки, которые<br/>выше среднего для всех значений в диапазоне.<br/> Действительно только для типа = ВышеСреднего.|
| [text](/cells/python-net/ru/aspose.cells/formatcondition/text) | Текстовое значение в правиле условного форматирования «текст содержит».<br/>Действительно только для type = containsText, notContainsText, beginWith и endsWith.<br/> Значение по умолчанию — ноль.|
| [time_period](/cells/python-net/ru/aspose.cells/formatcondition/time_period) | Применимый период времени в правиле условного форматирования «дата наступления…».<br/>Действительно только для type = timePeriod.<br/> Значение по умолчанию — TimePeriodType.Today.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`get_formula1(self, is_r1c1, is_local)`](/cells/python-net/ru/aspose.cells/formatcondition/get_formula1/#bool-bool) | Возвращает значение или выражение, связанное с этим условием формата.|
| [`get_formula1(self, is_r1c1, is_local, row, column)`](/cells/python-net/ru/aspose.cells/formatcondition/get_formula1/#bool-bool-int-int) | Возвращает значение или выражение условного форматирования ячейки.|
| [`get_formula1(self, row, column)`](/cells/python-net/ru/aspose.cells/formatcondition/get_formula1/#int-int) | Получает формулу условного форматирования ячейки.|
| [`get_formula2(self, is_r1c1, is_local)`](/cells/python-net/ru/aspose.cells/formatcondition/get_formula2/#bool-bool) | Возвращает значение или выражение, связанное с этим условием формата.|
| [`get_formula2(self, is_r1c1, is_local, row, column)`](/cells/python-net/ru/aspose.cells/formatcondition/get_formula2/#bool-bool-int-int) | Возвращает значение или выражение условного форматирования ячейки.|
| [`get_formula2(self, row, column)`](/cells/python-net/ru/aspose.cells/formatcondition/get_formula2/#int-int) | Получает формулу условного форматирования ячейки.|
| [`set_formulas(self, formula1, formula2, is_r1c1, is_local)`](/cells/python-net/ru/aspose.cells/formatcondition/set_formulas/#str-str-bool-bool) | Задает значение или выражение, связанное с этим условием формата.|
| [`set_formula1(self, formula, is_r1c1, is_local)`](/cells/python-net/ru/aspose.cells/formatcondition/set_formula1/#str-bool-bool) | Задает значение или выражение, связанное с этим условием формата.|
| [`set_formula2(self, formula, is_r1c1, is_local)`](/cells/python-net/ru/aspose.cells/formatcondition/set_formula2/#str-bool-bool) | Задает значение или выражение, связанное с этим условием формата.|



###  Пример

```python
from aspose.cells import CellArea, FormatConditionType, OperatorType, Workbook
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
