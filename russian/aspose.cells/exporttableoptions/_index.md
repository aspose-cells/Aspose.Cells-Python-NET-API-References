---
title: ExportTableOptions класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 560
url: /ru/aspose.cells/exporttableoptions/
is_root: false
---
##  ExportTableOptions класс
Представляет все параметры экспортной таблицы.



Тип ExportTableOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells/exporttableoptions/__init__/#) | Создает новый экземпляр ExportTableOptions|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [export_column_name](/cells/python-net/ru/aspose.cells/exporttableoptions/export_column_name) | Указывает, экспортируются ли данные из первой строки в имя столбца DataTable.<br/> Значение по умолчанию — false.|
| [skip_error_value](/cells/python-net/ru/aspose.cells/exporttableoptions/skip_error_value) | Указывает, следует ли пропускать недопустимое значение для столбца.<br/> Например, если тип столбца — десятичный, значение больше decimal.MaxValue<br/>и это свойство истинно, мы не будем снова выдавать исключение.<br/> Значение по умолчанию — false.|
| [plot_visible_cells](/cells/python-net/ru/aspose.cells/exporttableoptions/plot_visible_cells) | Экспортирует только видимые ячейки.|
| [plot_visible_rows](/cells/python-net/ru/aspose.cells/exporttableoptions/plot_visible_rows) | Экспортирует только видимые строки.|
| [plot_visible_columns](/cells/python-net/ru/aspose.cells/exporttableoptions/plot_visible_columns) | Экспортирует только видимые столбцы.|
| [export_as_string](/cells/python-net/ru/aspose.cells/exporttableoptions/export_as_string) | Экспортирует строковое значение ячеек в DataTable.|
| [export_as_html_string](/cells/python-net/ru/aspose.cells/exporttableoptions/export_as_html_string) | Экспортирует строковое значение HTML ячеек в DataTable.|
| [format_strategy](/cells/python-net/ru/aspose.cells/exporttableoptions/format_strategy) | Возвращает и задает стратегию форматирования при экспорте значения как строкового значения.|
| [check_mixed_value_type](/cells/python-net/ru/aspose.cells/exporttableoptions/check_mixed_value_type) | Ложь, Aspose.Cells установит тип DataColumn по типу значения первой строки для производительности.<br/> True, Aspose.Cells проверит, являются ли типы значений в столбце смешанными, прежде чем задать тип DataColumn.<br/> А типы значений смешанные, тип DataColumn будет строковым.|
| [allow_db_null](/cells/python-net/ru/aspose.cells/exporttableoptions/allow_db_null) |Это значение указывает, разрешены ли значения DBNulls в этой таблице.|
| [is_vertical](/cells/python-net/ru/aspose.cells/exporttableoptions/is_vertical) | True, если строка в файле Workbook представляет строку в DataTable. False, если столбец в файле Workbook представляет строку в DataTable.|
| [indexes](/cells/python-net/ru/aspose.cells/exporttableoptions/indexes) | Индексы столбцов/строк, которые следует экспортировать.|
| [rename_strategy](/cells/python-net/ru/aspose.cells/exporttableoptions/rename_strategy) | Стратегия в отношении дублирующихся названий столбцов.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`preprocess_exported_value(self, cell_row, cell_column, value)`](/cells/python-net/ru/aspose.cells/exporttableoptions/preprocess_exported_value/#int-int-aspose.cells.cellvalue) | Предварительно обработать значение текущей ячейки для экспорта.|



###  Примечания

Если есть особые требования к экспорту, например, игнорирование значений ошибок, пользователь может расширить этот класс.
перезаписать соответствующие API для достижения цели.

###  Смотрите также
* модуль [`aspose.cells`](..)
