---
title: WorksheetCollection класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 1610
url: /ru/aspose.cells/worksheetcollection/
is_root: false
---
##  WorksheetCollection класс
Инкапсулирует коллекцию из [`Worksheet`](/cells/python-net/ru/aspose.cells/worksheet) объектов.



Тип WorksheetCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [web_extension_task_panes](/cells/python-net/ru/aspose.cells/worksheetcollection/web_extension_task_panes) | Получает список областей задач.|
| [web_extensions](/cells/python-net/ru/aspose.cells/worksheetcollection/web_extensions) | Получает список областей задач.|
| [threaded_comment_authors](/cells/python-net/ru/aspose.cells/worksheetcollection/threaded_comment_authors) | Получает список авторов связанных комментариев.|
| [is_refresh_all_connections](/cells/python-net/ru/aspose.cells/worksheetcollection/is_refresh_all_connections) | Указывает, обновлять ли все соединения при открытии файла в MS Excel.|
| [names](/cells/python-net/ru/aspose.cells/worksheetcollection/names) | Получает коллекцию всех объектов Name в электронной таблице.|
| [active_sheet_name](/cells/python-net/ru/aspose.cells/worksheetcollection/active_sheet_name) | Представляет имя активного рабочего листа при открытии электронной таблицы.|
| [active_sheet_index](/cells/python-net/ru/aspose.cells/worksheetcollection/active_sheet_index) | Представляет индекс активного листа при открытии электронной таблицы.|
| [dxfs](/cells/python-net/ru/aspose.cells/worksheetcollection/dxfs) | Получает основные записи дифференциального форматирования.|
| [xml_maps](/cells/python-net/ru/aspose.cells/worksheetcollection/xml_maps) | Получает и задает карты XML в рабочей книге.|
| [built_in_document_properties](/cells/python-net/ru/aspose.cells/worksheetcollection/built_in_document_properties) | Возвращает коллекцию [`DocumentProperty`](/cells/python-net/ru/aspose.cells.properties/documentproperty), которая представляет все встроенные свойства документа электронной таблицы.|
| [custom_document_properties](/cells/python-net/ru/aspose.cells/worksheetcollection/custom_document_properties) | Возвращает коллекцию [`DocumentProperty`](/cells/python-net/ru/aspose.cells.properties/documentproperty), которая представляет все пользовательские свойства документа электронной таблицы.|
| [ole_size](/cells/python-net/ru/aspose.cells/worksheetcollection/ole_size) | Возвращает и задает отображаемый размер, когда файл рабочей книги используется как объект Ole.|
| [external_links](/cells/python-net/ru/aspose.cells/worksheetcollection/external_links) |Представляет внешние ссылки в рабочей книге.|
| [table_styles](/cells/python-net/ru/aspose.cells/worksheetcollection/table_styles) | Получает объект [`WorksheetCollection.table_styles`](/cells/python-net/ru/aspose.cells/worksheetcollection#table_styles).|
| [revision_logs](/cells/python-net/ru/aspose.cells/worksheetcollection/revision_logs) | Представляет журналы изменений.|
| [sensitivity_labels](/cells/python-net/ru/aspose.cells/worksheetcollection/sensitivity_labels) | Представляет все метки чувствительности.|
| [capacity](/cells/python-net/ru/aspose.cells/worksheetcollection/capacity) | Возвращает или задает количество элементов, которые может содержать список массива.|



Получает элемент [`Worksheet`](/cells/python-net/ru/aspose.cells/worksheet) по указанному индексу.
###  Индексатор
| Имя| Описание|
| :- | :- |
| [index] | Индекс элемента, отсчитываемый от нуля.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`get(self, index)`](/cells/python-net/ru/aspose.cells/worksheetcollection/get/#int) | Добавьте API for Python через .Net.since this[int index] не поддерживается|
| [`get(self, sheet_name)`](/cells/python-net/ru/aspose.cells/worksheetcollection/get/#str) | Добавьте API for Python через .Net.since this[string sheetName] is not supported|
| [`add(self, type)`](/cells/python-net/ru/aspose.cells/worksheetcollection/add/#aspose.cells.sheettype) | Добавляет рабочий лист в коллекцию.|
| [`add(self)`](/cells/python-net/ru/aspose.cells/worksheetcollection/add/#) | Добавляет рабочий лист в коллекцию.|
| [`add(self, sheet_name)`](/cells/python-net/ru/aspose.cells/worksheetcollection/add/#str) | Добавляет рабочий лист в коллекцию.|
| [`register_add_in_function(self, add_in_file, function_name, lib)`](/cells/python-net/ru/aspose.cells/worksheetcollection/register_add_in_function/#str-str-bool) | Добавляет функцию надстройки в рабочую книгу|
| [`register_add_in_function(self, id, function_name)`](/cells/python-net/ru/aspose.cells/worksheetcollection/register_add_in_function/#int-str) | Добавляет функцию надстройки в рабочую книгу|
| [`add_copy(self, sheet_name)`](/cells/python-net/ru/aspose.cells/worksheetcollection/add_copy/#str) | Добавляет рабочий лист в коллекцию и копирует данные из существующего рабочего листа.|
| [`add_copy(self, sheet_index)`](/cells/python-net/ru/aspose.cells/worksheetcollection/add_copy/#int) | Добавляет рабочий лист в коллекцию и копирует данные из существующего рабочего листа.|
| [`add_copy(self, source, dest_sheet_names)`](/cells/python-net/ru/aspose.cells/worksheetcollection/add_copy/#list-list) | Скопируйте группу рабочих листов.|
| [`get_range_by_name(self, range_name)`](/cells/python-net/ru/aspose.cells/worksheetcollection/get_range_by_name/#str) | Получает объект Range по предопределенному имени.|
| [`get_range_by_name(self, range_name, current_sheet_index, include_table)`](/cells/python-net/ru/aspose.cells/worksheetcollection/get_range_by_name/#str-int-bool) | Получает [`Range`](/cells/python-net/ru/aspose.cells/range) по предопределенному имени или имени таблицы|
| [`refresh_pivot_tables(self)`](/cells/python-net/ru/aspose.cells/worksheetcollection/refresh_pivot_tables/#) | Обновляет все сводные таблицы в файле Excel.|
| [`refresh_pivot_tables(self, option)`](/cells/python-net/ru/aspose.cells/worksheetcollection/refresh_pivot_tables/#aspose.cells.pivot.pivottablerefreshoption) | Обновляет все сводные таблицы в файле Excel.|
| [`copy_to(self, array)`](/cells/python-net/ru/aspose.cells/worksheetcollection/copy_to/#list) |Копирует весь список массивов в совместимый одномерный список массивов, начиная с начала целевого списка массивов.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ru/aspose.cells/worksheetcollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массивов в совместимый список одномерных массивов, начиная с указанного индекса целевого списка массивов.|
| [`index_of(self, item, index)`](/cells/python-net/ru/aspose.cells/worksheetcollection/index_of/#aspose.cells.worksheet-int) | Выполняет поиск указанного объекта и возвращает индекс (начиная с нуля) первого вхождения в диапазоне элементов списка массива, который простирается от указанного индекса до последнего элемента.|
| [`index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells/worksheetcollection/index_of/#aspose.cells.worksheet-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов списка массива, который начинается с указанного индекса и содержит указанное количество элементов.|
| [`last_index_of(self, item)`](/cells/python-net/ru/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.worksheet) | Выполняет поиск указанного объекта и возвращает нулевой индекс последнего вхождения во всем списке массива.|
| [`last_index_of(self, item, index)`](/cells/python-net/ru/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.worksheet-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который простирается от первого элемента до указанного индекса.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.worksheet-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который содержит указанное количество элементов и заканчивается на указанном индексе.|
| [`create_range(self, address, sheet_index)`](/cells/python-net/ru/aspose.cells/worksheetcollection/create_range/#str-int) | Создает объект [`Range`](/cells/python-net/ru/aspose.cells/range) из адреса диапазона.|
| [`create_union_range(self, address, sheet_index)`](/cells/python-net/ru/aspose.cells/worksheetcollection/create_union_range/#str-int) | Создает объект [`Range`](/cells/python-net/ru/aspose.cells/range) из адреса диапазона.|
| [`get_sheet_by_code_name(self, code_name)`](/cells/python-net/ru/aspose.cells/worksheetcollection/get_sheet_by_code_name/#str) | Получает рабочий лист по кодовому имени.|
| [`sort_names(self)`](/cells/python-net/ru/aspose.cells/worksheetcollection/sort_names/#) | Сортирует определенные имена.|
| [`swap_sheet(self, sheet_index1, sheet_index2)`](/cells/python-net/ru/aspose.cells/worksheetcollection/swap_sheet/#int-int) | Меняет местами два листа.|
| [`remove_by_name(self, name)`](/cells/python-net/ru/aspose.cells/worksheetcollection/remove_by_name/#str) | Удалить лист по имени листа.(CELLSPYTHONNET-192)|
| [`remove_by_index(self, index)`](/cells/python-net/ru/aspose.cells/worksheetcollection/remove_by_index/#int) | Удалить индекс лист за листом|
| [`remove_at(self, name)`](/cells/python-net/ru/aspose.cells/worksheetcollection/remove_at/#str) | Удаляет элемент с указанным именем.|
| [`get_named_ranges(self)`](/cells/python-net/ru/aspose.cells/worksheetcollection/get_named_ranges/#) | Получает все предопределенные именованные диапазоны в электронной таблице.|
| [`get_named_ranges_and_tables(self)`](/cells/python-net/ru/aspose.cells/worksheetcollection/get_named_ranges_and_tables/#) | Получает все предопределенные именованные диапазоны в электронной таблице.|
| [`set_ole_size(self, start_row, end_row, start_column, end_column)`](/cells/python-net/ru/aspose.cells/worksheetcollection/set_ole_size/#int-int-int-int) | Устанавливает отображаемый размер при использовании файла рабочей книги в качестве объекта Ole.|
| [`clear_pivottables(self)`](/cells/python-net/ru/aspose.cells/worksheetcollection/clear_pivottables/#) |Удаляет сводные таблицы из электронной таблицы.|
| [`refresh_all(self)`](/cells/python-net/ru/aspose.cells/worksheetcollection/refresh_all/#) | Обновите все сводные таблицы и диаграммы с использованием источника сводных данных.|
| [`binary_search(self, item)`](/cells/python-net/ru/aspose.cells/worksheetcollection/binary_search/#aspose.cells.worksheet) | Выполняет поиск элемента во всем отсортированном списке массивов, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



###  Пример

```python
from aspose.cells import Workbook

workbook = Workbook()
sheets = workbook.worksheets
# Add a worksheet
sheets.add()
# Change the name of a worksheet
sheets[0].name = "First Sheet"
# Set the active sheet to the second worksheet
sheets.active_sheet_index = 1

```

###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`DocumentProperty`](/cells/python-net/ru/aspose.cells.properties/documentproperty)
* класс [`Range`](/cells/python-net/ru/aspose.cells/range)
* класс [`Worksheet`](/cells/python-net/ru/aspose.cells/worksheet)
