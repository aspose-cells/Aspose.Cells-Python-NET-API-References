---
title: DocxSaveOptions класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 510
url: /ru/aspose.cells/docxsaveoptions/
is_root: false
---
##  DocxSaveOptions класс
Представляет параметры сохранения файла .docx.



**Наследование:** [`DocxSaveOptions`](/cells/python-net/aspose.cells/docxsaveoptions) → 
[`PaginatedSaveOptions`](/cells/python-net/aspose.cells/paginatedsaveoptions) → 
[`SaveOptions`](/cells/python-net/ru/aspose.cells/saveoptions)



Тип DocxSaveOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [__init__](/cells/python-net/ru/aspose.cells/docxsaveoptions/__init__/#) | Представляет параметры сохранения файла .docx.|
| [__init__](/cells/python-net/ru/aspose.cells/docxsaveoptions/__init__/#bool) | Представляет параметры сохранения файла .docx.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [save_format](/cells/python-net/ru/aspose.cells/docxsaveoptions/save_format) | Получает формат файла сохранения.|
| [clear_data](/cells/python-net/ru/aspose.cells/docxsaveoptions/clear_data) | Сделайте книгу пустой после сохранения файла.|
| [cached_file_folder](/cells/python-net/ru/aspose.cells/docxsaveoptions/cached_file_folder) | Папка с кэшированными файлами используется для хранения больших данных.|
| [validate_merged_areas](/cells/python-net/ru/aspose.cells/docxsaveoptions/validate_merged_areas) | Указывает, следует ли проверять объединенные ячейки перед сохранением файла.|
| [merge_areas](/cells/python-net/ru/aspose.cells/docxsaveoptions/merge_areas) | Указывает, нужно ли объединять области условного форматирования и проверки перед сохранением файла.|
| [create_directory](/cells/python-net/ru/aspose.cells/docxsaveoptions/create_directory) | Если это правда и каталог не существует, каталог будет автоматически создан перед сохранением файла.|
| [sort_names](/cells/python-net/ru/aspose.cells/docxsaveoptions/sort_names) | Указывает, выполняется ли сортировка определенных имен перед сохранением файла.|
| [sort_external_names](/cells/python-net/ru/aspose.cells/docxsaveoptions/sort_external_names) | Указывает, следует ли сортировать внешние определенные имена перед сохранением файла.|
| [refresh_chart_cache](/cells/python-net/ru/aspose.cells/docxsaveoptions/refresh_chart_cache) | Указывает, обновляются ли данные кэша диаграммы.|
| [warning_callback](/cells/python-net/ru/aspose.cells/docxsaveoptions/warning_callback) | Получает или задает обратный вызов с предупреждением.|
| [update_smart_art](/cells/python-net/ru/aspose.cells/docxsaveoptions/update_smart_art) | Указывает, обновляются ли настройки Smart Art.<br/> Значение по умолчанию неверно.|
| [default_font](/cells/python-net/ru/aspose.cells/docxsaveoptions/default_font) | Если символы в Excel имеют формат Unicode и не имеют правильного шрифта в стиле ячейки,<br/>Они могут отображаться как блоки в формате pdf, изображения.<br/>Установите DefaultFont, например MingLiu или MS Gothic, чтобы отобразить эти символы.<br/> Если это свойство не установлено, Aspose.Cells будет использовать системный шрифт по умолчанию для отображения этих символов Юникода.|
| [check_workbook_default_font](/cells/python-net/ru/aspose.cells/docxsaveoptions/check_workbook_default_font) | Если символы в Excel имеют формат Unicode и не имеют правильного шрифта в стиле ячейки,<br/>Они могут отображаться как блоки в формате pdf, изображения.<br/> Установите для этого параметра значение true, чтобы попытаться использовать шрифт книги по умолчанию для отображения этих символов в первую очередь.|
| [check_font_compatibility](/cells/python-net/ru/aspose.cells/docxsaveoptions/check_font_compatibility) | Указывает, следует ли проверять совместимость шрифтов для каждого символа в тексте.|
| [is_font_substitution_char_granularity](/cells/python-net/ru/aspose.cells/docxsaveoptions/is_font_substitution_char_granularity) |Указывает, следует ли заменять шрифт символа только в том случае, если шрифт ячейки несовместим с ним.|
| [one_page_per_sheet](/cells/python-net/ru/aspose.cells/docxsaveoptions/one_page_per_sheet) | Если OnePagePerSheet имеет значение true , все содержимое одного листа в результате будет выведено только на одну страницу.<br/> Размер бумаги в настройках страницы будет недействительным, а другие настройки страницы<br/> все равно вступит в силу.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/ru/aspose.cells/docxsaveoptions/all_columns_in_one_page_per_sheet) | Если AllColumnsInOnePagePerSheet имеет значение true , все содержимое столбцов одного листа будет выводиться только на одну страницу.<br/> Ширина бумаги, указанная в настройках страницы, будет игнорироваться, а другие настройки страницы будут игнорироваться.<br/> все равно вступит в силу.|
| [ignore_error](/cells/python-net/ru/aspose.cells/docxsaveoptions/ignore_error) | Указывает, нужно ли скрыть ошибку при рендеринге.<br/> Ошибка может заключаться в ошибке формы, изображения, отрисовки диаграммы и т. д.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/ru/aspose.cells/docxsaveoptions/output_blank_page_when_nothing_to_print) | Указывает, выводить ли пустую страницу, если печатать нечего.|
| [page_index](/cells/python-net/ru/aspose.cells/docxsaveoptions/page_index) | Получает или задает индекс первой сохраняемой страницы, отсчитываемый от 0.|
| [page_count](/cells/python-net/ru/aspose.cells/docxsaveoptions/page_count) | Получает или задает количество сохраняемых страниц.|
| [printing_page_type](/cells/python-net/ru/aspose.cells/docxsaveoptions/printing_page_type) | Указывает, какие страницы не будут распечатаны.|
| [gridline_type](/cells/python-net/ru/aspose.cells/docxsaveoptions/gridline_type) | Получает или задает тип линии сетки.|
| [text_cross_type](/cells/python-net/ru/aspose.cells/docxsaveoptions/text_cross_type) | Получает или задает отображаемый тип текста, когда ширина текста больше ширины ячейки.|
| [default_edit_language](/cells/python-net/ru/aspose.cells/docxsaveoptions/default_edit_language) | Получает или задает язык редактирования по умолчанию.|
| [sheet_set](/cells/python-net/ru/aspose.cells/docxsaveoptions/sheet_set) |Получает или задает листы для визуализации. По умолчанию — все видимые листы в книге: [`SheetSet.visible`](/cells/python-net/ru/aspose.cells.rendering/sheetset#visible).|
| [draw_object_event_handler](/cells/python-net/ru/aspose.cells/docxsaveoptions/draw_object_event_handler) | Реализует этот интерфейс для получения DrawObject и Bound при рендеринге.|
| [page_saving_callback](/cells/python-net/ru/aspose.cells/docxsaveoptions/page_saving_callback) | Контролируйте/отображайте ход процесса сохранения страницы.|
| [emf_render_setting](/cells/python-net/ru/aspose.cells/docxsaveoptions/emf_render_setting) | Настройка рендеринга метафайла Emf.|



###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`DocxSaveOptions`](/cells/python-net/ru/aspose.cells/docxsaveoptions)
* класс [`PaginatedSaveOptions`](/cells/python-net/ru/aspose.cells/paginatedsaveoptions)
* класс [`SaveOptions`](/cells/python-net/ru/aspose.cells/saveoptions)
