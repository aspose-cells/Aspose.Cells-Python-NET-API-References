---
title: PdfSaveOptions класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 1220
url: /ru/aspose.cells/pdfsaveoptions/
is_root: false
---
##  PdfSaveOptions класс
Представляет параметры сохранения файла PDF.



**Наследование:** [`PdfSaveOptions`](/cells/python-net/aspose.cells/pdfsaveoptions) → 
[`PaginatedSaveOptions`](/cells/python-net/aspose.cells/paginatedsaveoptions) → 
[`SaveOptions`](/cells/python-net/ru/aspose.cells/saveoptions)



Тип PdfSaveOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [__init__](/cells/python-net/ru/aspose.cells/pdfsaveoptions/__init__/#) | Создает параметры для сохранения файла PDF.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [save_format](/cells/python-net/ru/aspose.cells/pdfsaveoptions/save_format) | Получает формат файла сохранения.|
| [clear_data](/cells/python-net/ru/aspose.cells/pdfsaveoptions/clear_data) | Сделайте книгу пустой после сохранения файла.|
| [cached_file_folder](/cells/python-net/ru/aspose.cells/pdfsaveoptions/cached_file_folder) | Папка с кэшированными файлами используется для хранения больших данных.|
| [validate_merged_areas](/cells/python-net/ru/aspose.cells/pdfsaveoptions/validate_merged_areas) | Указывает, следует ли проверять объединенные ячейки перед сохранением файла.|
| [merge_areas](/cells/python-net/ru/aspose.cells/pdfsaveoptions/merge_areas) | Указывает, нужно ли объединять области условного форматирования и проверки перед сохранением файла.|
| [create_directory](/cells/python-net/ru/aspose.cells/pdfsaveoptions/create_directory) | Если это правда и каталог не существует, каталог будет автоматически создан перед сохранением файла.|
| [sort_names](/cells/python-net/ru/aspose.cells/pdfsaveoptions/sort_names) | Указывает, выполняется ли сортировка определенных имен перед сохранением файла.|
| [sort_external_names](/cells/python-net/ru/aspose.cells/pdfsaveoptions/sort_external_names) | Указывает, следует ли сортировать внешние определенные имена перед сохранением файла.|
| [refresh_chart_cache](/cells/python-net/ru/aspose.cells/pdfsaveoptions/refresh_chart_cache) | Указывает, обновляются ли данные кэша диаграммы.|
| [warning_callback](/cells/python-net/ru/aspose.cells/pdfsaveoptions/warning_callback) | Получает или задает обратный вызов с предупреждением.|
| [update_smart_art](/cells/python-net/ru/aspose.cells/pdfsaveoptions/update_smart_art) | Указывает, обновляются ли настройки Smart Art.<br/> Значение по умолчанию неверно.|
| [default_font](/cells/python-net/ru/aspose.cells/pdfsaveoptions/default_font) | Если символы в Excel имеют формат Unicode и не имеют правильного шрифта в стиле ячейки,<br/>Они могут отображаться как блоки в формате pdf, изображения.<br/>Установите DefaultFont, например MingLiu или MS Gothic, чтобы отобразить эти символы.<br/> Если это свойство не установлено, Aspose.Cells будет использовать системный шрифт по умолчанию для отображения этих символов Юникода.|
| [check_workbook_default_font](/cells/python-net/ru/aspose.cells/pdfsaveoptions/check_workbook_default_font) | Если символы в Excel имеют формат Unicode и не имеют правильного шрифта в стиле ячейки,<br/>Они могут отображаться как блоки в формате pdf, изображения.<br/> Установите для этого параметра значение true, чтобы попытаться использовать шрифт книги по умолчанию для отображения этих символов в первую очередь.|
| [check_font_compatibility](/cells/python-net/ru/aspose.cells/pdfsaveoptions/check_font_compatibility) | Указывает, следует ли проверять совместимость шрифтов для каждого символа в тексте.|
| [is_font_substitution_char_granularity](/cells/python-net/ru/aspose.cells/pdfsaveoptions/is_font_substitution_char_granularity) |Указывает, следует ли заменять шрифт символа только в том случае, если шрифт ячейки несовместим с ним.|
| [one_page_per_sheet](/cells/python-net/ru/aspose.cells/pdfsaveoptions/one_page_per_sheet) | Если OnePagePerSheet имеет значение true , все содержимое одного листа в результате будет выведено только на одну страницу.<br/> Размер бумаги в настройках страницы будет недействительным, а другие настройки страницы<br/> все равно вступит в силу.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/ru/aspose.cells/pdfsaveoptions/all_columns_in_one_page_per_sheet) | Если AllColumnsInOnePagePerSheet имеет значение true , все содержимое столбцов одного листа будет выводиться только на одну страницу.<br/> Ширина бумаги, указанная в настройках страницы, будет игнорироваться, а другие настройки страницы будут игнорироваться.<br/> все равно вступит в силу.|
| [ignore_error](/cells/python-net/ru/aspose.cells/pdfsaveoptions/ignore_error) | Указывает, нужно ли скрыть ошибку при рендеринге.<br/> Ошибка может заключаться в ошибке формы, изображения, отрисовки диаграммы и т. д.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/ru/aspose.cells/pdfsaveoptions/output_blank_page_when_nothing_to_print) | Указывает, выводить ли пустую страницу, если печатать нечего.|
| [page_index](/cells/python-net/ru/aspose.cells/pdfsaveoptions/page_index) | Получает или задает индекс первой сохраняемой страницы, отсчитываемый от 0.|
| [page_count](/cells/python-net/ru/aspose.cells/pdfsaveoptions/page_count) | Получает или задает количество сохраняемых страниц.|
| [printing_page_type](/cells/python-net/ru/aspose.cells/pdfsaveoptions/printing_page_type) | Указывает, какие страницы не будут распечатаны.|
| [gridline_type](/cells/python-net/ru/aspose.cells/pdfsaveoptions/gridline_type) | Получает или задает тип линии сетки.|
| [text_cross_type](/cells/python-net/ru/aspose.cells/pdfsaveoptions/text_cross_type) | Получает или задает отображаемый тип текста, когда ширина текста больше ширины ячейки.|
| [default_edit_language](/cells/python-net/ru/aspose.cells/pdfsaveoptions/default_edit_language) | Получает или задает язык редактирования по умолчанию.|
| [sheet_set](/cells/python-net/ru/aspose.cells/pdfsaveoptions/sheet_set) |Получает или задает листы для визуализации. По умолчанию — все видимые листы в книге: [`SheetSet.visible`](/cells/python-net/ru/aspose.cells.rendering/sheetset#visible).|
| [draw_object_event_handler](/cells/python-net/ru/aspose.cells/pdfsaveoptions/draw_object_event_handler) | Реализует этот интерфейс для получения DrawObject и Bound при рендеринге.|
| [page_saving_callback](/cells/python-net/ru/aspose.cells/pdfsaveoptions/page_saving_callback) | Контролируйте/отображайте ход процесса сохранения страницы.|
| [emf_render_setting](/cells/python-net/ru/aspose.cells/pdfsaveoptions/emf_render_setting) | Настройка рендеринга метафайла Emf.|
| [embed_standard_windows_fonts](/cells/python-net/ru/aspose.cells/pdfsaveoptions/embed_standard_windows_fonts) | True для встраивания шрифтов истинного типа.<br/>Влияет только на символы ASCII 32–127.<br/>Шрифты для кодов символов больше 127 всегда встроены.<br/>Шрифты всегда встроены для стандарта PDF/A-1a, PDF/A-1b.<br/> По умолчанию верно.|
| [bookmark](/cells/python-net/ru/aspose.cells/pdfsaveoptions/bookmark) | Получает и задает объект [`PdfBookmarkEntry`](/cells/python-net/ru/aspose.cells.rendering/pdfbookmarkentry).|
| [compliance](/cells/python-net/ru/aspose.cells/pdfsaveoptions/compliance) | Получает или задает уровень соответствия стандартам PDF для выходных документов.|
| [security_options](/cells/python-net/ru/aspose.cells/pdfsaveoptions/security_options) | Установите эти параметры, если в результате xls2pdf требуется безопасность.|
| [image_type](/cells/python-net/ru/aspose.cells/pdfsaveoptions/image_type) |Представляет тип изображения при преобразовании диаграммы и фигуры.|
| [calculate_formula](/cells/python-net/ru/aspose.cells/pdfsaveoptions/calculate_formula) | Указывает, следует ли вычислять формулы перед сохранением файла PDF.|
| [pdf_compression](/cells/python-net/ru/aspose.cells/pdfsaveoptions/pdf_compression) | Укажите алгоритм сжатия|
| [created_time](/cells/python-net/ru/aspose.cells/pdfsaveoptions/created_time) | Получает и устанавливает время создания PDF-документа.|
| [producer](/cells/python-net/ru/aspose.cells/pdfsaveoptions/producer) | Получает и устанавливает производителя созданного PDF-документа.|
| [optimization_type](/cells/python-net/ru/aspose.cells/pdfsaveoptions/optimization_type) | Получает и устанавливает тип оптимизации PDF.|
| [custom_properties_export](/cells/python-net/ru/aspose.cells/pdfsaveoptions/custom_properties_export) | Получает или задает значение, определяющее способ экспорта [`CustomDocumentPropertyCollection`](/cells/python-net/ru/aspose.cells.properties/customdocumentpropertycollection) в файл PDF. Значение по умолчанию — Нет.|
| [export_document_structure](/cells/python-net/ru/aspose.cells/pdfsaveoptions/export_document_structure) | Указывает, экспортировать ли структуру документа.|
| [display_doc_title](/cells/python-net/ru/aspose.cells/pdfsaveoptions/display_doc_title) | Указывает, должен ли заголовок окна отображать заголовок документа.|
| [font_encoding](/cells/python-net/ru/aspose.cells/pdfsaveoptions/font_encoding) | Получает или задает кодировку встроенного шрифта в PDF.|
| [watermark](/cells/python-net/ru/aspose.cells/pdfsaveoptions/watermark) | Получает или задает водяной знак для вывода.|


###  Методы
| Метод| Описание|
| :- | :- |
| [set_image_resample](/cells/python-net/ru/aspose.cells/pdfsaveoptions/set_image_resample/#int-int) | Устанавливает желаемое PPI (пикселей на дюйм) изображений с повторной выборкой и качество JPEG.<br/> Все изображения будут преобразованы в JPEG с указанными настройками качества.<br/> и изображения, размер которых превышает указанное значение PPI (пикселей на дюйм), будут подвергнуты повторной выборке.|



###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`CustomDocumentPropertyCollection`](/cells/python-net/ru/aspose.cells.properties/customdocumentpropertycollection)
* класс [`PaginatedSaveOptions`](/cells/python-net/ru/aspose.cells/paginatedsaveoptions)
* класс [`PdfBookmarkEntry`](/cells/python-net/ru/aspose.cells.rendering/pdfbookmarkentry)
* класс [`PdfSaveOptions`](/cells/python-net/ru/aspose.cells/pdfsaveoptions)
* класс [`SaveOptions`](/cells/python-net/ru/aspose.cells/saveoptions)
