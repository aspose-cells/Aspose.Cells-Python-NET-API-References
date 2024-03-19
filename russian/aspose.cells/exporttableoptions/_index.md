---
title: ExportTableOptions класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 580
url: /ru/aspose.cells/exporttableoptions/
is_root: false
---
##  ExportTableOptions класс
Представляет все параметры таблицы экспорта.



Тип ExportTableOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [__init__](/cells/python-net/ru/aspose.cells/exporttableoptions/__init__/#) | Создает новый экземпляр ExportTableOptions.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [export_column_name](/cells/python-net/ru/aspose.cells/exporttableoptions/export_column_name) | Указывает, экспортируются ли данные в первой строке в имя столбца DataTable.<br/> Значение по умолчанию неверно.|
| [skip_error_value](/cells/python-net/ru/aspose.cells/exporttableoptions/skip_error_value) | Указывает, нужно ли пропускать недопустимое значение для столбца.<br/> Например, если тип столбца десятичный, значение больше десятичного. MaxValue<br/>и это свойство истинно, мы больше не будем создавать исключение.<br/> Значение по умолчанию неверно.|
| [plot_visible_cells](/cells/python-net/ru/aspose.cells/exporttableoptions/plot_visible_cells) | Экспортирует только видимые ячейки.|
| [plot_visible_rows](/cells/python-net/ru/aspose.cells/exporttableoptions/plot_visible_rows) | Экспортирует только видимые строки.|
| [plot_visible_columns](/cells/python-net/ru/aspose.cells/exporttableoptions/plot_visible_columns) | Экспортирует только видимые столбцы.|
| [export_as_string](/cells/python-net/ru/aspose.cells/exporttableoptions/export_as_string) | Экспортирует строковое значение ячеек в DataTable.|
| [export_as_html_string](/cells/python-net/ru/aspose.cells/exporttableoptions/export_as_html_string) | Экспортирует строковое значение ячеек HTML в DataTable.|
| [format_strategy](/cells/python-net/ru/aspose.cells/exporttableoptions/format_strategy) | Получает и задает стратегию форматирования при экспорте значения в виде строкового значения.|
| [check_mixed_value_type](/cells/python-net/ru/aspose.cells/exporttableoptions/check_mixed_value_type) | False, Aspose.Cells установит тип DataColumn по типу значения первой строки для повышения производительности.<br/> Правда, Aspose.Cells проверит, смешаны ли типы значений в столбце, прежде чем устанавливать тип DataColumn.<br/>И тип значения смешанный, тип DataColumn будет строковым.|
| [allow_db_null](/cells/python-net/ru/aspose.cells/exporttableoptions/allow_db_null) | Это значение указывает, разрешены ли DBNull в этой таблице.|
| [is_vertical](/cells/python-net/ru/aspose.cells/exporttableoptions/is_vertical) | Истинно, если строка в файле книги представляет строку в DataTable. Значение false, если столбец в файле книги представляет строку в DataTable.|
| [indexes](/cells/python-net/ru/aspose.cells/exporttableoptions/indexes) | Индексы столбцов/строк, которые следует экспортировать.|
| [rename_strategy](/cells/python-net/ru/aspose.cells/exporttableoptions/rename_strategy) | Стратегия дублирования названий столбцов.|


###  Методы
| Метод| Описание|
| :- | :- |
| [preprocess_exported_value](/cells/python-net/ru/aspose.cells/exporttableoptions/preprocess_exported_value/#int-int-aspose.cells.CellValue) | Предварительно обработайте значение текущей ячейки для экспорта.|



###  Примечания

Если есть какие-то особые требования к экспорту, например, игнорирование значений ошибок, пользователь может расширить этот класс.
перезаписать соответствующие API для достижения цели.

###  Смотрите также
* модуль [`aspose.cells`](..)
