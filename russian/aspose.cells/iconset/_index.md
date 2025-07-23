---
title: IconSet класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 850
url: /ru/aspose.cells/iconset/
is_root: false
---
##  IconSet класс
 Опишите правило условного форматирования IconSet.
Это правило условного форматирования применяет значки к ячейкам.
в соответствии со своими ценностями.



Тип IconSet предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [cf_icons](/cells/python-net/ru/aspose.cells/iconset/cf_icons) | Получите [`ConditionalFormattingIcon`](/cells/python-net/ru/aspose.cells/conditionalformattingicon) из коллекции|
| [cfvos](/cells/python-net/ru/aspose.cells/iconset/cfvos) | Получите экземпляр CFValueObjects.|
| [type](/cells/python-net/ru/aspose.cells/iconset/type) | Получить или установить тип набора значков для отображения.<br/>При выборе типа будет выполнена автоматическая проверка текущего количества Cfvos.<br/> Соответствует новому типу. Если не соответствует, старые Cfvos будут очищены и<br/> Будут добавлены Cfvos по умолчанию.|
| [is_custom](/cells/python-net/ru/aspose.cells/iconset/is_custom) | Указывает, является ли набор значков пользовательским.<br/> Значение по умолчанию — false.|
| [show_value](/cells/python-net/ru/aspose.cells/iconset/show_value) | Получите или установите флаг, указывающий, следует ли отображать значения ячеек, к которым применен этот набор значков.<br/> Значение по умолчанию — true.|
| [reverse](/cells/python-net/ru/aspose.cells/iconset/reverse) |Получите или задайте флаг, указывающий, следует ли изменить порядок значков по умолчанию в этом наборе значков на обратный.<br/> Значение по умолчанию — false.|



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
