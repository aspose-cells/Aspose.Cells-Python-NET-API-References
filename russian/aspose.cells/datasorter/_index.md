---
title: DataSorter класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 410
url: /ru/aspose.cells/datasorter/
is_root: false
---
##  DataSorter класс
Краткое описание для DataSorter.



Тип DataSorter предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [keys](/cells/python-net/ru/aspose.cells/datasorter/keys) | Получает список ключей сортировщика данных.|
| [has_headers](/cells/python-net/ru/aspose.cells/datasorter/has_headers) | Указывает, есть ли у диапазона заголовки.|
| [key1](/cells/python-net/ru/aspose.cells/datasorter/key1) | Представляет первый отсортированный индекс столбца (абсолютная позиция, столбец A равен 0, B равен 1, ...).|
| [order1](/cells/python-net/ru/aspose.cells/datasorter/order1) | Представляет порядок сортировки первого ключа.|
| [key2](/cells/python-net/ru/aspose.cells/datasorter/key2) | Представляет второй отсортированный индекс столбца (абсолютная позиция, столбец A равен 0, B равен 1, ...).|
| [order2](/cells/python-net/ru/aspose.cells/datasorter/order2) | Представляет порядок сортировки второго ключа.|
| [key3](/cells/python-net/ru/aspose.cells/datasorter/key3) | Представляет третий отсортированный индекс столбца (абсолютная позиция, столбец A равен 0, B равен 1, ...).|
| [order3](/cells/python-net/ru/aspose.cells/datasorter/order3) | Представляет порядок сортировки третьего ключа.|
| [sort_left_to_right](/cells/python-net/ru/aspose.cells/datasorter/sort_left_to_right) |True означает, что ориентация сортировки — слева направо.<br/>Значение False означает, что сортировка производится сверху вниз.<br/> Значение по умолчанию — false.|
| [case_sensitive](/cells/python-net/ru/aspose.cells/datasorter/case_sensitive) | Возвращает и задает, учитывается ли регистр при сравнении строк.|
| [sort_as_number](/cells/python-net/ru/aspose.cells/datasorter/sort_as_number) | Указывает, сортируется ли что-либо, похожее на число.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`add_key(self, key, order)`](/cells/python-net/ru/aspose.cells/datasorter/add_key/#int-aspose.cells.sortorder) | Добавляет отсортированный индекс столбца и порядок сортировки.|
| [`add_key(self, key, order, custom_list)`](/cells/python-net/ru/aspose.cells/datasorter/add_key/#int-aspose.cells.sortorder-str) | Добавляет отсортированный индекс столбца и порядок сортировки с помощью настраиваемого списка сортировки.|
| [`add_key(self, key, type, order, custom_list)`](/cells/python-net/ru/aspose.cells/datasorter/add_key/#int-aspose.cells.sortontype-aspose.cells.sortorder-any) | Добавляет отсортированный индекс столбца и порядок сортировки с помощью настраиваемого списка сортировки.|
| [`add_key(self, key, order, custom_list)`](/cells/python-net/ru/aspose.cells/datasorter/add_key/#int-aspose.cells.sortorder-list) | Добавляет отсортированный индекс столбца и порядок сортировки с помощью настраиваемого списка сортировки.|
| [`sort(self, cells, start_row, start_column, end_row, end_column)`](/cells/python-net/ru/aspose.cells/datasorter/sort/#aspose.cells.cells-int-int-int-int) | Сортирует данные по области.|
| [`sort(self, cells, area)`](/cells/python-net/ru/aspose.cells/datasorter/sort/#aspose.cells.cells-aspose.cells.cellarea) | Сортировать данные по области.|
| [`sort(self)`](/cells/python-net/ru/aspose.cells/datasorter/sort/#) | Отсортируйте данные в диапазоне.|
| [`clear(self)`](/cells/python-net/ru/aspose.cells/datasorter/clear/#) | Очистить все настройки.|
| [`add_color_key(self, key, type, order, color)`](/cells/python-net/ru/aspose.cells/datasorter/add_color_key/#int-aspose.cells.sortontype-aspose.cells.sortorder-aspose.pydrawing.color) | Добавляет ключ сортировки по цвету.|



###  Пример

```python
from aspose.cells import CellArea, SortOrder, Workbook

# Instantiate a new Workbook object.
workbook = Workbook("Book1.xls")
# Get the workbook datasorter object.
sorter = workbook.data_sorter
# Set the first order for datasorter object.
sorter.order1 = SortOrder.DESCENDING
# Define the first key.
sorter.key1 = 0
# Set the second order for datasorter object.
sorter.order2 = SortOrder.ASCENDING
# Define the second key.
sorter.key2 = 1
# Create a cells area (range).
ca = CellArea()
# Specify the start row index.
ca.start_row = 0
# Specify the start column index.
ca.start_column = 0
# Specify the last row index.
ca.end_row = 13
# Specify the last column index.
ca.end_column = 1
# Sort data in the specified data range (A1:B14)
sorter.sort(workbook.worksheets[0].cells, ca)
# Save the excel file.
workbook.save("outBook.xls")

```

###  Смотрите также
* модуль [`aspose.cells`](..)
