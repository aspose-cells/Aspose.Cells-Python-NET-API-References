---
title: TxtSaveOptions класс
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 1520
url: /ru/aspose.cells/txtsaveoptions/
is_root: false
---
##  TxtSaveOptions класс
Представляет параметры сохранения для CSV/разделителей табуляции/другого текстового формата.



**Наследование:** [TxtSaveOptions](/cells/python-net/aspose.cells/txtsaveoptions) → 
[SaveOptions](/cells/python-net/ru/aspose.cells/saveoptions)



Тип TxtSaveOptions предоставляет следующие члены:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [TxtSaveOptions()](/cells/python-net/ru/aspose.cells/txtsaveoptions/__init__/#) | Создает параметры сохранения текстового файла.|
| [TxtSaveOptions(format)](/cells/python-net/ru/aspose.cells/txtsaveoptions/__init__/#SaveFormat) | Создает параметры сохранения текстового файла.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [save_format](/cells/python-net/ru/aspose.cells/txtsaveoptions/save_format) | Получает формат файла сохранения.|
| [clear_data](/cells/python-net/ru/aspose.cells/txtsaveoptions/clear_data) | Сделайте рабочую книгу пустой после сохранения файла.|
| [cached_file_folder](/cells/python-net/ru/aspose.cells/txtsaveoptions/cached_file_folder) | Папка с кэшированными файлами используется для хранения больших данных.|
| [validate_merged_areas](/cells/python-net/ru/aspose.cells/txtsaveoptions/validate_merged_areas) | Указывает, следует ли проверять объединенные ячейки перед сохранением файла.|
| [merge_areas](/cells/python-net/ru/aspose.cells/txtsaveoptions/merge_areas) | Указывает, объединяются ли области условного форматирования и проверки перед сохранением файла.|
| [create_directory](/cells/python-net/ru/aspose.cells/txtsaveoptions/create_directory) | Если true и каталог не существует, каталог будет автоматически создан перед сохранением файла.|
| [sort_names](/cells/python-net/ru/aspose.cells/txtsaveoptions/sort_names) | Указывает, выполняется ли сортировка определенных имен перед сохранением файла.|
| [sort_external_names](/cells/python-net/ru/aspose.cells/txtsaveoptions/sort_external_names) |Указывает, выполняется ли сортировка внешних определенных имен перед сохранением файла.|
| [refresh_chart_cache](/cells/python-net/ru/aspose.cells/txtsaveoptions/refresh_chart_cache) | Указывает, обновляются ли данные кэша диаграммы.|
| [warning_callback](/cells/python-net/ru/aspose.cells/txtsaveoptions/warning_callback) | Получает или задает обратный вызов предупреждения.|
| [update_smart_art](/cells/python-net/ru/aspose.cells/txtsaveoptions/update_smart_art) | Указывает, обновляются ли настройки смарт-арта.<br/> Значение по умолчанию неверно.|
| [separator](/cells/python-net/ru/aspose.cells/txtsaveoptions/separator) | Получает и устанавливает символьный разделитель текстового файла.|
| [separator_string](/cells/python-net/ru/aspose.cells/txtsaveoptions/separator_string) | Получает и задает строковое значение в качестве разделителя.|
| [encoding](/cells/python-net/ru/aspose.cells/txtsaveoptions/encoding) | Получает и задает кодировку по умолчанию.|
| [always_quoted](/cells/python-net/ru/aspose.cells/txtsaveoptions/always_quoted) | Указывает, всегда ли добавляется '"' для каждого поля.<br/>Если true, то все значения будут заключены в кавычки;<br/>Если false, то значения будут заключаться в кавычки только при необходимости (например,<br/>когда значения содержат специальные символы, такие как '"' , '\n' или символ-разделитель).<br/> Значение по умолчанию — ложь.|
| [quote_type](/cells/python-net/ru/aspose.cells/txtsaveoptions/quote_type) | Получает или задает, как заключать в кавычки значения в экспортированном текстовом файле.|
| [format_strategy](/cells/python-net/ru/aspose.cells/txtsaveoptions/format_strategy) | Получает и задает стратегию форматирования при экспорте значения ячейки в виде строки.|
| [light_cells_data_provider](/cells/python-net/ru/aspose.cells/txtsaveoptions/light_cells_data_provider) | Поставщик данных для предоставления данных ячеек для сохранения книги в облегченном режиме.|
| [trim_leading_blank_row_and_column](/cells/python-net/ru/aspose.cells/txtsaveoptions/trim_leading_blank_row_and_column) | Указывает, следует ли обрезать ведущие пустые строки и столбцы, как это делает MS Excel.<br/> Значение по умолчанию верно.|
| [trim_tailing_blank_cells](/cells/python-net/ru/aspose.cells/txtsaveoptions/trim_tailing_blank_cells) | Указывает, следует ли обрезать хвостовые пустые ячейки в одной строке. Значение по умолчанию — ложь.|
| [keep_separators_for_blank_row](/cells/python-net/ru/aspose.cells/txtsaveoptions/keep_separators_for_blank_row) | Указывает, следует ли выводить разделители для пустой строки.<br/> Значение по умолчанию — false, поэтому по умолчанию содержимое пустой строки будет пустым.|
| [export_area](/cells/python-net/ru/aspose.cells/txtsaveoptions/export_area) | Диапазон экспортируемых ячеек.|
| [export_quote_prefix](/cells/python-net/ru/aspose.cells/txtsaveoptions/export_quote_prefix) | Указывает, следует ли экспортировать одинарную кавычку как часть значения одной ячейки.<br/> когда для него верно [Style.quote_prefix](/cells/python-net/ru/aspose.cells/style#quote_prefix). Значение по умолчанию — ложь.|
| [export_all_sheets](/cells/python-net/ru/aspose.cells/txtsaveoptions/export_all_sheets) |Указывает, экспортируются ли все листы в текстовый файл.<br/> Если это неверно, экспортируйте только активный лист, как в MS Excel.|



###  Смотрите также
* модуль [aspose.cells](..)
* класс [SaveOptions](/cells/python-net/ru/aspose.cells/saveoptions)
* класс [TxtSaveOptions](/cells/python-net/ru/aspose.cells/txtsaveoptions)
