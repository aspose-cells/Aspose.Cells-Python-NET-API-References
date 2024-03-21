---
title: FormatCondition класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 720
url: /ru/aspose.cells/formatcondition/
is_root: false
---
##  FormatCondition класс
Представляет условие условного форматирования.



Тип FormatCondition предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [formula1](/cells/python-net/ru/aspose.cells/formatcondition/formula1) | Получает и задает значение или выражение, связанное с условным форматированием.|
| [formula2](/cells/python-net/ru/aspose.cells/formatcondition/formula2) | Получает и задает значение или выражение, связанное с условным форматированием.|
| [operator](/cells/python-net/ru/aspose.cells/formatcondition/operator) | Получает и задает тип оператора условного форматирования.|
| [stop_if_true](/cells/python-net/ru/aspose.cells/formatcondition/stop_if_true) | Действительно, никакие правила с более низким приоритетом не могут быть применены к этому правилу, если это правило имеет значение true.<br/> Применяется только для Excel 2007;|
| [priority](/cells/python-net/ru/aspose.cells/formatcondition/priority) | Приоритет этого правила условного форматирования. Это значение используется для определения того, какой<br/>формат должен быть оценен и отображен. Меньшие числовые значения имеют более высокий приоритет, чем<br/> более высокие числовые значения, где «1» — наивысший приоритет.|
| [style](/cells/python-net/ru/aspose.cells/formatcondition/style) | Получает или задает стиль диапазонов ячеек условного форматирования.|
| [type](/cells/python-net/ru/aspose.cells/formatcondition/type) |Получает и задает тип условного формата.|
| [icon_set](/cells/python-net/ru/aspose.cells/formatcondition/icon_set) | Получите экземпляр «IconSet» условного форматирования.<br/>IconSetType экземпляра по умолчанию — TrafficLights31.<br/> Действительно только для типа = IconSet.|
| [data_bar](/cells/python-net/ru/aspose.cells/formatcondition/data_bar) | Получите экземпляр DataBar условного форматирования.<br/>Цвет экземпляра по умолчанию — синий.<br/> Допустимо только для типа DataBar.|
| [color_scale](/cells/python-net/ru/aspose.cells/formatcondition/color_scale) | Получите экземпляр «ColorScale» условного форматирования.<br/>Экземпляром по умолчанию является 3ColorScale «зелено-желто-красный».<br/> Действительно только для типа = ColorScale.|
| [top10](/cells/python-net/ru/aspose.cells/formatcondition/top10) | Получите экземпляр «Top10» условного форматирования.<br/>Правило экземпляра по умолчанию выделяет ячейки,<br/>значения попадают в топ-10.<br/> Действительно только для типа Top10.|
| [above_average](/cells/python-net/ru/aspose.cells/formatcondition/above_average) | Получите экземпляр условного форматирования «AboveAverage».<br/> Правило экземпляра по умолчанию выделяет ячейки, которые<br/>выше среднего для всех значений в диапазоне.<br/>Действительно только для типа = выше среднего.|
| [text](/cells/python-net/ru/aspose.cells/formatcondition/text) | Текстовое значение в правиле условного форматирования «текст содержит».<br/>Допустимо только для типов = containsText, notContainsText, BeginsWith и EndsWith.<br/> Значение по умолчанию — ноль.|
| [time_period](/cells/python-net/ru/aspose.cells/formatcondition/time_period) | Применимый период времени в правиле условного форматирования «дата наступления…».<br/>Действительно только для типа = timePeriod.<br/> Значение по умолчанию — TimePeriodType.Today.|


###  Методы
| Метод| Описание|
| :- | :- |
| [get_formula1](/cells/python-net/ru/aspose.cells/formatcondition/get_formula1/#bool-bool) | Получает значение или выражение, связанное с этим условием форматирования.|
| [get_formula1](/cells/python-net/ru/aspose.cells/formatcondition/get_formula1/#bool-bool-int-int) | Получает значение или выражение условного форматирования ячейки.|
| [get_formula1](/cells/python-net/ru/aspose.cells/formatcondition/get_formula1/#int-int) | Получает формулу условного форматирования ячейки.|
| [get_formula2](/cells/python-net/ru/aspose.cells/formatcondition/get_formula2/#bool-bool) | Получает значение или выражение, связанное с этим условием форматирования.|
| [get_formula2](/cells/python-net/ru/aspose.cells/formatcondition/get_formula2/#bool-bool-int-int) | Получает значение или выражение условного форматирования ячейки.|
| [get_formula2](/cells/python-net/ru/aspose.cells/formatcondition/get_formula2/#int-int) | Получает формулу условного форматирования ячейки.|
| [set_formulas](/cells/python-net/ru/aspose.cells/formatcondition/set_formulas/#str-str-bool-bool) | Устанавливает значение или выражение, связанное с этим условием формата.|
| [set_formula1](/cells/python-net/ru/aspose.cells/formatcondition/set_formula1/#str-bool-bool) | Устанавливает значение или выражение, связанное с этим условием формата.|
| [set_formula2](/cells/python-net/ru/aspose.cells/formatcondition/set_formula2/#str-bool-bool) | Устанавливает значение или выражение, связанное с этим условием формата.|



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
