---
title: TxtSaveOptions класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 1590
url: /ru/aspose.cells/txtsaveoptions/
is_root: false
---
##  TxtSaveOptions класс
Представляет параметры сохранения для формата csv/с разделителями табуляции/другого текстового формата.



**Наследование:** [`TxtSaveOptions`](/cells/python-net/aspose.cells/txtsaveoptions) → 
[`SaveOptions`](/cells/python-net/ru/aspose.cells/saveoptions)



Тип TxtSaveOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [__init__](/cells/python-net/ru/aspose.cells/txtsaveoptions/__init__/#) | Создает параметры сохранения текстового файла.|
| [__init__](/cells/python-net/ru/aspose.cells/txtsaveoptions/__init__/#aspose.cells.SaveFormat) | Создает параметры сохранения текстового файла.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [save_format](/cells/python-net/ru/aspose.cells/txtsaveoptions/save_format) | Получает формат файла сохранения.|
| [clear_data](/cells/python-net/ru/aspose.cells/txtsaveoptions/clear_data) | Сделайте книгу пустой после сохранения файла.|
| [cached_file_folder](/cells/python-net/ru/aspose.cells/txtsaveoptions/cached_file_folder) | Папка с кэшированными файлами используется для хранения больших данных.|
| [validate_merged_areas](/cells/python-net/ru/aspose.cells/txtsaveoptions/validate_merged_areas) | Указывает, следует ли проверять объединенные ячейки перед сохранением файла.|
| [merge_areas](/cells/python-net/ru/aspose.cells/txtsaveoptions/merge_areas) | Указывает, нужно ли объединять области условного форматирования и проверки перед сохранением файла.|
| [create_directory](/cells/python-net/ru/aspose.cells/txtsaveoptions/create_directory) | Если это правда и каталог не существует, каталог будет автоматически создан перед сохранением файла.|
| [sort_names](/cells/python-net/ru/aspose.cells/txtsaveoptions/sort_names) | Указывает, выполняется ли сортировка определенных имен перед сохранением файла.|
| [sort_external_names](/cells/python-net/ru/aspose.cells/txtsaveoptions/sort_external_names) | Указывает, следует ли сортировать внешние определенные имена перед сохранением файла.|
| [refresh_chart_cache](/cells/python-net/ru/aspose.cells/txtsaveoptions/refresh_chart_cache) | Указывает, обновляются ли данные кэша диаграммы.|
| [warning_callback](/cells/python-net/ru/aspose.cells/txtsaveoptions/warning_callback) | Получает или задает обратный вызов с предупреждением.|
| [update_smart_art](/cells/python-net/ru/aspose.cells/txtsaveoptions/update_smart_art) | Указывает, обновляются ли настройки Smart Art.<br/> Значение по умолчанию неверно.|
| [separator](/cells/python-net/ru/aspose.cells/txtsaveoptions/separator) | Получает и устанавливает символьный разделитель текстового файла.|
| [separator_string](/cells/python-net/ru/aspose.cells/txtsaveoptions/separator_string) | Получает и устанавливает строковое значение в качестве разделителя.|
| [encoding](/cells/python-net/ru/aspose.cells/txtsaveoptions/encoding) | Получает и задает кодировку по умолчанию.|
| [always_quoted](/cells/python-net/ru/aspose.cells/txtsaveoptions/always_quoted) | Указывает, всегда ли добавляется «» для каждого поля.<br/>Если это правда, то все значения будут заключены в кавычки;<br/>Если false, то значения будут заключаться в кавычки только при необходимости (например,<br/>когда значения содержат специальные символы, такие как '"' , '\n' или символ-разделитель).<br/> По умолчанию — ложь.|
| [quote_type](/cells/python-net/ru/aspose.cells/txtsaveoptions/quote_type) | Получает или задает способ заключения значений в кавычки в экспортированном текстовом файле.|
| [format_strategy](/cells/python-net/ru/aspose.cells/txtsaveoptions/format_strategy) | Получает и задает стратегию форматирования при экспорте значения ячейки в виде строки.|
| [light_cells_data_provider](/cells/python-net/ru/aspose.cells/txtsaveoptions/light_cells_data_provider) | Поставщик данных для сохранения книги в облегченном режиме.|
| [trim_leading_blank_row_and_column](/cells/python-net/ru/aspose.cells/txtsaveoptions/trim_leading_blank_row_and_column) | Указывает, следует ли обрезать ведущие пустые строки и столбцы, как это делает MS Excel.<br/> По умолчанию верно.|
| [trim_tailing_blank_cells](/cells/python-net/ru/aspose.cells/txtsaveoptions/trim_tailing_blank_cells) | Указывает, следует ли обрезать оставшиеся пустые ячейки в одной строке. По умолчанию — ложь.|
| [keep_separators_for_blank_row](/cells/python-net/ru/aspose.cells/txtsaveoptions/keep_separators_for_blank_row) |Указывает, должны ли выводиться разделители для пустой строки.<br/> Значение по умолчанию — false, поэтому по умолчанию содержимое пустой строки будет пустым.|
| [export_area](/cells/python-net/ru/aspose.cells/txtsaveoptions/export_area) | Диапазон ячеек, подлежащих экспорту.|
| [export_quote_prefix](/cells/python-net/ru/aspose.cells/txtsaveoptions/export_quote_prefix) | Указывает, следует ли экспортировать знак одинарной кавычки как часть значения одной ячейки.<br/> когда для него верно [`Style.quote_prefix`](/cells/python-net/ru/aspose.cells/style#quote_prefix). По умолчанию — ложь.|
| [export_all_sheets](/cells/python-net/ru/aspose.cells/txtsaveoptions/export_all_sheets) | Указывает, экспортируются ли все листы в текстовый файл.<br/> Если это ложь, экспортируйте только активный лист, как в MS Excel.|



###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`SaveOptions`](/cells/python-net/ru/aspose.cells/saveoptions)
* класс [`TxtSaveOptions`](/cells/python-net/ru/aspose.cells/txtsaveoptions)
