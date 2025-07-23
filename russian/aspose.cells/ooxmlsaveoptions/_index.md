---
title: OoxmlSaveOptions класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 1050
url: /ru/aspose.cells/ooxmlsaveoptions/
is_root: false
---
##  OoxmlSaveOptions класс
Представляет варианты сохранения файла Office Open XML.



**Наследование:** [`OoxmlSaveOptions`](/cells/python-net/aspose.cells/ooxmlsaveoptions) → 
[`SaveOptions`](/cells/python-net/ru/aspose.cells/saveoptions)



Тип OoxmlSaveOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells/ooxmlsaveoptions/__init__/#) | Создает параметры сохранения файла Office Open XML.|
| [`__init__(self, save_format)`](/cells/python-net/ru/aspose.cells/ooxmlsaveoptions/__init__/#aspose.cells.saveformat) | Создает параметры сохранения файла Office Open XML.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [save_format](/cells/python-net/ru/aspose.cells/ooxmlsaveoptions/save_format) | Получает формат сохраняемого файла.|
| [clear_data](/cells/python-net/ru/aspose.cells/ooxmlsaveoptions/clear_data) | После сохранения файла сделайте книгу пустой.|
| [cached_file_folder](/cells/python-net/ru/aspose.cells/ooxmlsaveoptions/cached_file_folder) | Папка для временных файлов, которые могут использоваться в качестве кэша данных.|
| [validate_merged_areas](/cells/python-net/ru/aspose.cells/ooxmlsaveoptions/validate_merged_areas) | Указывает, следует ли проверять объединенные ячейки перед сохранением файла.|
| [merge_areas](/cells/python-net/ru/aspose.cells/ooxmlsaveoptions/merge_areas) | Указывает, следует ли объединять области условного форматирования и проверки перед сохранением файла.|
| [create_directory](/cells/python-net/ru/aspose.cells/ooxmlsaveoptions/create_directory) | Если значение true и каталог не существует, каталог будет автоматически создан перед сохранением файла.|
| [sort_names](/cells/python-net/ru/aspose.cells/ooxmlsaveoptions/sort_names) |Указывает, сортируются ли определенные имена перед сохранением файла.|
| [sort_external_names](/cells/python-net/ru/aspose.cells/ooxmlsaveoptions/sort_external_names) | Указывает, следует ли сортировать внешние определенные имена перед сохранением файла.|
| [refresh_chart_cache](/cells/python-net/ru/aspose.cells/ooxmlsaveoptions/refresh_chart_cache) | Указывает, обновляются ли данные кэша диаграммы|
| [check_excel_restriction](/cells/python-net/ru/aspose.cells/ooxmlsaveoptions/check_excel_restriction) | Проверять ли ограничения файла Excel, когда пользователь изменяет ячейки, связанные с объектами.<br/>Например, Excel не позволяет вводить строковое значение длиной более 32К.<br/> При вводе значения длиннее 32 КБ оно будет усечено.|
| [update_smart_art](/cells/python-net/ru/aspose.cells/ooxmlsaveoptions/update_smart_art) | Указывает, обновляются ли настройки смарт-арта.<br/> Значение по умолчанию — false.|
| [encrypt_document_properties](/cells/python-net/ru/aspose.cells/ooxmlsaveoptions/encrypt_document_properties) | Указывает, шифровать ли свойства документа при сохранении в формате .xls.<br/> Значение по умолчанию — true.|
| [export_cell_name](/cells/python-net/ru/aspose.cells/ooxmlsaveoptions/export_cell_name) | Указывает, следует ли экспортировать имя ячейки в файл Excel2007 .xlsx (.xlsm, .xltx, .xltm).<br/>Если к выходному файлу может получить доступ SQL Server DTS, это значение должно быть истинным.<br/>Установка значения false значительно увеличит производительность и уменьшит размер файла при создании больших файлов.<br/> Значение по умолчанию — true.|
| [update_zoom](/cells/python-net/ru/aspose.cells/ooxmlsaveoptions/update_zoom) | Указывает, следует ли обновлять коэффициент масштабирования перед сохранением файла.<br/> если свойства PageSetup.FitToPagesWide и PageSetup.FitToPagesTall управляют масштабированием листа.|
| [enable_zip64](/cells/python-net/ru/aspose.cells/ooxmlsaveoptions/enable_zip64) | Всегда используйте расширения ZIP64 при создании ZIP-архивов, даже если в этом нет необходимости.|
| [embed_ooxml_as_ole_object](/cells/python-net/ru/aspose.cells/ooxmlsaveoptions/embed_ooxml_as_ole_object) | Указывает, следует ли встраивать файлы Ooxml OleObject как объект ole.|
| [compression_type](/cells/python-net/ru/aspose.cells/ooxmlsaveoptions/compression_type) | Получает и задает тип сжатия для файла ooxml.|
| [wps_compatibility](/cells/python-net/ru/aspose.cells/ooxmlsaveoptions/wps_compatibility) | Указывает, следует ли сделать xls более совместимым с WPS.|



###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`OoxmlSaveOptions`](/cells/python-net/ru/aspose.cells/ooxmlsaveoptions)
* класс [`SaveOptions`](/cells/python-net/ru/aspose.cells/saveoptions)
