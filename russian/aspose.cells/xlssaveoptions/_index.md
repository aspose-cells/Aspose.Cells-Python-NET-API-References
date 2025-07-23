---
title: XlsSaveOptions класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 1630
url: /ru/aspose.cells/xlssaveoptions/
is_root: false
---
##  XlsSaveOptions класс
Представляет параметры сохранения для формата файла Excel 97-2003: xls и xlt.



**Наследование:** [`XlsSaveOptions`](/cells/python-net/aspose.cells/xlssaveoptions) → 
[`SaveOptions`](/cells/python-net/ru/aspose.cells/saveoptions)



Тип XlsSaveOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells/xlssaveoptions/__init__/#) | Создает параметры для сохранения xls-файла Excel 97-2003.|
| [`__init__(self, save_format)`](/cells/python-net/ru/aspose.cells/xlssaveoptions/__init__/#aspose.cells.saveformat) | Создает параметры для сохранения файла Excel 97-2003 xls/xlt.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [save_format](/cells/python-net/ru/aspose.cells/xlssaveoptions/save_format) | Получает формат сохраняемого файла.|
| [clear_data](/cells/python-net/ru/aspose.cells/xlssaveoptions/clear_data) | После сохранения файла сделайте книгу пустой.|
| [cached_file_folder](/cells/python-net/ru/aspose.cells/xlssaveoptions/cached_file_folder) | Папка для временных файлов, которые могут использоваться в качестве кэша данных.|
| [validate_merged_areas](/cells/python-net/ru/aspose.cells/xlssaveoptions/validate_merged_areas) | Указывает, следует ли проверять объединенные ячейки перед сохранением файла.|
| [merge_areas](/cells/python-net/ru/aspose.cells/xlssaveoptions/merge_areas) | Указывает, следует ли объединять области условного форматирования и проверки перед сохранением файла.|
| [create_directory](/cells/python-net/ru/aspose.cells/xlssaveoptions/create_directory) | Если значение true и каталог не существует, каталог будет автоматически создан перед сохранением файла.|
| [sort_names](/cells/python-net/ru/aspose.cells/xlssaveoptions/sort_names) |Указывает, сортируются ли определенные имена перед сохранением файла.|
| [sort_external_names](/cells/python-net/ru/aspose.cells/xlssaveoptions/sort_external_names) | Указывает, следует ли сортировать внешние определенные имена перед сохранением файла.|
| [refresh_chart_cache](/cells/python-net/ru/aspose.cells/xlssaveoptions/refresh_chart_cache) | Указывает, обновляются ли данные кэша диаграммы|
| [check_excel_restriction](/cells/python-net/ru/aspose.cells/xlssaveoptions/check_excel_restriction) | Проверять ли ограничения файла Excel, когда пользователь изменяет ячейки, связанные с объектами.<br/>Например, Excel не позволяет вводить строковое значение длиной более 32К.<br/> При вводе значения длиннее 32 КБ оно будет усечено.|
| [update_smart_art](/cells/python-net/ru/aspose.cells/xlssaveoptions/update_smart_art) | Указывает, обновляются ли настройки смарт-арта.<br/> Значение по умолчанию — false.|
| [encrypt_document_properties](/cells/python-net/ru/aspose.cells/xlssaveoptions/encrypt_document_properties) | Указывает, шифровать ли свойства документа при сохранении в формате .xls.<br/> Значение по умолчанию — true.|
| [is_template](/cells/python-net/ru/aspose.cells/xlssaveoptions/is_template) | Указывает, сохраняется ли файл шаблона.|
| [match_color](/cells/python-net/ru/aspose.cells/xlssaveoptions/match_color) | Указывает, соответствует ли цвет шрифта, поскольку в стандартной цветовой палитре 56 цветов.|
| [wps_compatibility](/cells/python-net/ru/aspose.cells/xlssaveoptions/wps_compatibility) | Указывает, следует ли сделать xls более совместимым с WPS.|



###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`SaveOptions`](/cells/python-net/ru/aspose.cells/saveoptions)
* класс [`XlsSaveOptions`](/cells/python-net/ru/aspose.cells/xlssaveoptions)
