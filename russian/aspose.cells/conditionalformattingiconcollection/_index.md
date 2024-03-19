---
title: ConditionalFormattingIconCollection класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 330
url: /ru/aspose.cells/conditionalformattingiconcollection/
is_root: false
---
##  ConditionalFormattingIconCollection класс
Представляет коллекцию из [`ConditionalFormattingIcon`](/cells/python-net/ru/aspose.cells/conditionalformattingicon) объектов.



Тип ConditionalFormattingIconCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [capacity](/cells/python-net/ru/aspose.cells/conditionalformattingiconcollection/capacity) | Получает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [add](/cells/python-net/ru/aspose.cells/conditionalformattingiconcollection/add/#aspose.cells.IconSetType-int) | Добавляет объект [`ConditionalFormattingIcon`](/cells/python-net/ru/aspose.cells/conditionalformattingicon).|
| [add](/cells/python-net/ru/aspose.cells/conditionalformattingiconcollection/add/#aspose.cells.ConditionalFormattingIcon) | Добавляет объект [`ConditionalFormattingIcon`](/cells/python-net/ru/aspose.cells/conditionalformattingicon).|
| [copy_to](/cells/python-net/ru/aspose.cells/conditionalformattingiconcollection/copy_to/#list) | Копирует весь список массивов в совместимый список одномерных массивов, начиная с начала списка целевых массивов.|
| [copy_to](/cells/python-net/ru/aspose.cells/conditionalformattingiconcollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массива в совместимый список одномерных массивов, начиная с указанного индекса списка целевого массива.|
| [index_of](/cells/python-net/ru/aspose.cells/conditionalformattingiconcollection/index_of/#aspose.cells.ConditionalFormattingIcon-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов в списке массива, простирающемся от указанного индекса до последнего элемента.|
| [index_of](/cells/python-net/ru/aspose.cells/conditionalformattingiconcollection/index_of/#aspose.cells.ConditionalFormattingIcon-int-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов в списке массивов, который начинается с указанного индекса и содержит указанное количество элементов.|
| [last_index_of](/cells/python-net/ru/aspose.cells/conditionalformattingiconcollection/last_index_of/#aspose.cells.ConditionalFormattingIcon) | Ищет указанный объект и возвращает отсчитываемый от нуля индекс последнего вхождения во всем списке массива.|
| [last_index_of](/cells/python-net/ru/aspose.cells/conditionalformattingiconcollection/last_index_of/#aspose.cells.ConditionalFormattingIcon-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов в списке массива, простирающемся от первого элемента до указанного индекса.|
| [last_index_of](/cells/python-net/ru/aspose.cells/conditionalformattingiconcollection/last_index_of/#aspose.cells.ConditionalFormattingIcon-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов в списке массива, который содержит указанное количество элементов и заканчивается указанным индексом.|
| [binary_search](/cells/python-net/ru/aspose.cells/conditionalformattingiconcollection/binary_search/#aspose.cells.ConditionalFormattingIcon) | Выполняет поиск элемента во всем списке отсортированного массива, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



###  Пример

```python
from aspose.cells import CellArea, FormatConditionType, IconSetType, Workbook

# Instantiating a Workbook object
workbook = Workbook()
sheet = workbook.worksheets[0]
# Get Conditional Formatting
cformattings = sheet.conditional_formattings
# Adds an empty conditional formatting
index = cformattings.add()
# Get newly added Conditional formatting
fcs = cformattings[index]
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
# Sets condition
idx = fcs.add_condition(FormatConditionType.ICON_SET)
cond = fcs[idx]
# Sets condition's type
cond.icon_set.type = IconSetType.ARROWS_GRAY3
# Add custom iconset condition.
cfIcon = cond.icon_set.cf_icons[0]
cfIcon.type = IconSetType.ARROWS3
cfIcon.index = 0
cfIcon1 = cond.icon_set.cf_icons[1]
cfIcon1.type = IconSetType.ARROWS_GRAY3
cfIcon1.index = 1
cfIcon2 = cond.icon_set.cf_icons[2]
cfIcon2.type = IconSetType.BOXES5
cfIcon2.index = 2
# Saving the Excel file
workbook.save("output.xls")

```

###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`ConditionalFormattingIcon`](/cells/python-net/ru/aspose.cells/conditionalformattingicon)
