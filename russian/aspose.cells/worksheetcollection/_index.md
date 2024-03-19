---
title: WorksheetCollection класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 1700
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
| [threaded_comment_authors](/cells/python-net/ru/aspose.cells/worksheetcollection/threaded_comment_authors) | Получает список авторов цепочек комментариев.|
| [is_refresh_all_connections](/cells/python-net/ru/aspose.cells/worksheetcollection/is_refresh_all_connections) | Указывает, обновляются ли все соединения при открытии файла в MS Excel.|
| [names](/cells/python-net/ru/aspose.cells/worksheetcollection/names) |Получает коллекцию всех объектов Name в электронной таблице.|
| [active_sheet_name](/cells/python-net/ru/aspose.cells/worksheetcollection/active_sheet_name) | Представляет имя активного листа при открытии электронной таблицы.|
| [active_sheet_index](/cells/python-net/ru/aspose.cells/worksheetcollection/active_sheet_index) | Представляет индекс активного листа при открытии электронной таблицы.|
| [dxfs](/cells/python-net/ru/aspose.cells/worksheetcollection/dxfs) | Получает основные записи дифференциального форматирования.|
| [xml_maps](/cells/python-net/ru/aspose.cells/worksheetcollection/xml_maps) | Получает и задает карты XML в книге.|
| [built_in_document_properties](/cells/python-net/ru/aspose.cells/worksheetcollection/built_in_document_properties) | Возвращает коллекцию [`DocumentProperty`](/cells/python-net/ru/aspose.cells.properties/documentproperty), которая представляет все встроенные свойства документа электронной таблицы.|
| [custom_document_properties](/cells/python-net/ru/aspose.cells/worksheetcollection/custom_document_properties) | Возвращает коллекцию [`DocumentProperty`](/cells/python-net/ru/aspose.cells.properties/documentproperty), которая представляет все настраиваемые свойства документа электронной таблицы.|
| [ole_size](/cells/python-net/ru/aspose.cells/worksheetcollection/ole_size) | Получает и задает отображаемый размер, когда файл книги используется в качестве объекта Ole.|
| [external_links](/cells/python-net/ru/aspose.cells/worksheetcollection/external_links) | Представляет внешние ссылки в книге.|
| [table_styles](/cells/python-net/ru/aspose.cells/worksheetcollection/table_styles) | Получает объект [`WorksheetCollection.table_styles`](/cells/python-net/ru/aspose.cells/worksheetcollection#table_styles).|
| [revision_logs](/cells/python-net/ru/aspose.cells/worksheetcollection/revision_logs) | Представляет журналы изменений.|
| [capacity](/cells/python-net/ru/aspose.cells/worksheetcollection/capacity) | Получает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [get](/cells/python-net/ru/aspose.cells/worksheetcollection/get/#int) | Добавьте API for Python через .Net.так как этот[int index] не поддерживается.|
| [get](/cells/python-net/ru/aspose.cells/worksheetcollection/get/#str) | Добавьте API for Python через .Net.поскольку это [строковое имя листа] не поддерживается.|
| [add](/cells/python-net/ru/aspose.cells/worksheetcollection/add/#aspose.cells.SheetType) | Добавляет лист в коллекцию.|
| [add](/cells/python-net/ru/aspose.cells/worksheetcollection/add/#) | Добавляет лист в коллекцию.|
| [add](/cells/python-net/ru/aspose.cells/worksheetcollection/add/#str) | Добавляет лист в коллекцию.|
| [register_add_in_function](/cells/python-net/ru/aspose.cells/worksheetcollection/register_add_in_function/#str-str-bool) | Добавляет функцию надстройки в книгу|
| [register_add_in_function](/cells/python-net/ru/aspose.cells/worksheetcollection/register_add_in_function/#int-str) | Добавляет функцию надстройки в книгу|
| [add_copy](/cells/python-net/ru/aspose.cells/worksheetcollection/add_copy/#str) | Добавляет лист в коллекцию и копирует данные из существующего листа.|
| [add_copy](/cells/python-net/ru/aspose.cells/worksheetcollection/add_copy/#int) | Добавляет лист в коллекцию и копирует данные из существующего листа.|
| [add_copy](/cells/python-net/ru/aspose.cells/worksheetcollection/add_copy/#list-list) | Скопируйте группу листов.|
| [get_range_by_name](/cells/python-net/ru/aspose.cells/worksheetcollection/get_range_by_name/#str) | Получает объект Range по заранее определенному имени.|
| [get_range_by_name](/cells/python-net/ru/aspose.cells/worksheetcollection/get_range_by_name/#str-int-bool) | Получает [`Range`](/cells/python-net/ru/aspose.cells/range) по заранее определенному имени или имени таблицы.|
| [copy_to](/cells/python-net/ru/aspose.cells/worksheetcollection/copy_to/#list) | Копирует весь список массивов в совместимый список одномерных массивов, начиная с начала списка целевых массивов.|
| [copy_to](/cells/python-net/ru/aspose.cells/worksheetcollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массива в совместимый список одномерных массивов, начиная с указанного индекса списка целевого массива.|
| [index_of](/cells/python-net/ru/aspose.cells/worksheetcollection/index_of/#aspose.cells.Worksheet-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов в списке массива, простирающемся от указанного индекса до последнего элемента.|
| [index_of](/cells/python-net/ru/aspose.cells/worksheetcollection/index_of/#aspose.cells.Worksheet-int-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов в списке массивов, который начинается с указанного индекса и содержит указанное количество элементов.|
| [last_index_of](/cells/python-net/ru/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.Worksheet) | Ищет указанный объект и возвращает отсчитываемый от нуля индекс последнего вхождения во всем списке массива.|
| [last_index_of](/cells/python-net/ru/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.Worksheet-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов в списке массива, простирающемся от первого элемента до указанного индекса.|
| [last_index_of](/cells/python-net/ru/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.Worksheet-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов в списке массива, который содержит указанное количество элементов и заканчивается указанным индексом.|
| [create_range](/cells/python-net/ru/aspose.cells/worksheetcollection/create_range/#str-int) | Создает объект [`Range`](/cells/python-net/ru/aspose.cells/range) на основе адреса диапазона.|
| [create_union_range](/cells/python-net/ru/aspose.cells/worksheetcollection/create_union_range/#str-int) | Создает объект [`Range`](/cells/python-net/ru/aspose.cells/range) на основе адреса диапазона.|
| [get_sheet_by_code_name](/cells/python-net/ru/aspose.cells/worksheetcollection/get_sheet_by_code_name/#str) | Получает лист по кодовому имени.|
| [sort_names](/cells/python-net/ru/aspose.cells/worksheetcollection/sort_names/#) | Сортирует определенные имена.|
| [swap_sheet](/cells/python-net/ru/aspose.cells/worksheetcollection/swap_sheet/#int-int) |Меняет местами два листа.|
| [remove_at](/cells/python-net/ru/aspose.cells/worksheetcollection/remove_at/#str) | Удаляет элемент с указанным именем.|
| [get_named_ranges](/cells/python-net/ru/aspose.cells/worksheetcollection/get_named_ranges/#) | Получает все предварительно определенные именованные диапазоны в электронной таблице.|
| [get_named_ranges_and_tables](/cells/python-net/ru/aspose.cells/worksheetcollection/get_named_ranges_and_tables/#) | Получает все предварительно определенные именованные диапазоны в электронной таблице.|
| [set_ole_size](/cells/python-net/ru/aspose.cells/worksheetcollection/set_ole_size/#int-int-int-int) | Устанавливает отображаемый размер, когда файл книги используется в качестве объекта Ole.|
| [clear_pivottables](/cells/python-net/ru/aspose.cells/worksheetcollection/clear_pivottables/#) | Удаляет сводные таблицы из электронной таблицы.|
| [refresh_all](/cells/python-net/ru/aspose.cells/worksheetcollection/refresh_all/#) | Обновите все сводные таблицы и диаграммы, используя источник сводных данных.|
| [refresh_pivot_tables](/cells/python-net/ru/aspose.cells/worksheetcollection/refresh_pivot_tables/#) | Обновляет все сводные таблицы в коллекции WorksheetCollection.|
| [binary_search](/cells/python-net/ru/aspose.cells/worksheetcollection/binary_search/#aspose.cells.Worksheet) | Выполняет поиск элемента во всем списке отсортированного массива, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



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
