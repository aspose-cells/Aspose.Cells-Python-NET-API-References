---
title: FindOptions класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 660
url: /ru/aspose.cells/findoptions/
is_root: false
---
##  FindOptions класс
Представляет параметры поиска.



Тип FindOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [__init__](/cells/python-net/ru/aspose.cells/findoptions/__init__/#) |Создает новый экземпляр FindOptions.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [is_case_sensitive](/cells/python-net/ru/aspose.cells/findoptions/is_case_sensitive) | Указывает, чувствительна ли искомая строка к регистру.|
| [case_sensitive](/cells/python-net/ru/aspose.cells/findoptions/case_sensitive) | Указывает, чувствительна ли искомая строка к регистру.|
| [look_at_type](/cells/python-net/ru/aspose.cells/findoptions/look_at_type) | Посмотрите на тип.|
| [is_range_set](/cells/python-net/ru/aspose.cells/findoptions/is_range_set) | Указывает, установлен ли диапазон поиска.|
| [search_next](/cells/python-net/ru/aspose.cells/findoptions/search_next) | Порядок поиска. Верно: искать дальше. Ложь: поиск предыдущего.|
| [search_backward](/cells/python-net/ru/aspose.cells/findoptions/search_backward) | Будет ли выполняться поиск ячеек в обратном направлении.|
| [seach_order_by_rows](/cells/python-net/ru/aspose.cells/findoptions/seach_order_by_rows) | Указывает, порядок поиска — по строкам или по столбцам.|
| [look_in_type](/cells/python-net/ru/aspose.cells/findoptions/look_in_type) | Посмотрите в типе.|
| [regex_key](/cells/python-net/ru/aspose.cells/findoptions/regex_key) | Указывает, является ли искомый ключ регулярным выражением.<br/> Если это правда, искомый ключ будет принят как регулярное выражение и проанализирован. В противном случае ключ будет разобран по правилам MS Excel.|
| [value_type_sensitive](/cells/python-net/ru/aspose.cells/findoptions/value_type_sensitive) | Указывает, должен ли тип значения искомой ячейки совпадать с искомым ключом.|
| [style](/cells/python-net/ru/aspose.cells/findoptions/style) | Формат для поиска.|
| [convert_numeric_data](/cells/python-net/ru/aspose.cells/findoptions/convert_numeric_data) | Получает или задает значение, указывающее, нужно ли преобразовывать искомое строковое значение в числовые данные.|


###  Методы
| Метод| Описание|
| :- | :- |
| [get_range](/cells/python-net/ru/aspose.cells/findoptions/get_range/#) | Получает и задает диапазон поиска.|
| [set_range](/cells/python-net/ru/aspose.cells/findoptions/set_range/#aspose.cells.CellArea) | Устанавливает диапазон поиска.|



###  Пример

```python
from aspose.cells import CellArea, FindOptions, LookInType, Workbook

# Instantiate the workbook object
workbook = Workbook("book1.xls")
# Get Cells collection
cells = workbook.worksheets[0].cells
# Instantiate FindOptions Object
findOptions = FindOptions()
# Create a Cells Area
ca = CellArea()
ca.start_row = 8
ca.start_column = 2
ca.end_row = 17
ca.end_column = 13
# Set cells area for find options
findOptions.set_range(ca)
# Set searching properties
findOptions.search_backward = False
findOptions.seach_order_by_rows = True
findOptions.look_in_type = LookInType.VALUES
# Find the cell with 0 value
cell = cells.find(0, None, findOptions)

```

###  Смотрите также
* модуль [`aspose.cells`](..)
