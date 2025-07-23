---
title: SlicerCollection класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 50
url: /ru/aspose.cells.slicers/slicercollection/
is_root: false
---
##  SlicerCollection класс
Задает коллекцию всех объектов среза на указанном рабочем листе.



Тип SlicerCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [capacity](/cells/python-net/ru/aspose.cells.slicers/slicercollection/capacity) | Возвращает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`add(self, pivot, dest_cell_name, base_field_name)`](/cells/python-net/ru/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-str-str) | Добавить новый срез, используя сводную таблицу в качестве источника данных|
| [`add(self, pivot, row, column, base_field_name)`](/cells/python-net/ru/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-int-int-str) | Добавить новый срез, используя сводную таблицу в качестве источника данных|
| [`add(self, pivot, row, column, base_field_index)`](/cells/python-net/ru/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-int-int-int) | Добавить новый срез, используя сводную таблицу в качестве источника данных|
| [`add(self, pivot, dest_cell_name, base_field_index)`](/cells/python-net/ru/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-str-int) | Добавить новый срез, используя сводную таблицу в качестве источника данных|
| [`add(self, pivot, row, column, base_field)`](/cells/python-net/ru/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-int-int-aspose.cells.pivot.pivotfield) | Добавить новый срез, используя сводную таблицу в качестве источника данных|
| [`add(self, pivot, dest_cell_name, base_field)`](/cells/python-net/ru/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-str-aspose.cells.pivot.pivotfield) | Добавить новый срез, используя сводную таблицу в качестве источника данных|
| [`add(self, table, index, dest_cell_name)`](/cells/python-net/ru/aspose.cells.slicers/slicercollection/add/#aspose.cells.tables.listobject-int-str) | Добавить новый слайсер, используя ListObjet в качестве источника данных|
| [`add(self, table, list_column, dest_cell_name)`](/cells/python-net/ru/aspose.cells.slicers/slicercollection/add/#aspose.cells.tables.listobject-aspose.cells.tables.listcolumn-str) | Добавить новый слайсер, используя ListObjet в качестве источника данных|
| [`add(self, table, list_column, row, column)`](/cells/python-net/ru/aspose.cells.slicers/slicercollection/add/#aspose.cells.tables.listobject-aspose.cells.tables.listcolumn-int-int) | Добавить новый слайсер, используя ListObjet в качестве источника данных|
| [`copy_to(self, array)`](/cells/python-net/ru/aspose.cells.slicers/slicercollection/copy_to/#list) |Копирует весь список массивов в совместимый одномерный список массивов, начиная с начала целевого списка массивов.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ru/aspose.cells.slicers/slicercollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массивов в совместимый список одномерных массивов, начиная с указанного индекса целевого списка массивов.|
| [`index_of(self, item, index)`](/cells/python-net/ru/aspose.cells.slicers/slicercollection/index_of/#aspose.cells.slicers.slicer-int) | Выполняет поиск указанного объекта и возвращает индекс (начиная с нуля) первого вхождения в диапазоне элементов списка массива, который простирается от указанного индекса до последнего элемента.|
| [`index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells.slicers/slicercollection/index_of/#aspose.cells.slicers.slicer-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов списка массива, который начинается с указанного индекса и содержит указанное количество элементов.|
| [`last_index_of(self, item)`](/cells/python-net/ru/aspose.cells.slicers/slicercollection/last_index_of/#aspose.cells.slicers.slicer) | Выполняет поиск указанного объекта и возвращает нулевой индекс последнего вхождения во всем списке массива.|
| [`last_index_of(self, item, index)`](/cells/python-net/ru/aspose.cells.slicers/slicercollection/last_index_of/#aspose.cells.slicers.slicer-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который простирается от первого элемента до указанного индекса.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells.slicers/slicercollection/last_index_of/#aspose.cells.slicers.slicer-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который содержит указанное количество элементов и заканчивается на указанном индексе.|
| [`get(self, name)`](/cells/python-net/ru/aspose.cells.slicers/slicercollection/get/#str) | Получает слайсер по имени слайсера.|
| [`binary_search(self, item)`](/cells/python-net/ru/aspose.cells.slicers/slicercollection/binary_search/#aspose.cells.slicers.slicer) | Выполняет поиск элемента во всем отсортированном списке массивов, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



###  Пример

```python
from aspose.cells import Workbook
from aspose.cells.pivot import PivotFieldType, PivotTableStyleType

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
pivot.refresh_data()
pivot.calculate_data()
slicers = sheet.slicers
tableIndex = sheet.list_objects.add("A1", "C9", True)
table = sheet.list_objects[tableIndex]
# do your business
book.save("out.xlsx")

```

###  Смотрите также
* модуль [`aspose.cells.slicers`](..)
