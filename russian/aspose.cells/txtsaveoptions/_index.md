---
title: TxtSaveOptions класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 1500
url: /ru/aspose.cells/txtsaveoptions/
is_root: false
---
##  TxtSaveOptions класс
Представляет параметры сохранения для формата CSV/разделителя табуляции/другого текстового формата.



**Наследование:** [`TxtSaveOptions`](/cells/python-net/aspose.cells/txtsaveoptions) → 
[`SaveOptions`](/cells/python-net/ru/aspose.cells/saveoptions)



Тип TxtSaveOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells/txtsaveoptions/__init__/#) | Создает параметры сохранения текстового файла.|
| [`__init__(self, save_format)`](/cells/python-net/ru/aspose.cells/txtsaveoptions/__init__/#aspose.cells.saveformat) | Создает параметры сохранения текстового файла.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [save_format](/cells/python-net/ru/aspose.cells/txtsaveoptions/save_format) | Получает формат сохраняемого файла.|
| [clear_data](/cells/python-net/ru/aspose.cells/txtsaveoptions/clear_data) | После сохранения файла сделайте книгу пустой.|
| [cached_file_folder](/cells/python-net/ru/aspose.cells/txtsaveoptions/cached_file_folder) | Папка для временных файлов, которые могут использоваться в качестве кэша данных.|
| [validate_merged_areas](/cells/python-net/ru/aspose.cells/txtsaveoptions/validate_merged_areas) | Указывает, следует ли проверять объединенные ячейки перед сохранением файла.|
| [merge_areas](/cells/python-net/ru/aspose.cells/txtsaveoptions/merge_areas) | Указывает, следует ли объединять области условного форматирования и проверки перед сохранением файла.|
| [create_directory](/cells/python-net/ru/aspose.cells/txtsaveoptions/create_directory) | Если значение true и каталог не существует, каталог будет автоматически создан перед сохранением файла.|
| [sort_names](/cells/python-net/ru/aspose.cells/txtsaveoptions/sort_names) |Указывает, сортируются ли определенные имена перед сохранением файла.|
| [sort_external_names](/cells/python-net/ru/aspose.cells/txtsaveoptions/sort_external_names) | Указывает, следует ли сортировать внешние определенные имена перед сохранением файла.|
| [refresh_chart_cache](/cells/python-net/ru/aspose.cells/txtsaveoptions/refresh_chart_cache) | Указывает, обновляются ли данные кэша диаграммы|
| [check_excel_restriction](/cells/python-net/ru/aspose.cells/txtsaveoptions/check_excel_restriction) | Проверять ли ограничения файла Excel, когда пользователь изменяет ячейки, связанные с объектами.<br/>Например, Excel не позволяет вводить строковое значение длиной более 32К.<br/> При вводе значения длиннее 32 КБ оно будет усечено.|
| [update_smart_art](/cells/python-net/ru/aspose.cells/txtsaveoptions/update_smart_art) | Указывает, обновляются ли настройки смарт-арта.<br/> Значение по умолчанию — false.|
| [encrypt_document_properties](/cells/python-net/ru/aspose.cells/txtsaveoptions/encrypt_document_properties) | Указывает, шифровать ли свойства документа при сохранении в формате .xls.<br/> Значение по умолчанию — true.|
| [separator](/cells/python-net/ru/aspose.cells/txtsaveoptions/separator) | Получает и задает символьный разделитель текстового файла.|
| [separator_string](/cells/python-net/ru/aspose.cells/txtsaveoptions/separator_string) | Получает и задает строковое значение в качестве разделителя.|
| [encoding](/cells/python-net/ru/aspose.cells/txtsaveoptions/encoding) | Получает и задает кодировку по умолчанию.|
| [always_quoted](/cells/python-net/ru/aspose.cells/txtsaveoptions/always_quoted) | Указывает, следует ли всегда добавлять '"' для каждого поля.<br/>Если true, то все значения будут заключены в кавычки;<br/>Если false, то значения будут заключаться в кавычки только при необходимости (например,<br/>когда значения содержат специальные символы, такие как '"' , '\n' или символ разделителя).<br/> Значение по умолчанию — false.|
| [quote_type](/cells/python-net/ru/aspose.cells/txtsaveoptions/quote_type) |Возвращает или задает способ заключения значений в кавычки в экспортированном текстовом файле.|
| [format_strategy](/cells/python-net/ru/aspose.cells/txtsaveoptions/format_strategy) | Возвращает и задает стратегию форматирования при экспорте значения ячейки в виде строки.|
| [trim_leading_blank_row_and_column](/cells/python-net/ru/aspose.cells/txtsaveoptions/trim_leading_blank_row_and_column) | Указывает, следует ли обрезать начальные пустые строки и столбцы, как это делает MS Excel.<br/> Значение по умолчанию — true.|
| [trim_tailing_blank_cells](/cells/python-net/ru/aspose.cells/txtsaveoptions/trim_tailing_blank_cells) | Указывает, следует ли обрезать пустые ячейки в конце одной строки. Значение по умолчанию — false.|
| [keep_separators_for_blank_row](/cells/python-net/ru/aspose.cells/txtsaveoptions/keep_separators_for_blank_row) | Указывает, следует ли выводить разделители для пустой строки.<br/> Значение по умолчанию — false, поэтому по умолчанию содержимое пустой строки будет пустым.|
| [export_area](/cells/python-net/ru/aspose.cells/txtsaveoptions/export_area) | Диапазон экспортируемых ячеек.|
| [export_quote_prefix](/cells/python-net/ru/aspose.cells/txtsaveoptions/export_quote_prefix) | Указывает, следует ли экспортировать знак одинарной кавычки как часть значения одной ячейки.<br/> когда для него задано значение [`Style.quote_prefix`](/cells/python-net/ru/aspose.cells/style#quote_prefix). Значение по умолчанию — false.|
| [export_all_sheets](/cells/python-net/ru/aspose.cells/txtsaveoptions/export_all_sheets) | Указывает, следует ли экспортировать все листы в текстовый файл.<br/> Если значение равно false, экспортировать только активный лист, как в MS Excel.|



###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`SaveOptions`](/cells/python-net/ru/aspose.cells/saveoptions)
* класс [`TxtSaveOptions`](/cells/python-net/ru/aspose.cells/txtsaveoptions)
