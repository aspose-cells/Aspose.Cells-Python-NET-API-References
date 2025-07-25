---
title: PivotTableCollection класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 250
url: /ru/aspose.cells.pivot/pivottablecollection/
is_root: false
---
##  PivotTableCollection класс
Представляет коллекцию всех объектов сводной таблицы на указанном листе.



Тип PivotTableCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [capacity](/cells/python-net/ru/aspose.cells.pivot/pivottablecollection/capacity) | Возвращает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`add(self, source_data, dest_cell_name, table_name)`](/cells/python-net/ru/aspose.cells.pivot/pivottablecollection/add/#str-str-str) | Добавляет новую сводную таблицу.|
| [`add(self, source_data, dest_cell_name, table_name, use_same_source)`](/cells/python-net/ru/aspose.cells.pivot/pivottablecollection/add/#str-str-str-bool) | Добавляет новую сводную таблицу.|
| [`add(self, source_data, row, column, table_name)`](/cells/python-net/ru/aspose.cells.pivot/pivottablecollection/add/#str-int-int-str) | Добавляет новую сводную таблицу.|
| [`add(self, source_data, row, column, table_name, use_same_source)`](/cells/python-net/ru/aspose.cells.pivot/pivottablecollection/add/#str-int-int-str-bool) | Добавляет новую сводную таблицу.|
| [`add(self, source_data, row, column, table_name, use_same_source, is_xls_classic)`](/cells/python-net/ru/aspose.cells.pivot/pivottablecollection/add/#str-int-int-str-bool-bool) | Добавляет новую сводную таблицу.|
| [`add(self, source_data, cell, table_name, use_same_source, is_xls_classic)`](/cells/python-net/ru/aspose.cells.pivot/pivottablecollection/add/#str-str-str-bool-bool) | Добавляет новую сводную таблицу.|
| [`add(self, pivot_table, dest_cell_name, table_name)`](/cells/python-net/ru/aspose.cells.pivot/pivottablecollection/add/#aspose.cells.pivot.pivottable-str-str) | Добавляет новую сводную таблицу на основе другой сводной таблицы.|
| [`add(self, pivot_table, row, column, table_name)`](/cells/python-net/ru/aspose.cells.pivot/pivottablecollection/add/#aspose.cells.pivot.pivottable-int-int-str) | Добавляет новую сводную таблицу на основе другой сводной таблицы.|
| [`add(self, source_data, is_auto_page, page_fields, dest_cell_name, table_name)`](/cells/python-net/ru/aspose.cells.pivot/pivottablecollection/add/#list-bool-aspose.cells.pivot.pivotpagefields-str-str) | Добавляет новый объект сводной таблицы в коллекцию с несколькими диапазонами консолидации в качестве источника данных.|
| [`add(self, source_data, is_auto_page, page_fields, row, column, table_name)`](/cells/python-net/ru/aspose.cells.pivot/pivottablecollection/add/#list-bool-aspose.cells.pivot.pivotpagefields-int-int-str) | Добавляет новый объект сводной таблицы в коллекцию с несколькими диапазонами консолидации в качестве источника данных.|
| [`copy_to(self, array)`](/cells/python-net/ru/aspose.cells.pivot/pivottablecollection/copy_to/#list) |Копирует весь список массивов в совместимый одномерный список массивов, начиная с начала целевого списка массивов.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ru/aspose.cells.pivot/pivottablecollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массивов в совместимый список одномерных массивов, начиная с указанного индекса целевого списка массивов.|
| [`index_of(self, item, index)`](/cells/python-net/ru/aspose.cells.pivot/pivottablecollection/index_of/#aspose.cells.pivot.pivottable-int) | Выполняет поиск указанного объекта и возвращает индекс (начиная с нуля) первого вхождения в диапазоне элементов списка массива, который простирается от указанного индекса до последнего элемента.|
| [`index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells.pivot/pivottablecollection/index_of/#aspose.cells.pivot.pivottable-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов списка массива, который начинается с указанного индекса и содержит указанное количество элементов.|
| [`last_index_of(self, item)`](/cells/python-net/ru/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.pivottable) | Выполняет поиск указанного объекта и возвращает нулевой индекс последнего вхождения во всем списке массива.|
| [`last_index_of(self, item, index)`](/cells/python-net/ru/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.pivottable-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который простирается от первого элемента до указанного индекса.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.pivottable-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который содержит указанное количество элементов и заканчивается на указанном индексе.|
| [`get(self, name)`](/cells/python-net/ru/aspose.cells.pivot/pivottablecollection/get/#str) | Получает отчет сводной таблицы по имени сводной таблицы.|
| [`remove_pivot_table(self, pivot_table)`](/cells/python-net/ru/aspose.cells.pivot/pivottablecollection/remove_pivot_table/#aspose.cells.pivot.pivottable) | Удаляет указанную сводную таблицу и удаляет ее данные.|
| [`remove_pivot_table_data(self, pivot_table, keep_data)`](/cells/python-net/ru/aspose.cells.pivot/pivottablecollection/remove_pivot_table_data/#aspose.cells.pivot.pivottable-bool) | Удаляет указанную сводную таблицу|
| [`remove_by_index(self, index)`](/cells/python-net/ru/aspose.cells.pivot/pivottablecollection/remove_by_index/#int) | Удаляет сводную таблицу по указанному индексу и удаляет данные сводной таблицы.|
| [`remove_at(self, index, keep_data)`](/cells/python-net/ru/aspose.cells.pivot/pivottablecollection/remove_at/#int-bool) | Удаляет сводную таблицу по указанному индексу.|
| [`binary_search(self, item)`](/cells/python-net/ru/aspose.cells.pivot/pivottablecollection/binary_search/#aspose.cells.pivot.pivottable) | Выполняет поиск элемента во всем отсортированном списке массивов, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



###  Пример

```python
from aspose.cells import FormatConditionType, OperatorType, Workbook
from aspose.cells.pivot import PivotFieldType, PivotFilterType, PivotTableStyleType
from aspose.pydrawing import Color

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
cells.get(5, 0).value = "grape"
cells.get(6, 0).value = "blueberry"
cells.get(7, 0).value = "kiwi"
cells.get(8, 0).value = "cherry"
cells.get(0, 1).value = "year"
cells.get(1, 1).value = 2020
cells.get(2, 1).value = 2020
cells.get(3, 1).value = 2020
cells.get(4, 1).value = 2020
cells.get(5, 1).value = 2021
cells.get(6, 1).value = 2021
cells.get(7, 1).value = 2021
cells.get(8, 1).value = 2021
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
cells.get(5, 2).value = 90
cells.get(6, 2).value = 100
cells.get(7, 2).value = 110
cells.get(8, 2).value = 120
pivots = sheet.pivot_tables
pivotIndex = pivots.add("=Sheet1!A1:C9", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "year")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
# Change PivotField's attributes
rowField = pivot.row_fields[0]
rowField.display_name = "custom display name"
# Add PivotFilter
index = pivot.pivot_filters.add(0, PivotFilterType.COUNT)
filter = pivot.pivot_filters[index]
filter.auto_filter.filter_top10(0, False, False, 2)
# Add PivotFormatCondition
formatIndex = pivot.pivot_format_conditions.add()
pfc = pivot.pivot_format_conditions[formatIndex]
fcc = pfc.format_conditions
fcc.add_area(pivot.data_body_range)
idx = fcc.add_condition(FormatConditionType.CELL_VALUE)
fc = fcc[idx]
fc.formula1 = "100"
fc.operator = OperatorType.GREATER_OR_EQUAL
fc.style.background_color = Color.red
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

###  Смотрите также
* модуль [`aspose.cells.pivot`](..)
