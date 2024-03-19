---
title: PptxSaveOptions класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 1230
url: /ru/aspose.cells/pptxsaveoptions/
is_root: false
---
##  PptxSaveOptions класс
Представляет параметры сохранения pptx.



**Наследование:** [`PptxSaveOptions`](/cells/python-net/aspose.cells/pptxsaveoptions) → 
[`PaginatedSaveOptions`](/cells/python-net/aspose.cells/paginatedsaveoptions) → 
[`SaveOptions`](/cells/python-net/ru/aspose.cells/saveoptions)



Тип PptxSaveOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [__init__](/cells/python-net/ru/aspose.cells/pptxsaveoptions/__init__/#) | Представляет параметры сохранения pptx.|
| [__init__](/cells/python-net/ru/aspose.cells/pptxsaveoptions/__init__/#bool) | Представляет параметры сохранения файла .pptx.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [save_format](/cells/python-net/ru/aspose.cells/pptxsaveoptions/save_format) | Получает формат файла сохранения.|
| [clear_data](/cells/python-net/ru/aspose.cells/pptxsaveoptions/clear_data) | Сделайте книгу пустой после сохранения файла.|
| [cached_file_folder](/cells/python-net/ru/aspose.cells/pptxsaveoptions/cached_file_folder) | Папка с кэшированными файлами используется для хранения больших данных.|
| [validate_merged_areas](/cells/python-net/ru/aspose.cells/pptxsaveoptions/validate_merged_areas) | Указывает, следует ли проверять объединенные ячейки перед сохранением файла.|
| [merge_areas](/cells/python-net/ru/aspose.cells/pptxsaveoptions/merge_areas) | Указывает, нужно ли объединять области условного форматирования и проверки перед сохранением файла.|
| [create_directory](/cells/python-net/ru/aspose.cells/pptxsaveoptions/create_directory) | Если это правда и каталог не существует, каталог будет автоматически создан перед сохранением файла.|
| [sort_names](/cells/python-net/ru/aspose.cells/pptxsaveoptions/sort_names) | Указывает, выполняется ли сортировка определенных имен перед сохранением файла.|
| [sort_external_names](/cells/python-net/ru/aspose.cells/pptxsaveoptions/sort_external_names) | Указывает, следует ли сортировать внешние определенные имена перед сохранением файла.|
| [refresh_chart_cache](/cells/python-net/ru/aspose.cells/pptxsaveoptions/refresh_chart_cache) | Указывает, обновляются ли данные кэша диаграммы.|
| [warning_callback](/cells/python-net/ru/aspose.cells/pptxsaveoptions/warning_callback) | Получает или задает обратный вызов с предупреждением.|
| [update_smart_art](/cells/python-net/ru/aspose.cells/pptxsaveoptions/update_smart_art) | Указывает, обновляются ли настройки Smart Art.<br/> Значение по умолчанию неверно.|
| [default_font](/cells/python-net/ru/aspose.cells/pptxsaveoptions/default_font) | Если символы в Excel имеют формат Unicode и не имеют правильного шрифта в стиле ячейки,<br/>Они могут отображаться как блоки в формате pdf, изображения.<br/>Установите DefaultFont, например MingLiu или MS Gothic, чтобы отобразить эти символы.<br/> Если это свойство не установлено, Aspose.Cells будет использовать системный шрифт по умолчанию для отображения этих символов Юникода.|
| [check_workbook_default_font](/cells/python-net/ru/aspose.cells/pptxsaveoptions/check_workbook_default_font) | Если символы в Excel имеют формат Unicode и не имеют правильного шрифта в стиле ячейки,<br/>Они могут отображаться как блоки в формате pdf, изображения.<br/> Установите для этого параметра значение true, чтобы попытаться использовать шрифт книги по умолчанию для отображения этих символов в первую очередь.|
| [check_font_compatibility](/cells/python-net/ru/aspose.cells/pptxsaveoptions/check_font_compatibility) | Указывает, следует ли проверять совместимость шрифтов для каждого символа в тексте.|
| [is_font_substitution_char_granularity](/cells/python-net/ru/aspose.cells/pptxsaveoptions/is_font_substitution_char_granularity) |Указывает, следует ли заменять шрифт символа только в том случае, если шрифт ячейки несовместим с ним.|
| [one_page_per_sheet](/cells/python-net/ru/aspose.cells/pptxsaveoptions/one_page_per_sheet) | Если OnePagePerSheet имеет значение true , все содержимое одного листа в результате будет выведено только на одну страницу.<br/> Размер бумаги в настройках страницы будет недействительным, а другие настройки страницы<br/> все равно вступит в силу.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/ru/aspose.cells/pptxsaveoptions/all_columns_in_one_page_per_sheet) | Если AllColumnsInOnePagePerSheet имеет значение true , все содержимое столбцов одного листа будет выводиться только на одну страницу.<br/> Ширина бумаги, указанная в настройках страницы, будет игнорироваться, а другие настройки страницы будут игнорироваться.<br/> все равно вступит в силу.|
| [ignore_error](/cells/python-net/ru/aspose.cells/pptxsaveoptions/ignore_error) | Указывает, нужно ли скрыть ошибку при рендеринге.<br/> Ошибка может заключаться в ошибке формы, изображения, отрисовки диаграммы и т. д.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/ru/aspose.cells/pptxsaveoptions/output_blank_page_when_nothing_to_print) | Указывает, выводить ли пустую страницу, если печатать нечего.|
| [page_index](/cells/python-net/ru/aspose.cells/pptxsaveoptions/page_index) | Получает или задает индекс первой сохраняемой страницы, отсчитываемый от 0.|
| [page_count](/cells/python-net/ru/aspose.cells/pptxsaveoptions/page_count) | Получает или задает количество сохраняемых страниц.|
| [printing_page_type](/cells/python-net/ru/aspose.cells/pptxsaveoptions/printing_page_type) | Указывает, какие страницы не будут распечатаны.|
| [gridline_type](/cells/python-net/ru/aspose.cells/pptxsaveoptions/gridline_type) | Получает или задает тип линии сетки.|
| [text_cross_type](/cells/python-net/ru/aspose.cells/pptxsaveoptions/text_cross_type) | Получает или задает отображаемый тип текста, когда ширина текста больше ширины ячейки.|
| [default_edit_language](/cells/python-net/ru/aspose.cells/pptxsaveoptions/default_edit_language) | Получает или задает язык редактирования по умолчанию.|
| [sheet_set](/cells/python-net/ru/aspose.cells/pptxsaveoptions/sheet_set) |Получает или задает листы для визуализации. По умолчанию — все видимые листы в книге: [`SheetSet.visible`](/cells/python-net/ru/aspose.cells.rendering/sheetset#visible).|
| [draw_object_event_handler](/cells/python-net/ru/aspose.cells/pptxsaveoptions/draw_object_event_handler) | Реализует этот интерфейс для получения DrawObject и Bound при рендеринге.|
| [page_saving_callback](/cells/python-net/ru/aspose.cells/pptxsaveoptions/page_saving_callback) | Контролируйте/отображайте ход процесса сохранения страницы.|
| [emf_render_setting](/cells/python-net/ru/aspose.cells/pptxsaveoptions/emf_render_setting) | Настройка рендеринга метафайла Emf.|
| [ignore_hidden_rows](/cells/python-net/ru/aspose.cells/pptxsaveoptions/ignore_hidden_rows) | Указывает, игнорируются ли скрытые строки при преобразовании Excel в PowerPoint.|
| [adjust_font_size_for_row_type](/cells/python-net/ru/aspose.cells/pptxsaveoptions/adjust_font_size_for_row_type) | Указывает, какой тип строки необходимо изменить, размер шрифта, если высота строки мала.|
| [export_view_type](/cells/python-net/ru/aspose.cells/pptxsaveoptions/export_view_type) | Получает и задает тип отображения при экспорте в номер PowerPoint.<br/> Тип экспорта по умолчанию работает как печать.|



###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`PaginatedSaveOptions`](/cells/python-net/ru/aspose.cells/paginatedsaveoptions)
* класс [`PptxSaveOptions`](/cells/python-net/ru/aspose.cells/pptxsaveoptions)
* класс [`SaveOptions`](/cells/python-net/ru/aspose.cells/saveoptions)
