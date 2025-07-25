---
title: TableStyleCollection класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 60
url: /ru/aspose.cells.tables/tablestylecollection/
is_root: false
---
##  TableStyleCollection класс
Представляет все пользовательские стили таблиц.



Тип TableStyleCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [default_table_style_name](/cells/python-net/ru/aspose.cells.tables/tablestylecollection/default_table_style_name) | Получает и задает имя стиля по умолчанию для таблицы.|
| [default_pivot_style_name](/cells/python-net/ru/aspose.cells.tables/tablestylecollection/default_pivot_style_name) | Получает и задает имя стиля по умолчанию для сводной таблицы.|
| [capacity](/cells/python-net/ru/aspose.cells.tables/tablestylecollection/capacity) | Возвращает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/ru/aspose.cells.tables/tablestylecollection/copy_to/#list) |Копирует весь список массивов в совместимый одномерный список массивов, начиная с начала целевого списка массивов.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ru/aspose.cells.tables/tablestylecollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массивов в совместимый список одномерных массивов, начиная с указанного индекса целевого списка массивов.|
| [`index_of(self, item, index)`](/cells/python-net/ru/aspose.cells.tables/tablestylecollection/index_of/#aspose.cells.tables.tablestyle-int) | Выполняет поиск указанного объекта и возвращает индекс (начиная с нуля) первого вхождения в диапазоне элементов списка массива, который простирается от указанного индекса до последнего элемента.|
| [`index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells.tables/tablestylecollection/index_of/#aspose.cells.tables.tablestyle-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов списка массива, который начинается с указанного индекса и содержит указанное количество элементов.|
| [`last_index_of(self, item)`](/cells/python-net/ru/aspose.cells.tables/tablestylecollection/last_index_of/#aspose.cells.tables.tablestyle) | Выполняет поиск указанного объекта и возвращает нулевой индекс последнего вхождения во всем списке массива.|
| [`last_index_of(self, item, index)`](/cells/python-net/ru/aspose.cells.tables/tablestylecollection/last_index_of/#aspose.cells.tables.tablestyle-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который простирается от первого элемента до указанного индекса.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells.tables/tablestylecollection/last_index_of/#aspose.cells.tables.tablestyle-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который содержит указанное количество элементов и заканчивается на указанном индексе.|
| [`add_table_style(self, name)`](/cells/python-net/ru/aspose.cells.tables/tablestylecollection/add_table_style/#str) | Добавляет пользовательский стиль таблицы.|
| [`add_pivot_table_style(self, name)`](/cells/python-net/ru/aspose.cells.tables/tablestylecollection/add_pivot_table_style/#str) | Добавляет пользовательский стиль сводной таблицы.|
| [`get(self, name)`](/cells/python-net/ru/aspose.cells.tables/tablestylecollection/get/#str) | Получает стиль таблицы по имени.|
| [`get_builtin_table_style(self, type)`](/cells/python-net/ru/aspose.cells.tables/tablestylecollection/get_builtin_table_style/#aspose.cells.tables.tablestyletype) | Получает встроенный стиль таблицы|
| [`binary_search(self, item)`](/cells/python-net/ru/aspose.cells.tables/tablestylecollection/binary_search/#aspose.cells.tables.tablestyle) | Выполняет поиск элемента во всем отсортированном списке массивов, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



###  Смотрите также
* модуль [`aspose.cells.tables`](..)
