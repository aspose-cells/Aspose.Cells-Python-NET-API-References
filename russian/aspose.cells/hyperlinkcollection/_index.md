---
title: HyperlinkCollection класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 830
url: /ru/aspose.cells/hyperlinkcollection/
is_root: false
---
##  HyperlinkCollection класс
Инкапсулирует коллекцию из [`Hyperlink`](/cells/python-net/ru/aspose.cells/hyperlink) объектов.



Тип HyperlinkCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [capacity](/cells/python-net/ru/aspose.cells/hyperlinkcollection/capacity) | Возвращает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`add(self, first_row, first_column, total_rows, total_columns, address)`](/cells/python-net/ru/aspose.cells/hyperlinkcollection/add/#int-int-int-int-str) | Добавляет гиперссылку к указанной ячейке или диапазону ячеек.|
| [`add(self, cell_name, total_rows, total_columns, address)`](/cells/python-net/ru/aspose.cells/hyperlinkcollection/add/#str-int-int-str) | Добавляет гиперссылку к указанной ячейке или диапазону ячеек.|
| [`add(self, start_cell_name, end_cell_name, address, text_to_display, screen_tip)`](/cells/python-net/ru/aspose.cells/hyperlinkcollection/add/#str-str-str-str-str) | Добавляет гиперссылку к указанной ячейке или диапазону ячеек.|
| [`copy_to(self, array)`](/cells/python-net/ru/aspose.cells/hyperlinkcollection/copy_to/#list) |Копирует весь список массивов в совместимый одномерный список массивов, начиная с начала целевого списка массивов.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ru/aspose.cells/hyperlinkcollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массивов в совместимый список одномерных массивов, начиная с указанного индекса целевого списка массивов.|
| [`index_of(self, item, index)`](/cells/python-net/ru/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.hyperlink-int) | Выполняет поиск указанного объекта и возвращает индекс (начиная с нуля) первого вхождения в диапазоне элементов списка массива, который простирается от указанного индекса до последнего элемента.|
| [`index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.hyperlink-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов списка массива, который начинается с указанного индекса и содержит указанное количество элементов.|
| [`last_index_of(self, item)`](/cells/python-net/ru/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.hyperlink) | Выполняет поиск указанного объекта и возвращает нулевой индекс последнего вхождения во всем списке массива.|
| [`last_index_of(self, item, index)`](/cells/python-net/ru/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.hyperlink-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который простирается от первого элемента до указанного индекса.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.hyperlink-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который содержит указанное количество элементов и заканчивается на указанном индексе.|
| [`binary_search(self, item)`](/cells/python-net/ru/aspose.cells/hyperlinkcollection/binary_search/#aspose.cells.hyperlink) | Выполняет поиск элемента во всем отсортированном списке массивов, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



###  Пример

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Get Hyperlinks Collection
hyperlinks = worksheet.hyperlinks
# Adding a hyperlink to a URL at "A1" cell
hyperlinks.add("A1", 1, 1, "http://www.aspose.com")
# Saving the Excel file
workbook.save("book1.xls")

```

###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`Hyperlink`](/cells/python-net/ru/aspose.cells/hyperlink)
