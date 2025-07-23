---
title: ImageSaveOptions класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 860
url: /ru/aspose.cells/imagesaveoptions/
is_root: false
---
##  ImageSaveOptions класс
Представляет параметры сохранения изображения.
Для расширенного использования используйте [`WorkbookRender`](/cells/python-net/ru/aspose.cells.rendering/workbookrender) или [`SheetRender`](/cells/python-net/ru/aspose.cells.rendering/sheetrender).



**Наследование:** [`ImageSaveOptions`](/cells/python-net/aspose.cells/imagesaveoptions) → 
[`SaveOptions`](/cells/python-net/ru/aspose.cells/saveoptions)



Тип ImageSaveOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells/imagesaveoptions/__init__/#) | Создает параметры сохранения файла изображения.|
| [`__init__(self, save_format)`](/cells/python-net/ru/aspose.cells/imagesaveoptions/__init__/#aspose.cells.saveformat) | Создает параметры сохранения файла изображения.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [save_format](/cells/python-net/ru/aspose.cells/imagesaveoptions/save_format) | Получает формат сохраняемого файла.|
| [clear_data](/cells/python-net/ru/aspose.cells/imagesaveoptions/clear_data) | После сохранения файла сделайте книгу пустой.|
| [cached_file_folder](/cells/python-net/ru/aspose.cells/imagesaveoptions/cached_file_folder) | Папка для временных файлов, которые могут использоваться в качестве кэша данных.|
| [validate_merged_areas](/cells/python-net/ru/aspose.cells/imagesaveoptions/validate_merged_areas) | Указывает, следует ли проверять объединенные ячейки перед сохранением файла.|
| [merge_areas](/cells/python-net/ru/aspose.cells/imagesaveoptions/merge_areas) | Указывает, следует ли объединять области условного форматирования и проверки перед сохранением файла.|
| [create_directory](/cells/python-net/ru/aspose.cells/imagesaveoptions/create_directory) | Если значение true и каталог не существует, каталог будет автоматически создан перед сохранением файла.|
| [sort_names](/cells/python-net/ru/aspose.cells/imagesaveoptions/sort_names) |Указывает, сортируются ли определенные имена перед сохранением файла.|
| [sort_external_names](/cells/python-net/ru/aspose.cells/imagesaveoptions/sort_external_names) | Указывает, следует ли сортировать внешние определенные имена перед сохранением файла.|
| [refresh_chart_cache](/cells/python-net/ru/aspose.cells/imagesaveoptions/refresh_chart_cache) | Указывает, обновляются ли данные кэша диаграммы|
| [check_excel_restriction](/cells/python-net/ru/aspose.cells/imagesaveoptions/check_excel_restriction) | Проверять ли ограничения файла Excel, когда пользователь изменяет ячейки, связанные с объектами.<br/>Например, Excel не позволяет вводить строковое значение длиной более 32К.<br/> При вводе значения длиннее 32 КБ оно будет усечено.|
| [update_smart_art](/cells/python-net/ru/aspose.cells/imagesaveoptions/update_smart_art) | Указывает, обновляются ли настройки смарт-арта.<br/> Значение по умолчанию — false.|
| [encrypt_document_properties](/cells/python-net/ru/aspose.cells/imagesaveoptions/encrypt_document_properties) | Указывает, шифровать ли свойства документа при сохранении в формате .xls.<br/> Значение по умолчанию — true.|
| [image_or_print_options](/cells/python-net/ru/aspose.cells/imagesaveoptions/image_or_print_options) | Дополнительные возможности создания изображений.|



###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`ImageSaveOptions`](/cells/python-net/ru/aspose.cells/imagesaveoptions)
* класс [`SaveOptions`](/cells/python-net/ru/aspose.cells/saveoptions)
* класс [`SheetRender`](/cells/python-net/ru/aspose.cells.rendering/sheetrender)
* класс [`WorkbookRender`](/cells/python-net/ru/aspose.cells.rendering/workbookrender)
