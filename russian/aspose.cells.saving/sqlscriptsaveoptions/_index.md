---
title: SqlScriptSaveOptions класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 40
url: /ru/aspose.cells.saving/sqlscriptsaveoptions/
is_root: false
---
##  SqlScriptSaveOptions класс
Представляет варианты сохранения sql.



**Наследование:** [`SqlScriptSaveOptions`](/cells/python-net/aspose.cells.saving/sqlscriptsaveoptions) → 
[`SaveOptions`](/cells/python-net/ru/aspose.cells/saveoptions)



Тип SqlScriptSaveOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/__init__/#) | Создает параметры для сохранения SQL-файла.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [save_format](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/save_format) | Получает формат сохраняемого файла.|
| [clear_data](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/clear_data) | После сохранения файла сделайте книгу пустой.|
| [cached_file_folder](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/cached_file_folder) | Папка для временных файлов, которые могут использоваться в качестве кэша данных.|
| [validate_merged_areas](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/validate_merged_areas) | Указывает, следует ли проверять объединенные ячейки перед сохранением файла.|
| [merge_areas](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/merge_areas) | Указывает, следует ли объединять области условного форматирования и проверки перед сохранением файла.|
| [create_directory](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/create_directory) | Если значение true и каталог не существует, каталог будет автоматически создан перед сохранением файла.|
| [sort_names](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/sort_names) |Указывает, сортируются ли определенные имена перед сохранением файла.|
| [sort_external_names](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/sort_external_names) | Указывает, следует ли сортировать внешние определенные имена перед сохранением файла.|
| [refresh_chart_cache](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/refresh_chart_cache) | Указывает, обновляются ли данные кэша диаграммы|
| [check_excel_restriction](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/check_excel_restriction) | Проверять ли ограничения файла Excel, когда пользователь изменяет ячейки, связанные с объектами.<br/>Например, Excel не позволяет вводить строковое значение длиной более 32К.<br/> При вводе значения длиннее 32 КБ оно будет усечено.|
| [update_smart_art](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/update_smart_art) | Указывает, обновляются ли настройки смарт-арта.<br/> Значение по умолчанию — false.|
| [encrypt_document_properties](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/encrypt_document_properties) | Указывает, шифровать ли свойства документа при сохранении в формате .xls.<br/> Значение по умолчанию — true.|
| [check_if_table_exists](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/check_if_table_exists) | Перед созданием проверьте, существует ли имя таблицы.|
| [column_type_map](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/column_type_map) | Получает и задает карту типов столбцов для разных баз данных.|
| [check_all_data_for_column_type](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/check_all_data_for_column_type) | Проверьте все данные, чтобы определить тип данных столбцов.|
| [add_blank_line_between_rows](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/add_blank_line_between_rows) | Вставляйте пустую строку между каждыми данными.|
| [separator](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/separator) | Получает и задает разделитель символов в скрипте SQL.|
| [operator_type](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/operator_type) | Получает и задает тип оператора sql.|
| [primary_key](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/primary_key) | Указывает, какой столбец является первичным ключом таблицы данных.|
| [create_table](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/create_table) | Указывает, экспортируется ли SQL-код создания таблицы.|
| [id_name](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/id_name) | Получает и задает имя столбца идентификатора.|
| [start_id](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/start_id) | Получает и задает начальный идентификатор.|
| [table_name](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/table_name) | Получает и задает имя таблицы.|
| [export_as_string](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/export_as_string) | Указывает, экспортируются ли все данные как строковое значение.|
| [sheet_indexes](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/sheet_indexes) |Представляет индексы экспортированных листов.|
| [export_area](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/export_area) | Получает или задает диапазон экспорта.|
| [has_header_row](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions/has_header_row) | Указывает, содержит ли диапазон строку заголовка.|



###  Смотрите также
* модуль [`aspose.cells.saving`](..)
* класс [`SaveOptions`](/cells/python-net/ru/aspose.cells/saveoptions)
* класс [`SqlScriptSaveOptions`](/cells/python-net/ru/aspose.cells.saving/sqlscriptsaveoptions)
