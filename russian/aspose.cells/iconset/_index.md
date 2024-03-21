---
title: IconSet класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 940
url: /ru/aspose.cells/iconset/
is_root: false
---
##  IconSet класс
 Опишите правило условного форматирования IconSet.
Это правило условного форматирования применяет значки к ячейкам.
согласно их ценностям.



Тип IconSet предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [cf_icons](/cells/python-net/ru/aspose.cells/iconset/cf_icons) | Получите [`ConditionalFormattingIcon`](/cells/python-net/ru/aspose.cells/conditionalformattingicon) из коллекции.|
| [cfvos](/cells/python-net/ru/aspose.cells/iconset/cfvos) | Получите экземпляр CFValueObjects.|
| [type](/cells/python-net/ru/aspose.cells/iconset/type) | Получите или установите тип набора значков для отображения.<br/>Установка типа автоматически проверит, соответствует ли текущий счетчик Cfvos.<br/> соответствовать новому типу. В противном случае старый Cfvos будет очищен и<br/> Cfvo по умолчанию будет добавлен.|
| [is_custom](/cells/python-net/ru/aspose.cells/iconset/is_custom) | Указывает, является ли набор значков пользовательским.<br/> Значение по умолчанию — ложь.|
| [show_value](/cells/python-net/ru/aspose.cells/iconset/show_value) | Получите или установите флаг, указывающий, следует ли отображать значения ячеек, к которым применяется этот набор значков.<br/> Значение по умолчанию — правда.|
| [reverse](/cells/python-net/ru/aspose.cells/iconset/reverse) | Получите или установите флаг, указывающий, следует ли изменить порядок значков по умолчанию в этом наборе значков.<br/> Значение по умолчанию — ложь.|



###  Пример

```python
from aspose.cells import CellArea, FormatConditionType, IconSetType, Workbook

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
idx = fcs.add_condition(FormatConditionType.ICON_SET)
fcs.add_area(ca)
cond = fcs[idx]
# Get Icon Set
iconSet = cond.icon_set
# Set Icon Type
iconSet.type = IconSetType.ARROWS3
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
* класс [`ConditionalFormattingIcon`](/cells/python-net/ru/aspose.cells/conditionalformattingicon)
