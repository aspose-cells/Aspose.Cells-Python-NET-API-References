---
title: JsonSaveOptions класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 920
url: /ru/aspose.cells/jsonsaveoptions/
is_root: false
---
##  JsonSaveOptions класс
Представляет варианты сохранения рабочей книги в виде файла JSON.



**Наследование:** [`JsonSaveOptions`](/cells/python-net/aspose.cells/jsonsaveoptions) → 
[`SaveOptions`](/cells/python-net/ru/aspose.cells/saveoptions)



Тип JsonSaveOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells/jsonsaveoptions/__init__/#) | Создает параметры для сохранения файла JSON.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [save_format](/cells/python-net/ru/aspose.cells/jsonsaveoptions/save_format) | Получает формат сохраняемого файла.|
| [clear_data](/cells/python-net/ru/aspose.cells/jsonsaveoptions/clear_data) | После сохранения файла сделайте книгу пустой.|
| [cached_file_folder](/cells/python-net/ru/aspose.cells/jsonsaveoptions/cached_file_folder) | Папка для временных файлов, которые могут использоваться в качестве кэша данных.|
| [validate_merged_areas](/cells/python-net/ru/aspose.cells/jsonsaveoptions/validate_merged_areas) | Указывает, следует ли проверять объединенные ячейки перед сохранением файла.|
| [merge_areas](/cells/python-net/ru/aspose.cells/jsonsaveoptions/merge_areas) | Указывает, следует ли объединять области условного форматирования и проверки перед сохранением файла.|
| [create_directory](/cells/python-net/ru/aspose.cells/jsonsaveoptions/create_directory) | Если значение true и каталог не существует, каталог будет автоматически создан перед сохранением файла.|
| [sort_names](/cells/python-net/ru/aspose.cells/jsonsaveoptions/sort_names) |Указывает, сортируются ли определенные имена перед сохранением файла.|
| [sort_external_names](/cells/python-net/ru/aspose.cells/jsonsaveoptions/sort_external_names) | Указывает, следует ли сортировать внешние определенные имена перед сохранением файла.|
| [refresh_chart_cache](/cells/python-net/ru/aspose.cells/jsonsaveoptions/refresh_chart_cache) | Указывает, обновляются ли данные кэша диаграммы|
| [check_excel_restriction](/cells/python-net/ru/aspose.cells/jsonsaveoptions/check_excel_restriction) | Проверять ли ограничения файла Excel, когда пользователь изменяет ячейки, связанные с объектами.<br/>Например, Excel не позволяет вводить строковое значение длиной более 32К.<br/> При вводе значения длиннее 32 КБ оно будет усечено.|
| [update_smart_art](/cells/python-net/ru/aspose.cells/jsonsaveoptions/update_smart_art) | Указывает, обновляются ли настройки смарт-арта.<br/> Значение по умолчанию — false.|
| [encrypt_document_properties](/cells/python-net/ru/aspose.cells/jsonsaveoptions/encrypt_document_properties) | Указывает, шифровать ли свойства документа при сохранении в формате .xls.<br/> Значение по умолчанию — true.|
| [export_style_pool](/cells/python-net/ru/aspose.cells/jsonsaveoptions/export_style_pool) | Указывает, следует ли экспортировать стили коллективно или по отдельности в каждую ячейку.|
| [export_hyperlink_type](/cells/python-net/ru/aspose.cells/jsonsaveoptions/export_hyperlink_type) | Представляет тип экспорта гиперссылки в JSON.|
| [skip_empty_rows](/cells/python-net/ru/aspose.cells/jsonsaveoptions/skip_empty_rows) | Указывает, следует ли пропускать пустые строки.|
| [sheet_indexes](/cells/python-net/ru/aspose.cells/jsonsaveoptions/sheet_indexes) |Представляет индексы экспортированных листов.|
| [schemas](/cells/python-net/ru/aspose.cells/jsonsaveoptions/schemas) | Исходная схема JSON каждого рабочего листа.|
| [export_area](/cells/python-net/ru/aspose.cells/jsonsaveoptions/export_area) | Получает или задает диапазон экспорта.|
| [has_header_row](/cells/python-net/ru/aspose.cells/jsonsaveoptions/has_header_row) | Указывает, содержит ли диапазон строку заголовка.|
| [export_as_string](/cells/python-net/ru/aspose.cells/jsonsaveoptions/export_as_string) | Экспортирует строковое значение ячеек в JSON.|
| [indent](/cells/python-net/ru/aspose.cells/jsonsaveoptions/indent) | Указывает отступ.|
| [export_nested_structure](/cells/python-net/ru/aspose.cells/jsonsaveoptions/export_nested_structure) | Экспортируется как структура Json иерархии «родители-потомки».|
| [export_empty_cells](/cells/python-net/ru/aspose.cells/jsonsaveoptions/export_empty_cells) | Указывает, следует ли экспортировать пустые ячейки как NULL.|
| [always_export_as_json_object](/cells/python-net/ru/aspose.cells/jsonsaveoptions/always_export_as_json_object) | Указывает, всегда ли экспортировать Excel в JSON как объект, даже если в файле есть только один рабочий лист.|
| [to_excel_struct](/cells/python-net/ru/aspose.cells/jsonsaveoptions/to_excel_struct) | Указывает, выполняется ли преобразование в структуру JSON файла Excel.|



###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`JsonSaveOptions`](/cells/python-net/ru/aspose.cells/jsonsaveoptions)
* класс [`SaveOptions`](/cells/python-net/ru/aspose.cells/saveoptions)
