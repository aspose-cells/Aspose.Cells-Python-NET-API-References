---
title: WorksheetCollection класс
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 1630
url: /ru/aspose.cells/worksheetcollection/
is_root: false
---
##  WorksheetCollection класс
Инкапсулирует коллекцию из [Worksheet](/cells/python-net/ru/aspose.cells/worksheet) объектов.



Тип WorksheetCollection предоставляет следующие члены:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [web_extension_task_panes](/cells/python-net/ru/aspose.cells/worksheetcollection/web_extension_task_panes) | Получает список областей задач.|
| [web_extensions](/cells/python-net/ru/aspose.cells/worksheetcollection/web_extensions) | Получает список областей задач.|
| [threaded_comment_authors](/cells/python-net/ru/aspose.cells/worksheetcollection/threaded_comment_authors) | Получает список авторов цепочек комментариев.|
| [is_refresh_all_connections](/cells/python-net/ru/aspose.cells/worksheetcollection/is_refresh_all_connections) | Указывает, будут ли обновляться все соединения при открытии файла в MS Excel.|
| [names](/cells/python-net/ru/aspose.cells/worksheetcollection/names) | Получает коллекцию всех объектов Name в электронной таблице.|
| [active_sheet_name](/cells/python-net/ru/aspose.cells/worksheetcollection/active_sheet_name) | Представляет имя активного рабочего листа при открытии электронной таблицы.|
| [active_sheet_index](/cells/python-net/ru/aspose.cells/worksheetcollection/active_sheet_index) | Представляет индекс активного рабочего листа при открытии электронной таблицы.|
| [dxfs](/cells/python-net/ru/aspose.cells/worksheetcollection/dxfs) | Получает основные записи дифференциального форматирования.|
| [xml_maps](/cells/python-net/ru/aspose.cells/worksheetcollection/xml_maps) | Получает и задает карты XML в книге.|
| [built_in_document_properties](/cells/python-net/ru/aspose.cells/worksheetcollection/built_in_document_properties) | Возвращает коллекцию [DocumentProperty](/cells/python-net/ru/aspose.cells.properties/documentproperty), которая представляет все встроенные свойства документа электронной таблицы.|
| [custom_document_properties](/cells/python-net/ru/aspose.cells/worksheetcollection/custom_document_properties) | Возвращает коллекцию [DocumentProperty](/cells/python-net/ru/aspose.cells.properties/documentproperty), которая представляет все настраиваемые свойства документа электронной таблицы.|
| [ole_size](/cells/python-net/ru/aspose.cells/worksheetcollection/ole_size) | Получает и задает отображаемый размер, когда файл рабочей книги используется в качестве объекта Ole.|
| [external_links](/cells/python-net/ru/aspose.cells/worksheetcollection/external_links) | Представляет внешние ссылки в книге.|
| [table_styles](/cells/python-net/ru/aspose.cells/worksheetcollection/table_styles) | Получает объект [WorksheetCollection.table_styles](/cells/python-net/ru/aspose.cells/worksheetcollection#table_styles).|
| [revision_logs](/cells/python-net/ru/aspose.cells/worksheetcollection/revision_logs) |Представляет журналы изменений.|
| [capacity](/cells/python-net/ru/aspose.cells/worksheetcollection/capacity) | Получает или задает количество элементов, которые может содержать список массивов.|


###  Методы
| Метод| Описание|
| :- | :- |
| [get(index)](/cells/python-net/ru/aspose.cells/worksheetcollection/get/#int) |Добавить API for Python через .Net.так как это [индекс int] не поддерживается|
| [get(sheet_name)](/cells/python-net/ru/aspose.cells/worksheetcollection/get/#str) | Добавить API for Python через .Net.так как это [string sheetName] не поддерживается|
| [add(type)](/cells/python-net/ru/aspose.cells/worksheetcollection/add/#SheetType) | Добавляет рабочий лист в коллекцию.|
| [add()](/cells/python-net/ru/aspose.cells/worksheetcollection/add/#) | Добавляет рабочий лист в коллекцию.|
| [add(sheet_name)](/cells/python-net/ru/aspose.cells/worksheetcollection/add/#str) | Добавляет рабочий лист в коллекцию.|
| [register_add_in_function(add_in_file, function_name, lib)](/cells/python-net/ru/aspose.cells/worksheetcollection/register_add_in_function/#str-str-bool) | Добавляет функцию надстройки в книгу|
| [register_add_in_function(id, function_name)](/cells/python-net/ru/aspose.cells/worksheetcollection/register_add_in_function/#int-str) | Добавляет функцию надстройки в книгу|
| [add_copy(sheet_name)](/cells/python-net/ru/aspose.cells/worksheetcollection/add_copy/#str) | Добавляет лист в коллекцию и копирует данные из существующего листа.|
| [add_copy(sheet_index)](/cells/python-net/ru/aspose.cells/worksheetcollection/add_copy/#int) | Добавляет лист в коллекцию и копирует данные из существующего листа.|
| [get_range_by_name(range_name)](/cells/python-net/ru/aspose.cells/worksheetcollection/get_range_by_name/#str) | Получает объект Range по заданному имени.|
| [get_range_by_name(range_name, current_sheet_index, include_table)](/cells/python-net/ru/aspose.cells/worksheetcollection/get_range_by_name/#str-int-bool) | Получает [Range](/cells/python-net/ru/aspose.cells/range) по заданному имени или имени таблицы|
| [copy_to(array)](/cells/python-net/ru/aspose.cells/worksheetcollection/copy_to/#list) | Копирует весь список массивов в совместимый список одномерных массивов, начиная с начала целевого списка массивов.|
| [copy_to(index, array, array_index, count)](/cells/python-net/ru/aspose.cells/worksheetcollection/copy_to/#int-list-int-int) |Копирует диапазон элементов из списка массивов в совместимый список одномерных массивов, начиная с указанного индекса целевого списка массивов.|
| [index_of(item, index)](/cells/python-net/ru/aspose.cells/worksheetcollection/index_of/#Worksheet-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов в списке массивов, который простирается от указанного индекса до последнего элемента.|
| [index_of(item, index, count)](/cells/python-net/ru/aspose.cells/worksheetcollection/index_of/#Worksheet-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов в списке массивов, который начинается с указанного индекса и содержит указанное количество элементов.|
| [last_index_of(item)](/cells/python-net/ru/aspose.cells/worksheetcollection/last_index_of/#Worksheet) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения во всем списке массивов.|
| [last_index_of(item, index)](/cells/python-net/ru/aspose.cells/worksheetcollection/last_index_of/#Worksheet-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов в списке массивов, который простирается от первого элемента до указанного индекса.|
| [last_index_of(item, index, count)](/cells/python-net/ru/aspose.cells/worksheetcollection/last_index_of/#Worksheet-int-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов в списке массивов, который содержит указанное количество элементов и заканчивается указанным индексом.|
| [create_range(address, sheet_index)](/cells/python-net/ru/aspose.cells/worksheetcollection/create_range/#str-int) | Создает объект [Range](/cells/python-net/ru/aspose.cells/range) из адреса диапазона.|
| [create_union_range(address, sheet_index)](/cells/python-net/ru/aspose.cells/worksheetcollection/create_union_range/#str-int) | Создает объект [Range](/cells/python-net/ru/aspose.cells/range) из адреса диапазона.|
| [get_sheet_by_code_name(code_name)](/cells/python-net/ru/aspose.cells/worksheetcollection/get_sheet_by_code_name/#str) | Получает рабочий лист по кодовому имени.|
| [sort_names()](/cells/python-net/ru/aspose.cells/worksheetcollection/sort_names/#) | Сортирует определенные имена.|
| [swap_sheet(sheet_index1, sheet_index2)](/cells/python-net/ru/aspose.cells/worksheetcollection/swap_sheet/#int-int) | Меняет местами два листа.|
| [remove_at(name)](/cells/python-net/ru/aspose.cells/worksheetcollection/remove_at/#str) | Удаляет элемент с указанным именем.|
| [get_named_ranges()](/cells/python-net/ru/aspose.cells/worksheetcollection/get_named_ranges/#) | Получает все предопределенные именованные диапазоны в электронной таблице.|
| [get_named_ranges_and_tables()](/cells/python-net/ru/aspose.cells/worksheetcollection/get_named_ranges_and_tables/#) | Получает все предопределенные именованные диапазоны в электронной таблице.|
| [set_ole_size(start_row, end_row, start_column, end_column)](/cells/python-net/ru/aspose.cells/worksheetcollection/set_ole_size/#int-int-int-int) | Устанавливает отображаемый размер, когда файл рабочей книги используется в качестве объекта Ole.|
| [clear_pivottables()](/cells/python-net/ru/aspose.cells/worksheetcollection/clear_pivottables/#) | Удаляет сводные таблицы из электронной таблицы.|
| [refresh_pivot_tables()](/cells/python-net/ru/aspose.cells/worksheetcollection/refresh_pivot_tables/#) | Обновляет все сводные таблицы в коллекции WorksheetCollection.|
| [binary_search(item)](/cells/python-net/ru/aspose.cells/worksheetcollection/binary_search/#Worksheet) | Ищет элемент во всем отсортированном списке массивов, используя компаратор по умолчанию, и возвращает отсчитываемый от нуля индекс элемента.|



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
* модуль [aspose.cells](..)
* класс [DocumentProperty](/cells/python-net/ru/aspose.cells.properties/documentproperty)
* класс [Range](/cells/python-net/ru/aspose.cells/range)
* класс [Worksheet](/cells/python-net/ru/aspose.cells/worksheet)
